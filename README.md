# Deber-01
Algoritmo y logíistica
//Ejercicios-1









//Ejercicios-4
Algoritmo presentar_menor
// Ingresar tres números y presentar el menor
Definir A, B, C, M como Entero
Escribir “Ingresa el 1er número”
Leer A
Escribir “Ingresa el 2do número”
Leer B
Escribir “Ingresa el 3er número”
Leer C
Si A <= B y A <= C Entonces
   M <- A
Sino
   Si B <= A y B <= C Entonces
      M <- B
   Sino
      M <- C
   FinSi
FinSi
Escribir M, “ es el menor”
FinAlgoritmo



//Ejercicio-5
Algoritmo presentar_mayor
//Pseudocodigo que muestra el número mayor ingreso por teclado y si son iguales muestre //el cartel “Son iguales”
Definir A, B, M como enteros 
Escribir “Ingresar 1er número”
Leer A
Escribir “Ingresar 2do número”
Leer B
  Si A > B Entonces
    M<-A
  Sino
    Si A = B Entonces
      Escribir  M, “Son iguales ”
    Sino
      M<-B
    FinSi
  FinSi
Finalgoritmo 


