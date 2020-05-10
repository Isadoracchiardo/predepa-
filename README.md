# predepa-
Ejercicios clases 

varbleUno<-2
varbleUno
varbleUno<-3
varbleUno
varidos<-5
varidos
x<-3
y<-7
x<y 
x>y
x<4
x<=3
x<3
x==3
y==6
TRUE && TRUE  
TRUE && FALSE
FALSE && FALSE
TRUE || FALSE
T || T 
F || T
x<y & F
y<x & F
y<x & (y>x)
x<y & (y>x)
(x<y) | (y>x) & varidos>varbleUno
x + y 
x^(1/4)
5%%5
5 %% 4

x<-6
##como se calcula un numero par e impar 
x %% 2 == 0

x<-5 
x %% 2 == 0 
r<-x %% 2 == 0

__________________________________

#ejemplos clases.

numerador <- 6
denominador <- 4
r <- numerador/denominador
r
r <- sqrt(4)
r
suma <- function(x,y) {
  r <- x+y
  return(r)
}
r <- suma (2,3)
r

#escriba una funcion que retorne true o false cuando un numero es par o impar 
npar <- function(x){
  r <-  x %% 2 == 0
  return(r)
}
npar(3)
npar(8)

#calcular area de un cuadrado 

area.cuadrado <- function(lado1){
  area <- (lado1*lado1)
  return(area)
}
area.cuadrado(5)

area.cuadrado <- function(lado1){
  area <- (lado1^2)
  return(area)
}
area.cuadrado(3)

area.rectangulo <- function(largo, ancho){
  area <- ancho*largo
  return(area)
}
area.rectangulo(2,3)

diferencia.area <-function(lado1,lado2){
lado1 <- area1(lado1*lado1)
lado2 <- area2(lado2*lado2)
return(abs(area1-area2))
}