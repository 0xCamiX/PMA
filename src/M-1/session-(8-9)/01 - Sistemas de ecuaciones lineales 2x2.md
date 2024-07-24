## Objetivos de la Clase
- Comprender qué es un sistema de ecuaciones lineales 2x2.
- Aprender los cuatro métodos de solución: sustitución, igualación, reducción (o eliminación) y Cramer.
- Aplicar estos métodos en la resolución de problemas.

## Introducción
Un sistema de ecuaciones lineales 2x2 consiste en dos ecuaciones lineales con dos variables. La solución del sistema es el par ordenado que satisface ambas ecuaciones simultáneamente.

### Forma General
Un sistema de ecuaciones lineales 2x2 se puede escribir de la siguiente forma:
$$
\begin{cases}
a_1x + b_1y = c_1 \\
a_2x + b_2y = c_2
\end{cases}
$$

## Métodos de Solución

### 1. Método de Sustitución
En este método, se despeja una de las variables en una de las ecuaciones y se sustituye su valor en la otra ecuación. Esto convierte el sistema en una ecuación con una sola variable, que se puede resolver fácilmente.

#### Idea General
1. Despejar una variable en una de las ecuaciones.
2. Sustituir esa expresión en la otra ecuación.
3. Resolver la ecuación resultante para la otra variable.
4. Sustituir el valor encontrado en la primera ecuación para hallar el valor de la primera variable.

### 2. Método de Igualación
En este método, se despejan ambas variables en ambas ecuaciones y se igualan las expresiones resultantes. Esto también convierte el sistema en una ecuación con una sola variable.

#### Idea General
1. Despejar la misma variable en ambas ecuaciones.
2. Igualar las dos expresiones obtenidas.
3. Resolver la ecuación resultante para una de las variables.
4. Sustituir el valor encontrado en una de las ecuaciones originales para hallar el valor de la otra variable.

### 3. Método de Reducción o Eliminación
En este método, se multiplican las ecuaciones por constantes adecuadas para que al sumarlas o restarlas, una de las variables se elimine. Esto deja una ecuación con una sola variable.

#### Idea General
1. Multiplicar una o ambas ecuaciones por constantes adecuadas para que los coeficientes de una de las variables sean opuestos.
2. Sumar o restar las ecuaciones para eliminar una variable.
3. Resolver la ecuación resultante para una variable.
4. Sustituir el valor encontrado en una de las ecuaciones originales para hallar el valor de la otra variable.

### 4. Método de Cramer
Este método utiliza determinantes para encontrar la solución del sistema. Es aplicable cuando el sistema tiene una solución única.

#### Idea General
1. Escribir el sistema en forma de matriz:
   $$
   \begin{cases}
   a_1x + b_1y = c_1 \\
   a_2x + b_2y = c_2
   \end{cases}
   $$
   se puede escribir como
   $$
   A \mathbf{x} = \mathbf{b}
   $$
   donde
   $$
   A = \begin{pmatrix}
   a_1 & b_1 \\
   a_2 & b_2
   \end{pmatrix},
   \quad \mathbf{x} = \begin{pmatrix}
   x \\
   y
   \end{pmatrix},
   \quad \mathbf{b} = \begin{pmatrix}
   c_1 \\
   c_2
   \end{pmatrix}
   $$
2. Calcular el determinante de la matriz \( A \):
   $$
   \Delta = \begin{vmatrix}
   a_1 & b_1 \\
   a_2 & b_2
   \end{vmatrix}
   = a_1b_2 - a_2b_1
   $$
3. Calcular los determinantes \( \Delta_x \) y \( \Delta_y \) reemplazando la columna correspondiente de \( A \) por el vector \( \mathbf{b} \):
   $$
   \Delta_x = \begin{vmatrix}
   c_1 & b_1 \\
   c_2 & b_2
   \end{vmatrix}
   = c_1b_2 - c_2b_1
   $$
   $$
   \Delta_y = \begin{vmatrix}
   a_1 & c_1 \\
   a_2 & c_2
   \end{vmatrix}
   = a_1c_2 - a_2c_1
   $$
4. Resolver para \( x \) y \( y \):
   $$
   x = \frac{\Delta_x}{\Delta}, \quad y = \frac{\Delta_y}{\Delta}
   $$

## Conclusión
Los sistemas de ecuaciones lineales 2x2 pueden resolverse de manera eficiente utilizando diferentes métodos, cada uno con sus propias ventajas. La comprensión de estos métodos permite abordar una variedad de problemas matemáticos y aplicarlos en diferentes contextos.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 1: Fundamentos. Sección 1.3: Sistemas de Ecuaciones Lineales.

## Ejercicios Propuestos
1. Resuelve el sistema de ecuaciones utilizando el método de sustitución:
   $$
   \begin{cases}
   3x + 2y = 5 \\
   x - y = 1
   \end{cases}
   $$
2. Resuelve el sistema de ecuaciones utilizando el método de igualación:
   $$
   \begin{cases}
   2x - y = 3 \\
   4x + y = 7
   \end{cases}
   $$
3. Resuelve el sistema de ecuaciones utilizando el método de reducción:
   $$
   \begin{cases}
   5x + 3y = 7 \\
   2x - 3y = 4
   \end{cases}
   $$
4. Resuelve el sistema de ecuaciones utilizando el método de Cramer:
   $$
   \begin{cases}
   x + 2y = 3 \\
   3x - y = 2
   \end{cases}
   $$
