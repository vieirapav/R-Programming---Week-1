---Tipos de Matriz---


Matrizes são vetores com duas dimensões (e por isso só possuem elementos de uma mesma classe).

  
  Como criar uma mtriz:
  
>m <- matrix(nrow = 2, ncol = 3)
>m
      [,1] [,2] [,3]
[1,]   NA   NA   NA
[2,]   NA   NA   NA

>attributes(m)
$dim
[1]2 3

#Com **attribtes(m)** é possivel decobrir A **dimensão = dim** da matriz de "m".

>m <- matrix(1:6, nrow = 2, ncol = 3)
>m
      [,1] [,2] [,3]
[1,]   1     3    5
[2,]   2     4    6

#Ao determinar a sequencia e o n° de colunas e linhas essa é a maneira que os valores irão se ajustar

---Outras formas de criar matriz---
  
  
  1° Adicionar uma dimensão no vetor:

>p <- 1:10
>p
[1] 1 2 3 4 5 6 7 8 9 10

>dim(p) <- c(2, p5) 
> p
     [,1] [,2] [,3] [,4] [,5]
[1,]    1    3    5    7    9
[2,]    2    4    6    8   10

A funçăo **dim()** retorna a dimensăo do objeto.


    2°cbind e rbind
    
    
> r <- 1:3
> s <- 10:12

#cria **coluna** "r" e "s"

> cbind(r, s)
     r  s
[1,] 1 10
[2,] 2 11
[3,] 3 12


#cria **linha** "r" e "s"

>rbind(r, s)
 [,1] [,2] [,3]
r    1    2    3
s   10   11   12

