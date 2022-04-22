Ejercicios Propuestos
1. Calcular y mostrar el cuadrado de los números del 1 a 30.
```
Algoritmo CuadradoDeNumeros
    num <- 1
    Repetir
         Escribir "El cuadrado de: " + num + "es:"
         Escribir num*num
         num <- num + 1
    Hasta que num>30
FinAlgoritmo
```
2. Números primos
3. Construir un avión de papel
```
Algoritmo AvionPapel
    Escribir "Conseguir hoja de papel" 
    Escribir "Doblar hoja de papel" 
    Escribir "Doblar lado derecho en forma de ala" 
    Escribir "Doblar lado izquierdo en forma de ala" 
    Escribir "Felicidades, Ahora tenes un avion de papel"  
FinAlgoritmo
```
4. Realizar las cuatro operaciones básicas (Suma, Resta, Multiplicación, División)
```
Algoritmo OperacionesBasicas
    Escribir "Ingrese un numero" 
    Leer nro1
    Escribir "Ingrese otro numero" 
    Leer nro2

    result<- nro1 + nro2
    Escribir "La suma es:" + result
    result<- nro1 - nro2
    Escribir "La resta es:" + result
    result<- nro1 * nro2
    Escribir "La multiplicaciom es:" + result
    result<- nro1 / nro2
    Escribir "La division es:" + result
FinAlgoritmo
```
5. Volumen y Area de un Cilindro

```
Algoritmo Cilindro
    pi<- 3.14
    Escribir "Ingrese el radio del cilindro"
    Leer r
    Escribir "Ingrese la altura del cilindro"
    Leer h

    area <- 2*(pi* r * r) + 2*(pi * r * h)
    volumen <-pi * r *r *h

    Escribir "El area del cilindro es:" + area
    Escribir "El volumen del cilindro es:" + volumen
FinAlgoritmo
```


6. Pedir un libro en una biblioteca
```
Algoritmo AvionPapel
    Escribir "Ir hasta la Biblioteca" 
    Escribir "Hablar con la Bibliotecaria" 
    Escribir "Indicar libro correspondiente" 
    Escribir "Entregar tarjeta de biblioteca" 
    Escribir "Volver a casa con el libro"  
FinAlgoritmo
```
7. Encontrar el mayor número de tres números
```
Algoritmo MayorNumero
    Escribir "Ingrese el primer numero" 
    Leer num1
    Escribir "Ingrese el segundo numero" 
    Leer num2
    Escribir "Ingrese el tercer numero" 
    Leer num3
    result<-0
    Si num1>= num2 y num1>=num3
        result<-num1
    sino si num2>= num1 y num2>=num3
            result<-num2
         sino 
            result<-num3 
         FinSi
    FinSi
    Escribir "El mayor numero es:" + result
FinAlgoritmo
```
8. Factorial de cualquier número
```
Algoritmo Factorial
    Escribir "Ingrese un numero" 
    Leer num
    cont<-1
    fact<-1
    Mientras cont< num Hacer
        fact<-fact*cont
        cont<-cont+1
    FinMientras
    Escribir "El factorial de su numero es:" + fact
FinAlgoritmo
```
9. Encontrar si un numero en mayor o menor a un número dado.
```
Algoritmo EsMayor
    Escribir "Ingrese un numero" 
    Leer num
    si num > N
        Escribir "Su numero es mayor"
    sino
        Escribir "Su numero es menor o igual a N"
    FinSi
FinAlgoritmo
```
10. Adivinar una palabra.