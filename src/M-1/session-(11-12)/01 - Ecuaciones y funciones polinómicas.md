## Objetivos de la Clase
- Comprender el concepto de funciones y ecuaciones polinómicas.
- Aprender a identificar y representar funciones polinómicas.
- Conocer los métodos para resolver ecuaciones polinómicas.

## Introducción
Las funciones y ecuaciones polinómicas son expresiones algebraicas que incluyen términos de la forma \(ax^n\), donde \(a\) es un coeficiente y \(n\) es un exponente no negativo. Estas funciones y ecuaciones son fundamentales en matemáticas y tienen diversas aplicaciones en ciencias e ingeniería.

## Conceptos Clave

### Funciones Polinómicas
Una función polinómica es una función que puede expresarse como:
$$
f(x) = a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0
$$
donde \(a_n, a_{n-1}, \ldots, a_1, a_0\) son constantes, \(a_n \neq 0\), y \(n\) es un entero no negativo.

#### Grado del Polinomio
El grado del polinomio es el mayor exponente \(n\) en la función polinómica. El término \(a_nx^n\) se llama término de grado más alto.

#### Ejemplo
La función \(f(x) = 4x^3 - 2x^2 + 3x - 5\) es una función polinómica de grado 3 con coeficientes \(a_3 = 4\), \(a_2 = -2\), \(a_1 = 3\) y \(a_0 = -5\).

### Ecuaciones Polinómicas
Una ecuación polinómica se puede escribir en la forma:
$$
a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0 = 0
$$
donde \(a_n, a_{n-1}, \ldots, a_1, a_0\) son constantes y \(a_n \neq 0\).

#### Ejemplo
La ecuación \(2x^4 - 3x^3 + x^2 - 6x + 2 = 0\) es una ecuación polinómica de grado 4.

## Representación de Funciones Polinómicas

### Gráfica de una Función Polinómica
La gráfica de una función polinómica de grado \(n\) puede tener hasta \(n-1\) puntos de inflexión y hasta \(n\) intersecciones con el eje \(x\). El comportamiento de la función en los extremos depende del término de grado más alto \(a_nx^n\).

#### Comportamiento en los Extremos
- Si \(a_n > 0\) y \(n\) es par, \(f(x) \rightarrow \infty\) cuando \(x \rightarrow \pm\infty\).
- Si \(a_n < 0\) y \(n\) es par, \(f(x) \rightarrow -\infty\) cuando \(x \rightarrow \pm\infty\).
- Si \(a_n > 0\) y \(n\) es impar, \(f(x) \rightarrow \infty\) cuando \(x \rightarrow \infty\) y \(f(x) \rightarrow -\infty\) cuando \(x \rightarrow -\infty\).
- Si \(a_n < 0\) y \(n\) es impar, \(f(x) \rightarrow -\infty\) cuando \(x \rightarrow \infty\) y \(f(x) \rightarrow \infty\) cuando \(x \rightarrow -\infty\).

### Raíces de un Polinomio
Las raíces (o ceros) de una función polinómica son los valores de \(x\) para los cuales \(f(x) = 0\). Una función polinómica de grado \(n\) tiene exactamente \(n\) raíces (contando multiplicidades).

## Métodos de Solución de Ecuaciones Polinómicas

### 1. Factorización
Si la ecuación polinómica se puede factorizar, se puede escribir como el producto de factores más simples y resolver cada factor igualado a cero.

#### Idea General
1. Factorizar el polinomio:
   $$
   a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0 = (bx + c)(dx + e) \cdots = 0
   $$
2. Resolver cada factor:
   $$
   bx + c = 0, \quad dx + e = 0, \quad \cdots
   $$

### 2. Teorema del Factor
El teorema del factor establece que \(x - r\) es un factor del polinomio \(f(x)\) si y solo si \(f(r) = 0\). Este teorema puede utilizarse para encontrar las raíces del polinomio.

#### Idea General
1. Evaluar el polinomio en posibles raíces racionales utilizando el teorema de las raíces racionales.
2. Utilizar la división sintética para factorizar el polinomio.
3. Resolver los factores resultantes.

### 3. Fórmula Cuadrática
Para ecuaciones polinómicas de grado 2, se puede utilizar la fórmula cuadrática para encontrar las raíces.

#### Fórmula
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

### 4. Método de Ruffini
El método de Ruffini es una técnica para dividir polinomios y encontrar raíces. Es especialmente útil cuando se conoce una raíz y se desea simplificar el polinomio.

#### Idea General
1. Dividir el polinomio por \(x - r\) utilizando la división sintética.
2. Obtener un polinomio de menor grado.
3. Repetir el proceso hasta resolver completamente el polinomio.

### 5. Métodos Numéricos
Para polinomios de grados altos o con raíces complejas, se pueden utilizar métodos numéricos como el método de Newton-Raphson para aproximar las raíces.

## Conclusión
Las funciones y ecuaciones polinómicas son fundamentales en el estudio de las matemáticas. Comprender sus propiedades y métodos de solución es esencial para abordar problemas más avanzados en diversos campos científicos y de ingeniería.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 1: Fundamentos. Sección 1.5: Funciones y Ecuaciones Polinómicas.

## Ejercicios Propuestos
1. Factoriza y resuelve la ecuación polinómica \(x^3 - 4x^2 + 5x - 2 = 0\).
2. Utiliza el teorema del factor para encontrar una raíz de \(2x^3 - 3x^2 - 8x + 12 = 0\) y factoriza el polinomio.
3. Encuentra las raíces de la ecuación cuadrática \(3x^2 - 7x + 2 = 0\) usando la fórmula cuadrática.
4. Aplica el método de Ruffini para dividir el polinomio \(x^4 - 6x^3 + 11x^2 - 6x\) por \(x - 1\) y encuentra las raíces restantes.