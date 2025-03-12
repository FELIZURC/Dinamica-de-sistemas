# Contenido de clase
Son los apuntes de dinamica de sistemas Felipe Cruz Pineda, Angi Vanesa Vargas y Kevin Nicolas Perés Tobar.
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
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^m\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{C_1}{(s-p_1)}+\frac{C_2}{(s-p_1)^2}+\dots+\frac{C_m}{(s-p_1)^m}+\frac{C_{m+1}}{(s-p_2)}+\dots+\frac{C_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^m\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{C_1}{(s-p_1)}+\frac{C_2}{(s-p_1)^2}+\dots+\frac{C_m}{(s-p_1)^m}+\frac{C_{m+1}}{(s-p_2)}+\dots+\frac{C_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^m\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{C_1}{(s-p_1)}+\frac{C_2}{(s-p_1)^2}+\dots+\frac{C_m}{(s-p_1)^m}+\frac{C_{m+1}}{(s-p_2)}+\dots+\frac{C_n}{(s-p_n)}" border="0" />
</a>
</center>




> 🔑*Caso 3*: Q(s), tiene raices complejas conjugadas.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>


## 3. Tercer dia de clase

### 3.1. Raíces reales diferentes

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}"><img src="http://www.alciro.org/cgi/tex.cgi?G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" title="G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" border="0" /></a>
</center>

### 3.2. Raíces complejas conjugadas con un factor adicional

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}" title="\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}" border="0" />
</a>
</center>


### 3.3. Raíces complejas conjugadas y raíces reales

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}" title="\frac{P\left(s\right)}{(s^2 + p s + q)(s - r)}=\frac{A s + B}{(s^2 + p s + q)}+\frac{C}{(s - r)}" border="0" />
</a>
</center>





# Función para descomponer en fracciones parciales
def descomponer_fracciones_parciales():
    x = sp.symbols('x')

    # Caso 1: Raíces reales distintas
    # Ejemplo: 6 / ((x - 2) * (x - 3))
    f1 = 6 / ((x - 2) * (x - 3))
    fraccion_parcial1 = sp.apart(f1)
    print("Descomposición de fracción con raíces reales distintas:")
    print(fraccion_parcial1)

    # Caso 2: Raíces reales repetidas
    # Ejemplo: 6 / ((x - 2)**2 * (x - 3))
    f2 = 6 / ((x - 2)**2 * (x - 3))
    fraccion_parcial2 = sp.apart(f2)
    print("\nDescomposición de fracción con raíces reales repetidas:")
    print(fraccion_parcial2)

    # Caso 3: Raíces complejas conjugadas
    # Ejemplo: 6 / (x^2 + 2x + 5) (Raíces complejas conjugadas)
    f3 = 6 / (x**2 + 2*x + 5)
    fraccion_parcial3 = sp.apart(f3)
    print("\nDescomposición de fracción con raíces complejas conjugadas:")
    print(fraccion_parcial3)

# Ejecutar la función
descomponer_fracciones_parciales()


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
𝑥 
## 11. Referencias
https://sga.unemi.edu.ec/media/recursotema/Documento_2020618144651.pdf
