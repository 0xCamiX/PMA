## Objetivos de la Clase
- Definir la derivada de una función en un punto.
- Entender la interpretación geométrica de la derivada.
- Comprender la notación y las reglas básicas de derivación.
- Aplicar el concepto de derivada a problemas de la vida real.

## Introducción
La derivada es uno de los conceptos fundamentales del cálculo y de las matemáticas en general. Proporciona una manera precisa de describir cómo cambian las funciones y es esencial para el estudio de fenómenos dinámicos en diversas disciplinas.

## Definición de Derivada

### Derivada en un Punto
La derivada de una función $f(x)$ en un punto $a$, denotada por $f'(a)$, se define como el límite del cociente de diferencias cuando el incremento en $x$ tiende a cero:
$$
f'(a) = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
$$

### Interpretación Geométrica
Geometricamente, la derivada de una función en un punto $a$ representa la pendiente de la tangente a la curva $y = f(x)$ en el punto $(a, f(a))$. 

### Notación
Existen varias notaciones para la derivada de una función:
- Notación de Leibniz: $\frac{dy}{dx}$, donde $y = f(x)$.
- Notación de Lagrange: $f'(x)$.
- Notación de Newton: $\dot{y}$ (usada principalmente en física).

## Ejemplos de Cálculo de Derivadas

### Ejemplo 1: Derivada de una Función Lineal
Para la función $f(x) = 3x + 5$, la derivada es:
$$
f'(x) = 3
$$
Esto se debe a que la pendiente de una línea recta es constante.

### Ejemplo 2: Derivada de una Función Cuadrática
Para la función $f(x) = x^2$, la derivada es:
$$
f'(x) = 2x
$$
Esto se calcula usando la definición del límite.

## Reglas Básicas de Derivación

### Regla de la Potencia
Si $f(x) = x^n$, donde $n$ es un número real, entonces:
$$
f'(x) = nx^{n-1}
$$

### Regla de la Suma
Si $f(x) = g(x) + h(x)$, entonces:
$$
f'(x) = g'(x) + h'(x)
$$

### Regla del Producto
Si $f(x) = g(x) \cdot h(x)$, entonces:
$$
f'(x) = g'(x) \cdot h(x) + g(x) \cdot h'(x)
$$

### Regla del Cociente
Si $f(x) = \frac{g(x)}{h(x)}$, entonces:
$$
f'(x) = \frac{g'(x) \cdot h(x) - g(x) \cdot h'(x)}{(h(x))^2}
$$

### Regla de la Cadena
Si $y = f(u)$ y $u = g(x)$, entonces:
$$
\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}
$$

## Aplicaciones de las Derivadas

### Velocidad y Aceleración
En física, la derivada de la posición con respecto al tiempo es la velocidad, y la derivada de la velocidad es la aceleración.

### Máximos y Mínimos
Las derivadas se utilizan para encontrar los puntos críticos de una función, que pueden corresponder a máximos, mínimos o puntos de inflexión.

### Tasa de Cambio
En economía y otras ciencias sociales, las derivadas representan la tasa de cambio de una cantidad con respecto a otra.

## Conclusión
El concepto de derivada es fundamental para el cálculo y tiene aplicaciones en numerosas disciplinas. Entender cómo calcular y aplicar derivadas es crucial para el análisis matemático y la modelización de fenómenos dinámicos.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 3: Derivadas. Sección 3.1: La Derivada y la Tangente a la Curva.

## Ejercicios Propuestos
1. Calcular la derivada de $f(x) = 4x^3 - 2x^2 + x - 7$.
2. Encontrar $f'(x)$ para $f(x) = \frac{1}{x}$.
3. Utilizar la regla del producto para hallar la derivada de $f(x) = (2x^2 + 3x)(x - 1)$.
4. Aplicar la regla de la cadena para derivar $f(x) = \sin(3x^2 + 2x)$.
5. Determinar la velocidad de un objeto cuya posición está dada por $s(t) = t^3 - 6t^2 + 9t$ en el tiempo $t = 2$.
