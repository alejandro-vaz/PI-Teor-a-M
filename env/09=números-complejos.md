## Números complejos
---


### Conjuntos numéricos

Para entender qué es un número complejo, revisaremos primero la clasificación numérica. Los números los clasificamos en "conjuntos numéricos," que son grupos de números que tienen alguna característica en común.

El conjunto numérico más reducido es el de los números naturales ($\mathbb{N}$), estos números son los que representan una cantidad entera y positiva. La humanidad empezó a usar estos números hace milenios.

Si continuamos con la clasificación nos encontramos a los números enteros ($\mathbb{Z}$), que incluyen el cero y los números negativos, surgieron en la antiguedad debido a la gran utilidad que tenía representar cantidades negativas o nulas.
 
![Relative](/images/1.png) <br> Conjuntos numéricos.

Sin embargo, esos números no bastaban para representar todas las cantidades: como resultado de algunas divisiones obteniamos números que no entraban dentro de esta clasificación, números que estaban entre los números enteros, a los que se les llamó fraccionarios. Al conjunto que incluye los enteros y los fraccionarios se le llamó números racionales ($\mathbb{Q}$).

Pero todos esos números no eran suficientes. Cuando se empezó a estudiar los triángulos de forma más exhaustiva en la antigua Grecia, se encontrarón con raíces de números que no tenían una solución que se pudiese expresar con los racionales, que tenían infinitos decimales. A estos números se les llamó irracionales y al conjunto que engloba los racionales y los irracionales se nombró como números reales ($\mathbb{R}$).


Los números imaginarios ($\mathbb{I}$) existen aparte de los números reales, es decir, son una clasificación diferente e independiente. El conjunto que une los números reales e imaginarios es el conjunto de los números complejos ($\mathbb{C}$).


### Origen

Los números imaginarios surgieron del estudio de las funciones cuadráticas. Observa la siguiente función:

$$
\begin{align*}
f(x) &= x^2-3x+5
\end{align*}
$$

Vamos a averiguar sus puntos de corte con el eje de las $x$. Cuando una función $f(x)$ corta con el eje de las $x$ significa que $y$ (o $f(x)$) es igual a $0$. Para resolver este tipo de ecuaciones existen varios métodos, pero vamos a aplicar el método de la fórmula cuadrática, que nos permite averiguar los puntos de corte mediante la siguiente fórmula:

$$
\begin{align*}
x &= \frac{-b\pm \sqrt{b^2-4ac}}{2a}
\end{align*}
$$

donde $a$, $b$ y $c$ son los coeficientes de la función de segundo grado:

$$
\begin{align*}
f(x)&=ax^2+bx+c
\end{align*}
$$

Con funciones cuadráticas como la que hemos expuesto anteriormente, la aplicación de la fórmula cuadrática da como resultado un error si operamos con números reales, ya que el término de la raíz en el numerador es negativo. Nos queda tal que así:
    
$$
\begin{align*}
x &= \frac{3\pm \sqrt{-11}}{2}
\end{align*}
$$


Eso nos indica que no hay ningún punto de corte con el eje $x$. Sin embargo, nosotros podemos seguir operando. Recordando las propiedades de las raíces, una de ellas es que la multiplicación de dos raíces con el mismo índice equivale a una única raíz con ese índice y con los radicandos multiplicados:

$$
\begin{align*}
\sqrt[n]{x} \cdot \sqrt[n]{y} &= \sqrt[n]{xy}
\end{align*}
$$

Podemos entonces ampliar el término $\sqrt{-11}$ para dejar el negativo en una raíz aparte de la siguiente manera:

$$
\begin{align*}
x &= \frac{3\pm \sqrt{-11}}{2} \\
x &= \frac{3\pm \sqrt{-1 \cdot 11}}{2} \\
x &= \frac{3\pm \sqrt{-1} \cdot \sqrt{11}}{2}
\end{align*}
$$



Es en este momento en el que los matemáticos del siglo XVII (como René Descartes), sin saber realmente las aplicaciones de los números imaginarios, nombraron a $\sqrt{-1}$ como una variable; Aunque fueron Euler y Gauss quienes estandarizaron el uso de la letra $i$ para representar a $\sqrt{-1}$ en el siglo XVIII.


![Relative](/images/2.png) <br> Leonard Euler, matemático del siglo XVIII.

Al nombrar a $\sqrt{-1}$ como una variable estamos pasando a trabajar con números imaginarios y reales, por lo que hemos cambiado nuestro conjunto numérico de trabajo al de los números complejos ($\mathbb{C}$). Esto es debido a que en números reales, la raíz de un número negativo no existe, mientras que en números complejos sí.


$$
\begin{align*}
x &= \frac{3\pm \sqrt{11}i}{2} \\
x &\approx \frac{3\pm 3.32i}{2} \\
x &\approx 1.5 \pm 1.66i \\
\end{align*} \\
x_1 \approx 1.5 + 1.66i \qquad x_2 \approx 1.5 - 1.66i 
$$

Consideramos un número imaginario ($\mathbb{I}$) a aquel que contiene $i$, que puede estar multiplicado por un número real. Los siguientes números son números imaginarios:

$$
2i \qquad -5i \qquad 3.7i \qquad -\frac{1}{2}i \qquad \sqrt{2}i \qquad -\pi i
$$

En cambio, los números complejos ($\mathbb{C}$), aparecen de la siguiente forma:

$$
\begin{align*} 
z &= a + bi 
\end{align*}
$$

Se denomina a $a$ la parte real y a $bi$ la parte imaginaria. $bi$, por sí solo, es un número imaginario, mientras que $a$ es un número real.

### Operaciones aritméticas

Las operaciones aritméticas con números complejos son sencillas. Trataremos la mayor parte del tiempo a $i$ como una variable más, como si fuese $x$ o cualquiera otra. Se consideran operaciones aritméticas a la suma, la resta, la multiplicación y la división.


La suma de dos números complejos es igual que con dos binomios de primer grado. Es decir:

$$
(a + bi) + (c + di) = a + c + bi + di = (a + c) + (b + d)i
$$

Lo mismo sucede con la resta:

$$
(a + bi) - (c + di) = a - c + bi - di = (a - c) + (b - d)i
$$

La multiplicación de dos números complejos es similar a la de los binomios de grado $1$, pero tenemos que tener en cuenta que $i = \sqrt{-1}$, por lo que
 
$$
i^2 = \left(\sqrt{-1}\right)^2 = -1
$$

Si queremos multiplicar $2+3i$ por $4-5i$, tenemos que aplicar esa propiedad:

$$
(2 + 3i) \cdot (4 - 5i) \\
8 + 12i - 10i - 15i^2 \\
8 + 2i + 15 \\
23 + 2i
$$

El proceso para dividir es más tedioso. Veamos el siguiente ejemplo:

$$
\frac{2 + 3i}{4 - 6i}
$$

Multiplicaremos numerador y denominador por la expresión conjugada del denominador, que es el mismo número complejo pero con la parte imaginaria cambiada a su opuesto.


> Multiplicar por el conjugado del denominador nos dejará un numerador complejo pero con un denominador real, ya que un número complejo multiplicado por su conjugado es igual a un número real. Ampliaremos sobre los conjugados y sus propiedades en la próxima sección.

$$
\begin{align*}
&= \frac{2 + 3i}{4 - 6i} \cdot \frac{4+6i}{4+6i} \\
&= \frac{-10 + 24i}{52} \\
&\approx -0.19 + 0.46i
\end{align*}
$$

### Módulo y conjugado

Para imaginarnos como podría ser el módulo de un número complejo ($z = a + bi$), podemos pensar en el número representado como un vector $\mathbf{v} = (a, b)$ en el plano complejo. En el plano complejo el eje de las $x$ representa la parte real y el eje de las $y$ representa el coeficiente de la parte imaginaria.


De esa forma, calculamos el módulo como:
$$
\begin{align*}
z &= a + bi \\
|z| &= |\mathbf{v}| \\
|z| &= \sqrt{a^2 + b^2}
\end{align*}
$$

Gracias a las propiedades de los módulos, el módulo de un número complejo es siempre un número real no negativo.


El conjugado de un número complejo es similar al de un binomio. Denotamos al conjugado como $\overline{z}$ y se define como:

$$
\begin{align*}
\overline{z} &= a - bi
\end{align*}
$$

Una propiedad de los conjugados es que si a un número complejo cualquiera, lo multiplicamos por su conjugado, obtenemos siempre su módulo al cuadrado (que es un número real no negativo). Demostración:

$$
z = a + bi \qquad \overline{z} = a - bi \qquad |z|^2 = a^2 + b^2 \\
\begin{align*} 
z &= a + bi \\
z \cdot \overline{z} &= (a + bi) \cdot (a - bi) \\
z \cdot \overline{z} &= a^2 - abi + abi - b^2i^2 \\
z \cdot \overline{z} &= a^2 + b^2 \\
z \cdot \overline{z} &= |z|^2 
\end{align*}
$$

El conjugado también da resultados que nos podrían ser útiles si se lo sumamos o restamos al número original; si se lo sumamos:

$$
\begin{align*}
z + \overline{z} &= (a+bi) + (a-bi) \\
z + \overline{z} &= 2a \\
a &= \frac{z + \overline{z}}{2}
\end{align*}
$$

Es decir, la parte real de un número complejo la podemos conseguir si le sumamos su conjugado y dividimos todo entre dos. Algo similar podemos hacer si lo restamos:

$$
\begin{align*}
z - \overline{z} &= (a+bi) - (a-bi) \\
z - \overline{z} &= 2bi \\
bi &= \frac{z - \overline{z}}{2} \\
\end{align*}
$$

Consiguiendo así la parte imaginaria.

### Representación gráfica

![Relative](/images/3.png) <br> Números en el plano complejo

Hemos mencionado anteriormente el plano complejo, y cómo este se relacionaba con el módulo. Ahora lo explicaremos de forma más completa.

En el plano complejo , o plano de Argand-Gauss, representamos los números complejos de forma bidimensional. El eje de las $x$ representa la parte real y el eje de las $y$ representa la parte imaginaria (sin contar la $i$).

El número complejo $z = a + bi$ se representa como el vector $\mathbf{v} = (a, b)$, aunque las operaciones aritméticas se realizan con el número complejo.

En el plano, la suma de dos números complejos se puede representar como la unión de sus vectores, mientras que la resta se representa como la diferencia de sus vectores. El producto de dos números complejos no es igual a el producto escalar de sus vectores, ya que la multiplicación usa la propiedad distributiva mientras que el producto escalar multiplica las dimensiones de los vectores.


### Coordenadas polares

Si queremos determinar dónde se encuentra un número complejo en el plano, tenemos dos formas para hacerlo: con las coordenadas cartesianas $\mathbf{v} = (a, b)$, o con las coordenadas polares $\mathbf{p}=(r, \theta)$.

En las coordenadas polares, $r$ simboliza la distancia al origen del punto mientras que $\theta$ especifica la dirección (el ángulo). Podemos pasar de un sistema a otro fácilmente.

![Relative](/images/4.png) <br> Paso de coordenadas cartesianas a polares.

Para pasar de coordenadas cartesianas a polares primero tenemos que conseguir la distancia del punto al origen, es decir, su módulo. Ya expusimos anteriormente el proceso para conseguirlo.

$$
\begin{align*}
z &= a + bi \\
|z| &= \sqrt{a^2+b^2} \\
r &= \sqrt{a^2+b^2}
\end{align*}
$$

Después, necesitaremos conseguir el ángulo ($\theta$) que forma el vector de posición del punto en el plano complejo con el eje real positivo. El argumento de un número complejo es ese ángulo, la función para conseguirlo se denomina $arg(a+bi)$:

$$
z = a + bi \qquad arg(a + bi) = \arctan{\left(\frac{b}{a}\right)} \\
\begin{align*}
z &= a + bi \\
arg(z) &= arg(a + bi) \\
arg(z) &= \arctan{\left(\frac{b}{a}\right)} \\
\theta &= \arctan{\left(\frac{b}{a}\right)}
\end{align*}
$$

Por lo que $z$ lo podemos expresar como:

$$
z = a + bi = (a, b) = \left(\sqrt{a^2+b^2}, \arctan{\left(\frac{b}{a}\right)}\right)
$$

También podemos hacer el proceso a la inversa. Supongamos que tenemos $\mathbf{p} = (r, \theta)$ y queremos pasar a coordenadas cartesianas. Para ello usaremos la trigonometría fijándonos en cómo se muestran los números en el plano complejo:

$$
\begin{align*}
w &= (r, \theta) \\
a &= r\cos \theta \\
b &= r\sin \theta
\end{align*}
$$

Ya que $a$ representa el eje real horizontal y usamos coseno mientras que $b$ representa el eje imaginario vertical por lo que usamos seno. Multiplicamos por el radio para conseguir el punto a esa distancia.


Nos queda que el punto final es:

$$
w = r\cos \theta + ir\sin \theta = (r\cos \theta, r\sin \theta) = (r, \theta)
$$