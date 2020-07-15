
    ---Fatores---
      
Fatores podem ser vistos como vetores de inteiros que possuem rótulos (levels). Ordenados ou não

>sexo <- c("M", "H", "H", "H", "M", "M", "H")

>fator <- as.factor(sexo)
[1] M H H H M M H
Levels: H M

#Nesse caso, foi definido o sexo como uma fator **as.factor(sexo)**, e a função **levels()** retorna os rótulos do fator:

Eles são úteis para representar uma variável categórica (nominal e ordinal). Na modelagem, eles serão tratados de maneira especial em funções como **lm()** e **glm()**.

>yesorno <- factor(c("yes", "yes", "no", " yes", "no"))

>yesorno
[1] yes yes no yes no
Levels: no yes

>table(yesorno)
 yes   no  yes 
   1    2    2

>unclass(yesorno)
[1] 3 3 2 1 2
attr(,"levels")
[1] " yes" "no"   "yes" 