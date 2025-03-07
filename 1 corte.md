# Contenido de clase
Son los apuntes de dinamica de sistemas.
Para solucionar ecuaciones diferenciales "Transformada de Laplace"
## 1. Primer dia de clase
> *Planta:* Es todo lo fisico que esta presente en el proceso.

> *Proceso:* Es la receta de lo que va hacer.
 
> *Modelos dinámicos:* Se relaciona con la variable en función  del tiempo.
> La supoerposicion en circuitos es un sistema lineal.Usamos la transformada de laplace para pasar una ecuación diferencial y convertirla en una ecuación algebraica.
 
> *El método de la transformación de Laplace:* es una técnica para resolver ecuaciones diferenciales con condiciones iniciales.
Se usa normalmente para resolver problemas de sistemas y circuitos eléctricos.

## 2. Segundo dia de clase 
Recordamos y aprendimos a la descomposicion de fracciones parciales con los 3 casos.
### 2.1 Descomposicion de fracciones parciales
### 2.2.1 Caso 1
### 2.2.2 Caso 2
### 2.2.3 Caso 3

## 3. Tercer dia de clase
Usamos la transformada de laplace para pasar una ecuación diferencial y convertirla en una ecuación algebraica.
Tener encuenta que necesitamos conocer las condiciones generales debido a que no van hacer las mismas.
💡**Ejemplo 1:**  Si el pendulo arrancade en diferente angulo va a tener diferentes condiciones.
Las condiciones iniciales son constantes "Numeros"

💡**Ejemplo 2:** Ejercicio de La transformada de laplace $x"+2x'+5x$ con condiciones iniciales x=0 ,x'=0
$s^2(X(s))+2s((X(s))+5X(s)=3/s$, tener cuidado debido a que toca hacer la transformada a ambos lados de la ecuacion sin olvidar se de $3$ que es 3/s.

Se van a obtener terminos semejantes de X(s) y si esta multiplicando pasa a dividir como en este ejercicio. 
$X(s)=3/s(s^2+2s+5)=A/s+((Bs+D)/(s^2+2s+5))$

Toca resolverlo con caso 1 y caso 2 de descomposicion de descomposición de fracciones parciales.
Al aplicar fracciones parciales aparece un sistema de ecuaciones de 3 ecuaciones y 3 incognitas
$0=A+B$,$0=2A+D$,$3=A(5)$

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      3/5         |
|       B       |     -3/5         |
|       C       |      -6/5        |

📚

## 11. Referencias
https://sga.unemi.edu.ec/media/recursotema/Documento_2020618144651.pdf
