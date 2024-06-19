
### Objetivos de la Clase
- Comprender el método de integración por fracciones parciales.
- Conocer los diferentes casos para la descomposición en fracciones parciales.
- Aplicar el método de fracciones parciales para resolver integrales de funciones racionales.

## Introducción
La integración por fracciones parciales es una técnica utilizada para integrar funciones racionales, es decir, cocientes de polinomios. Esta técnica descompone una fracción compleja en una suma de fracciones más simples, que son más fáciles de integrar.

## Casos de Descomposición en Fracciones Parciales

### Caso 1: Factores Lineales Distintos
Si el denominador de la fracción tiene factores lineales distintos (no repetidos), de la forma $(x - a_1)(x - a_2) \cdots (x - a_n)$, la descomposición se realiza como:

$$
\frac{P(x)}{(x - a_1)(x - a_2) \cdots (x - a_n)} = \frac{A_1}{x - a_1} + \frac{A_2}{x - a_2} + \cdots + \frac{A_n}{x - a_n}
$$

donde $A_1, A_2, \ldots, A_n$ son constantes a determinar.

### Caso 2: Factores Lineales Repetidos
Si el denominador tiene factores lineales repetidos, de la forma $(x - a)^m$, la descomposición se realiza como:

$$
\frac{P(x)}{(x - a)^m} = \frac{A_1}{x - a} + \frac{A_2}{(x - a)^2} + \cdots + \frac{A_m}{(x - a)^m}
$$

donde $A_1, A_2, \ldots, A_m$ son constantes a determinar.

### Caso 3: Factores Cuadráticos Irreducibles
Si el denominador tiene factores cuadráticos irreducibles (que no pueden factorizarse más en números reales), de la forma $(x^2 + bx + c)$, la descomposición se realiza como:

$$
\frac{P(x)}{(x^2 + bx + c)} = \frac{Ax + B}{x^2 + bx + c}
$$

donde $A$ y $B$ son constantes a determinar.

### Caso 4: Factores Cuadráticos Irreducibles Repetidos
Si el denominador tiene factores cuadráticos irreducibles repetidos, de la forma $(x^2 + bx + c)^m$, la descomposición se realiza como:

$$
\frac{P(x)}{(x^2 + bx + c)^m} = \frac{A_1x + B_1}{x^2 + bx + c} + \frac{A_2x + B_2}{(x^2 + bx + c)^2} + \cdots + \frac{A_mx + B_m}{(x^2 + bx + c)^m}
$$

donde $A_1, B_1, A_2, B_2, \ldots, A_m, B_m$ son constantes a determinar.

## Procedimiento General para la Descomposición en Fracciones Parciales
1. **Factorizar el denominador**: Descomponer el denominador en factores lineales y cuadráticos irreducibles.
2. **Escribir la forma de la descomposición**: Usar los casos mencionados para escribir la forma general de la fracción parcial.
3. **Multiplicar por el denominador común**: Multiplicar ambos lados de la ecuación por el denominador original para eliminar las fracciones.
4. **Resolver para las constantes**: Igualar los coeficientes de los términos del numerador en ambos lados de la ecuación para formar un sistema de ecuaciones y resolver para las constantes.
5. **Integrar cada fracción parcial**: Integrar cada fracción parcial por separado.

## Conclusión
La integración por fracciones parciales es una técnica efectiva para resolver integrales de funciones racionales. Comprender los diferentes casos y cómo descomponer correctamente las fracciones es fundamental para aplicar esta técnica con éxito.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 7: Técnicas de Integración. Sección 7.4: Integración por Fracciones Parciales.

## Ejercicios Propuestos
1. Descomponer en fracciones parciales: $\frac{5x}{(x - 1)(x + 2)}$
2. Descomponer en fracciones parciales: $\frac{3x^2 + 7x + 5}{(x + 1)^2 (x^2 + 1)}$
3. Descomponer en fracciones parciales: $\frac{2x^3 + 3x^2 + x + 5}{(x^2 + x + 1)(x - 2)}$
