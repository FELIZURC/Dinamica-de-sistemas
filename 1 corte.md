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

>> >![](   ))




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
$3=A(5)$

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      3/5         |
|       B       |     -3/5         |
|       C       |      -6/5        |

>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_4.1_page-0001.jpg))

** Resultado del ejemplo :**  3/5 - (3*exp(-t)*(cos(2*t) + sin(2*t)/2))/5


📚
𝑥 
## 11. Referencias
https://sga.unemi.edu.ec/media/recursotema/Documento_2020618144651.pdf
