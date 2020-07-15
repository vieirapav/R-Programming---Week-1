   
    ---Data Frame---
    
#Tipo especial de lista, diferente da matriz, data frame pode armazenar diferentes tipos/classes de dados, inteiros, caracters etc 

Data frame são utilizados para armazenar dados em forma de tabela.

Data frame possui um atributo especial chamado: **row.names**, cada linha do fram possui um nome, pode ser util para identificar dados. Ex.: Cada linha pode representar um estudante


Data frames podem ser criados chamando as funções **read.table**, **read.csv** ou você pode usar a função **data.frame()** 

    Exemplo
> x <- data.frame(fOO = 1:4, BAR = c(T, T, F, F))

> x
  fOO   BAR
1   1  TRUE
2   2  TRUE
3   3 FALSE
4   4 FALSE

>nrow(x)
[1] 4

>ncol(x)
[1] 2