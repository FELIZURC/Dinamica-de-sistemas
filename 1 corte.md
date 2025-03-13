Felipe Cruz Pineda, Angie Vargas- M6A
# Clase Introductoria (Transformada de Laplace)
El presente resumen está dividido en dos partes, lo cual brinda un panorama general del curso de Dinámica de sistemas.

En primer lugar, se abordan conceptos básicos necesarios para el curso. Dando una explicación de conceptos que se utilizarán más adelante, lo cual nos da un parámetro general acerca de lo que tratará el curso.

Por otro lado, la segunda parte se centra en hacer un repaso de la transformada de Laplace, un tema clave para aplicar más adelante a los conceptos y temas que siguen en el curso.

##  1. Definiciones
>🔑 *Sistemas:* Un sistema es una combinación de componentes que actúan conjuntamente para alcanzar un objetivo específico. La combinación de componentes se puede representar por medio de reglas o principios que relacionan entradas con salidas.



<p align="center">
    <img src="./imagens/Sistema.PNG" alt="Figura de sistema" />
</p>



 
Básicamente, se nos indica que un sistema es un conjunto de pautas y reglas que trabajan en sincronia para solventar un problema y llegar a un objetivo. Este cuenta con entradas que pasan por reglas que en este caso pueden ser modelos matemáticos hasta llegar a la salida, que básicamente sería el objetivo que se quiere.

>🔑*Sistema dinámico:* Un sistema se llama dinámico si su salida en el presente depende de una entrada en el pasado.
También, si su salida en curso depende solamente de la entrada en curso, el sistema se conoce como estático.


<p align="center">
    <img src="./imagens/Sistema dinamico.PNG" alt="Figura de sistema dinamico" />
</p>



En este caso nos explica que un sistema es dinámico cuando la salida tiene dependencia de la entrada puesta anteriormente, dando así una especie de "ciclo", ya que siempre va a depender de los estados de entrada anteriores.

En este punto también nos explica que si esto no se cumple y la salida depende únicamente de la entrada propia del sistema, solo pasa a ser un sistema estático.

>🔑*Planta:* - Es todo lo físico que permite que se lleve a cabo un proceso. - Puede ser representado matemáticamente. - Puede ser representado a través de uno o varios sistemas.



Nos explica que la planta es básicamente todo lo físico y/o tangible que permite que todo el proceso se lleve a cabo.
Se suele confundir con proceso, pero sin embargo, al ver puntualmente su definición, ya se diferencia.



>🔑*Proceso:* Es la secuencia de pasos que permite el desarrollo o fabricación de un objeto o producto.
- A es el área de control que se usa como sinónimo de planta (aunque en sentido estricto no lo son).


Básicamente, el proceso es el paso a paso que se tiene en cuenta para resolver el problema o alcanzar el objetivo.

## 2. Modelos dinámicos:

En este apartado se nos explica que los modelos dinámicos son modelos matemáticos que relacionan las variables que se tengan con el tiempo y se necesita saber cuando cambian las variables de interés respecto al tiempo.  

$$f(t)$$

$$\frac{df(t)}{dt}$$

## 3. Derivada:
En este caso se nos presenta una breve descripción de la derivada como resumen de lo que ya se había visto en clases anteriores, presentada de la siguiente manera:

$$f(x)=x^2$$

$$\frac{\mathrm{df(x)} }{\mathrm{d} x}= 2x$$

💡**Ejemplo 1:**  $$\frac{\mathrm{df(2)} }{\mathrm{d} x}=2(2)= 4$$

💡**Ejemplo 2:**  $$\frac{\mathrm{df(3)} }{\mathrm{d} x}=2(3)= 6$$

💡**Ejemplo 3:**  $$\frac{\mathrm{df(0)} }{\mathrm{d} x}=2(0)= 0$$


<p align="center">
    <img src="./imagens/Derivada.PNG" alt="Figura de derivada" />
</p>

## 4. Sistemas lineales y no lineales:

### 4.1. Sistemas lineales

>🔑 *Un sistema es lineal cuando cumple con el principio de superposición*

El principio de superposición consiste en la idea de que la respuesta completa es la suma de las respuestas individuales de cada sistema

>🔑 *Un sistema es lineal también cuando tiene una proporcionalidad entre la entrada y la salida. *

Esto quiere decir que la entrada tiene que ser directamente proporcional a la salida.

### 4.2. Sistemas no lineales

>🔑 *Un sistema no lineal cuando no cumple con el principio de superposición.*

es cuando no se cumple el primer púnto de los sistemas lineales. O sea la suma de las respuestas indiciduales no es el resultado final.

## 5. Modelamiento y Validacion:
En este caso es importante validar el modelo con respecto al sistema físico que se tiene para poder comparar la salida del modelo con la salida del físico; si no coinciden, se tiene que modificar el modelo hasta que coincidan sus salidas.


## Transformada de Laplace:

>🔑 *Es un cambio de espacio geométrico del dominio del tiempo hacia el dominio de la frecuencia compleja.
>- Ecuaciones con derivadas son transformadas inecuaciones algebraicas.
>- la transformada de Laplace muestra las exponenciales y sinusoidales presentes en una señal *.


Básicamente, la transformada de Laplace es un cambio de espacio geométrico del dominio del tiempo hacia el dominio de la frecuencia compleja; también estas son ecuaciones con derivadas que pasan a ser ecuaciones algebraicas y a esto se le conoce como transformada o transformar.

  
La forma de representarla es la siguiente: 

$$x(t)--->X(s)$$

y escribe de la siguiente manera:

$$L[f(t)]$$ 

## Transformada inversa:
En este punto nos explica el paso contrario de la transformada, que es la transformada inversa; sin embargo, en la siguiente clase se va a ver más a fondo.

se representa de la siguiente manera:

$$X(s)--->x(t)$$

y se escribe de la siguiente manera:

$$L^(-1) [f(t)]$$

## Tabla de transformadas:

A continuación se presentará una tabla de transformadas, la cual nos ayudará a resolver y a dar respuesta básicamente a los ejercicios planteados.

<p align="center">
    <img src="./imagens/Transformada de Laplace.PNG" alt="Figura de tabla de transformada" />
</p>

## Conclusiones:
Este resumen ofrece una visión general del contenido del curso, incluyendo conceptos previamente conocidos y otros menos familiares, pero fundamentales para el desarrollo de la carrera.

Además, el resumen destaca cómo se pueden aplicar estos conceptos dentro de la materia. En el contexto de la dinámica de sistemas, se abordan temas como la definición de sistemas, modelos matemáticos, la transformada (principal ecuación que será empleada en el curso), procesos, su alcance y la comprensión de lo que implica una planta. Estos conceptos son esenciales y deberán considerarse cuidadosamente a lo largo del curso.

## Referencias:
https://acrobat.adobe.com/id/urn:aaid:sc:US:13513667-a82b-4d72-bbe1-81339126a05d
https://www.canva.com/design/DAGWSRhEhjU/4UJ2cu8t_VBxrxqtgmSBPA/edit
https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/dinamica_de_sistemas.pdf


# Contenido de clase
Son los apuntes de dinamica de sistemas Felipe Cruz Pineda y Angi Vanesa Vargas.
Para solucionar ecuaciones diferenciales "Transformada de Laplace"
## 1. Primer dia de clase
> *Planta:* Es todo lo fisico que esta presente en el proceso.

> *Proceso:* Es la receta de lo que va hacer.
 
> *Modelos dinámicos:* Se relaciona con la variable en función  del tiempo.
> La supoerposicion en circuitos es un sistema lineal.Usamos la transformada de laplace para pasar una ecuación diferencial y convertirla en una ecuación algebraica.
 
> *El método de la transformación de Laplace:* es una técnica para resolver ecuaciones diferenciales con condiciones iniciales.
Se usa normalmente para resolver problemas de sistemas y circuitos eléctricos.
> 
>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Transformadas%20de%20Laplace.png))


## 2. Segundo dia de clase 
Recordamos y aprendimos a la descomposicion de fracciones parciales con los 3 casos.
### 2.1 Descomposicion de fracciones parciales
> 🔑*Caso 1*: Q(s) tiene raíces reales distintas.
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

>
> Entonces,
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" title="\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" border="0" /></a>
</center>

> 🔑*Caso 2*:Que N tiene raices reales repetidos.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

> 🔑*Caso 3*: Q(s), tiene raices complejas conjugadas.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

📚 **Ejercicio 1:** $F=(3s+2)/(s(s+1)*(s-2))$

💡**Código 1:**
```
syms s t
F=(3s+2)/(s(s+1)*(s-2))
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |       -1         |
|       B       |       4/3        |
|       C       |       −1/3       |


>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_1_github_page-0001.jpg))

** Resultado ejercicio 1 :** (4*exp(2*t))/3 - exp(-t)/3 - 1

📚 **Ejercicio 2:** $F=(s-2)/((2s-1)^2*(s-1))$
💡**Código 2:**
```
syms s t
F=(s-2)/((2*s-1)^2*(s-1))
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        2         |
|       B       |        3         |
|       C       |        -1        |

>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_2_page-0001.jpg))

** Resultado ejercicio 2 :**exp(t/2) - exp(t) + (3*t*exp(t/2))/4

📚 **Ejercicio 3:** $F=(2s-3)/(s^3+s)$
```
syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        3         |
|       B       |        2         |
|       C       |        -3        |

>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_3_page-0001.jpg))

** Resultado ejercicio 3 :** 3*cos(t) + 2*sin(t) - 3

## 3. Tercer día de clase
Aprendimos a la descomposicion de fracciones parciales con los 3 casos. También se comprendio que es muy importandte el discriminante lo importante sobre las soluciones, debido a la clasificación de las soluciones de la ecuación cuadrática de la siguiente manera:

Si el discriminante, $d>0$, habrá dos soluciones distintas.
Si el discriminante, $d=0$, habrá una sola solución.
Si el discriminante, $d<0$, no hay soluciones reales, pero sí hay soluciones compleja.

🔑*Caso 1*: Raíces reales diferentes

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}"><img src="http://www.alciro.org/cgi/tex.cgi?G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" title="G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" border="0" /></a>
</center>

🔑*Caso 2*: Raíces reales iguales

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}" title="\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}" border="0" />
</a>
</center>


🔑*Caso 3*: Raíces complejas conjugadas
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}" title="\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}" border="0" />
</a>
</center>

📚 **Ejercicio 3:** $F=(2s-3)/(s^3+s)$
```
syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        1/2       |
|       B       |      -7/2        |
|       C       |       -5/2       |

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.1_page-0001.jpg))

** Resultado ejercicio 1:  2*exp(-t) - 6*exp(-2*t) - 8*t*exp(-2*t)
📚 **Ejercicio 3:** F=(3*s+8)/(s^2+2*s+5)

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.3_page-0001.jpg))

** Resultado ejercicio 3 :** 3*exp(-t)*(cos(2*t) + (5*sin(2*t))/6)

## 4. Cuarto día de clase
Usamos la transformada de laplace para pasar una ecuación diferencial y convertirla en una ecuación algebraica.
Tener encuenta que necesitamos conocer las condiciones generales debido a que pueden ser las mismas o no.
Transformada de una funcion "Esto lo vimos el primer dia pero la explicación fue en esta clase ":

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L\left\{ f(t) \right\}"><img src="http://www.alciro.org/cgi/tex.cgi?L\left\{ f(t) \right\}" title="L\left\{ f(t) \right\}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L\left\{ f'(t) \right\}=sF(S)-f(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L\left\{ f'(t) \right\}=sF(S)-f(0)" title="L\left\{ f'(t) \right\}=sF(S)-f(0)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L\left\{ f^{(2)}(t) \right\}=s^2F(S)-f(0)-f'(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L\left\{ f^{(2)}(t) \right\}=s^2F(S)-f(0)-f'(0)" title="L\left\{ f^{(2)}(t) \right\}=s^2F(S)-f(0)-f'(0)" border="0" /></a>

💡**Ejemplo 1:**  Si el pendulo arrancade en diferente angulo va a tener diferentes condiciones.
Las condiciones iniciales son constantes "Numeros"

💡**Ejemplo 2:** Ejercicio de La transformada de laplace $x"+2x'+5x$ con condiciones iniciales x=0 ,x'=0.
$s^2(X(s))+2s((X(s))+5X(s)=3/s$, tener cuidado debido a que toca hacer la transformada a ambos lados de la ecuacion sin olvidar se de $3$ que es 3/s.

Se van a obtener terminos semejantes de X(s) y si esta multiplicando pasa a dividir como en este ejercicio. 

Toca resolverlo con caso 1 y caso 2 de descomposicion de descomposición de fracciones parciales.
Al aplicar fracciones parciales aparece un sistema de ecuaciones de 3 ecuaciones y 3 incognitas

$0=A+B$,
$0=2A+D$,
$3=A(5)$,

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      3/5         |
|       B       |     -3/5         |
|       C       |      -6/5        |

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_4.1_page-0001.jpg))
![](https://github.com/FELIZURC/figuras/blob/main/WhatsApp%20Image%202025-03-12%20at%2011.06.28%20PM%20(2).jpeg))
![](https://github.com/FELIZURC/figuras/blob/main/WhatsApp%20Image%202025-03-12%20at%2011.07.13%20PM%20(1).jpeg))

** Resultado del ejemplo :**  3/5 - (3*exp(-t)*(cos(2*t) + sin(2*t)/2))/5
📚F=(2*s-3)/((s+2)*(s^2+s-2)*(s^2+6*s+10)*(s^2+8*s+17))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_7.1_page-0001.jpg))
📚F=x"+5x'+4x=0 y(0)=1 y'(0)=0
![](https://github.com/FELIZURC/figuras/blob/main/Figure_4.2_page-0001.jpg))

## 5. Quinto día de clase
Hicimos un ejercicio de transformada inversa de la función
📚F=(2*s-3)/((s+2)*(s^2+s-2)*(s^2+6*s+10)*(s^2+8*s+17))
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      1/3978      |
|       B       |     7/30         |
|       C       |      -92/225     |
|       d       |      7/34        |
|       e       |    -1/17         |
|       f       |      -6/5        |
|       g       |      -207/130    |

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_7.1_page-0001.jpg))

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.40.56%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.41.24%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.06%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.22%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.43%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.43.01%20PM.jpeg))
** Resultado del ejemplo :** (7*t*exp(-2*t))/30 - exp(t)/3978 - (92*exp(-2*t))/225 + (4*exp(-3*t)*(cos(t) + (15*sin(t))/8))/17 + (113*exp(-4*t)*(cos(t) - (59*sin(t))/113))/650
Este ejercicio me da un poco diferente.

## 11. Referencias
https://sga.unemi.edu.ec/media/recursotema/Documento_2020618144651.pdf
https://platzi.com/tutoriales/1320-ecuaciones/8937-transformada-de-laplace-de-la-derivada-de-una-funcion-pvi-repaso/
