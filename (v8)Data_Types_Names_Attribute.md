
    ---Nomes---


Os objetos podem ter nomes:

> names(x) <- c("foo", "bar", "norf")

> x
foo bar norf
1   2     3

> names(x)
[1] "foo" "bar" "norf"


    ---Listas recebe nome---

#Exemplo de **lista** com nome:
    
> u <- list(a = 1, b = 2, c = 3)
> u
$a
[1] 1

$b
[1] 2

$c
[1] 3

    ---Matrizes recebe nome---
    
#Exemplo de **matriz** com nome:

> m <- matrix(1:4, nrow = 2, ncol = 2)
> dimnames(m) <-list(c("a", "b"), c("c", "d"))
> m
  c d
a 1 3
b 2 4

