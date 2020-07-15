---Criando Vetores---
A função "c ()" pode ser usada para criar vetores de objetos

x <- c(0.5, 0.6) #numeric
x <- c(TREU, FALSE) #logical
x <- c(T, F) #logical
x <- c("a", "b", "c") #character
x <- 9:29 #integer
x <- c(l+,0i, 2+4i) #complex

Ao usar a função vector():
x <- vector("numeric", length = 10)
x [1] 0 0 0 0 0 0 0 0 0


Se misturando diferentes tipos de objetos no vetor?
  
y <- c(1.7, "a") #character
y <- c(True, 2) #numeric 
y <- c("a", TRUE) #character 

---Convertendo classe---
  
x <- 0:6
class(x)
[1] "integer"


#converte para numerico

as.numeric(x) 

[1] 0 1 2 3 4 5 6


#converte para logico

as.logical(x) 

[1] FALSE TRUE TRUE TRUE TRUE TRUE TRUE


#converte para caracter

as.character(x) 

[1] "0" "1" "2" "3" "4" "5" "6"

---LISTAS---

Dentro da lista é possivel colocar elementos de classes diferentes.

x <- list(1 ,"a", TRUE, 1 + 4i)

x
[[1]]
[1] 1

[[2]]
[1] "a"

[[3]]
[1] TRUE

[[4]]
[1] 1+4i

