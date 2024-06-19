
## Objetivos de la Clase
- Comprender el concepto de formas indeterminadas.
- Conocer los diferentes casos de formas indeterminadas en el cálculo.
- Aprender a resolver límites que presentan formas indeterminadas.

## Introducción
En el cálculo, las formas indeterminadas ocurren cuando se evalúan límites y se obtiene una expresión que no define claramente un valor. Las formas indeterminadas más comunes son $\frac{0}{0}$ y $\frac{\infty}{\infty}$, aunque existen otras formas que también requieren técnicas especiales para su resolución.

## Casos de Formas Indeterminadas

### Caso 1: $\frac{0}{0}$
Este caso ocurre cuando tanto el numerador como el denominador de una fracción tienden a cero. Es una de las formas indeterminadas más comunes y se resuelve generalmente mediante la factorización, la simplificación, o la regla de L'Hôpital.

**Enunciado:**
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \frac{0}{0}
$$

### Caso 2: $\frac{\infty}{\infty}$
Este caso ocurre cuando tanto el numerador como el denominador de una fracción tienden a infinito. Similar al caso $\frac{0}{0}$, se puede resolver utilizando la regla de L'Hôpital, simplificando la expresión, o aplicando técnicas de comparación.

**Enunciado:**
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \frac{\infty}{\infty}
$$

### Caso 3: $0 \cdot \infty$
Esta forma indeterminada ocurre cuando un factor tiende a cero mientras que el otro factor tiende a infinito. Se resuelve usualmente transformando el producto en una fracción.

**Enunciado:**
$$
\lim_{x \to c} f(x) \cdot g(x) = 0 \cdot \infty
$$

### Caso 4: $\infty - \infty$
Este caso ocurre cuando dos términos tienden a infinito pero su diferencia no está claramente definida. La resolución implica generalmente la combinación de términos o la simplificación.

**Enunciado:**
$$
\lim_{x \to c} (f(x) - g(x)) = \infty - \infty
$$

### Caso 5: $0^0$
La forma indeterminada $0^0$ se encuentra en límites donde una base que tiende a cero se eleva a una potencia que también tiende a cero. La resolución usualmente requiere el uso de logaritmos y exponentes.

**Enunciado:**
$$
\lim_{x \to c} f(x)^{g(x)} = 0^0
$$

### Caso 6: $\infty^0$
Este caso ocurre cuando una base que tiende a infinito se eleva a una potencia que tiende a cero. Similar a $0^0$, se resuelve usando logaritmos y la transformación exponencial.

**Enunciado:**
$$
\lim_{x \to c} f(x)^{g(x)} = \infty^0
$$

### Caso 7: $1^\infty$
Esta forma indeterminada se encuentra en límites donde una base que tiende a uno se eleva a una potencia que tiende a infinito. La resolución también se basa en logaritmos y técnicas de límites exponenciales.

**Enunciado:**
$$
\lim_{x \to c} f(x)^{g(x)} = 1^\infty
$$

## Procedimiento General para Resolver Formas Indeterminadas
1. **Identificar la Forma Indeterminada**: Determine cuál de las formas indeterminadas está presente en el límite.
2. **Aplicar Técnicas Adecuadas**: Use la regla de L'Hôpital, factorización, simplificación, logaritmos, o cualquier técnica apropiada para resolver la forma indeterminada.
3. **Reevaluar el Límite**: Después de simplificar la expresión, vuelva a evaluar el límite para obtener la respuesta final.

## Conclusión
Las formas indeterminadas representan desafíos comunes en el cálculo de límites. Comprender los diferentes casos y aplicar las técnicas adecuadas es esencial para resolver estos límites correctamente.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 4: Aplicaciones de la Derivada. Sección 4.4: Formas Indeterminadas y Regla de L'Hôpital.

## Ejercicios Propuestos
1. Resolver el límite $\lim_{x \to 0} \frac{\sin(x)}{x}$.
2. Determinar el valor de $\lim_{x \to \infty} \frac{e^x}{x^2}$.
3. Evaluar el límite $\lim_{x \to 0} x \ln(x)$.
4. Resolver $\lim_{x \to \infty} (\sqrt{x^2 + x} - x)$.
