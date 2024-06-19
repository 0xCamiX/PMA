## Objetivos de la Clase
- Comprender la regla de L'Hôpital y cuándo se aplica.
- Conocer los diferentes casos de formas indeterminadas donde se puede utilizar la regla de L'Hôpital.
- Aplicar la regla de L'Hôpital para resolver límites que presentan formas indeterminadas.

## Introducción
La regla de L'Hôpital es una herramienta poderosa en el cálculo para resolver límites que presentan formas indeterminadas. Esta regla se basa en el uso de derivadas para evaluar límites y es aplicable a varias formas indeterminadas comunes.

## Enunciado de la Regla de L'Hôpital

Si $\lim_{x \to c} f(x) = 0$ y $\lim_{x \to c} g(x) = 0$ o si $\lim_{x \to c} f(x) = \pm \infty$ y $\lim_{x \to c} g(x) = \pm \infty$, entonces:
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f'(x)}{g'(x)}
$$
si el límite del lado derecho existe.

La regla de L'Hôpital también se aplica a límites en el infinito:
$$
\lim_{x \to \infty} \frac{f(x)}{g(x)} = \lim_{x \to \infty} \frac{f'(x)}{g'(x)}
$$

## Casos de Formas Indeterminadas para la Regla de L'Hôpital

### Caso 1: $\frac{0}{0}$
Este caso ocurre cuando tanto el numerador como el denominador tienden a cero. La regla de L'Hôpital se aplica derivando el numerador y el denominador y evaluando el límite resultante.

**Enunciado:**
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \frac{0}{0}
$$
Aplicación de la regla de L'Hôpital:
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f'(x)}{g'(x)}
$$

### Caso 2: $\frac{\infty}{\infty}$
Este caso ocurre cuando tanto el numerador como el denominador tienden a infinito. Similar al caso $\frac{0}{0}$, se aplica la regla de L'Hôpital derivando el numerador y el denominador.

**Enunciado:**
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \frac{\infty}{\infty}
$$
Aplicación de la regla de L'Hôpital:
$$
\lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f'(x)}{g'(x)}
$$

### Extensiones de la Regla de L'Hôpital

#### Forma Indeterminada $0 \cdot \infty$
Para este caso, se reescribe el producto como una fracción y luego se aplica la regla de L'Hôpital.

**Enunciado:**
$$
\lim_{x \to c} f(x) \cdot g(x) = 0 \cdot \infty
$$
Reescritura y aplicación de la regla de L'Hôpital:
$$
\lim_{x \to c} f(x) \cdot g(x) = \lim_{x \to c} \frac{f(x)}{\frac{1}{g(x)}} \quad \text{o} \quad \lim_{x \to c} \frac{g(x)}{\frac{1}{f(x)}}
$$
$$
\lim_{x \to c} \frac{f'(x)}{\left(\frac{1}{g(x)}\right)'} \quad \text{o} \quad \lim_{x \to c} \frac{g'(x)}{\left(\frac{1}{f(x)}\right)'}
$$

#### Forma Indeterminada $\infty - \infty$
Para este caso, se combina o simplifica la expresión para convertirla en una fracción antes de aplicar la regla de L'Hôpital.

**Enunciado:**
$$
\lim_{x \to c} (f(x) - g(x)) = \infty - \infty
$$
Reescritura y aplicación de la regla de L'Hôpital:
$$
\lim_{x \to c} (f(x) - g(x)) = \lim_{x \to c} \frac{h(x)}{1/g(x)}
$$

#### Forma Indeterminada $0^0$, $\infty^0$, $1^\infty$
Estas formas indeterminadas se resuelven usando logaritmos antes de aplicar la regla de L'Hôpital.

**Enunciados:**
$$
\lim_{x \to c} f(x)^{g(x)} = 0^0, \quad \lim_{x \to c} f(x)^{g(x)} = \infty^0, \quad \lim_{x \to c} f(x)^{g(x)} = 1^\infty
$$
Reescritura usando logaritmos:
$$
y = f(x)^{g(x)} \implies \ln(y) = g(x) \ln(f(x))
$$
Aplicación de la regla de L'Hôpital:
$$
\lim_{x \to c} \ln(y) = \lim_{x \to c} g(x) \ln(f(x)) = \lim_{x \to c} \frac{\ln(f(x))}{1/g(x)}
$$
Finalmente:
$$
\lim_{x \to c} y = e^{\lim_{x \to c} \ln(y)}
$$

## Procedimiento General para Aplicar la Regla de L'Hôpital
1. **Identificar la Forma Indeterminada**: Determine si la forma es $\frac{0}{0}$, $\frac{\infty}{\infty}$, $0 \cdot \infty$, $\infty - \infty$, $0^0$, $\infty^0$, o $1^\infty$.
2. **Reescribir si es Necesario**: Transforme el límite en una forma adecuada para aplicar la regla de L'Hôpital, especialmente en casos de $0 \cdot \infty$, $\infty - \infty$, $0^0$, $\infty^0$, y $1^\infty$.
3. **Aplicar la Regla de L'Hôpital**: Derive el numerador y el denominador por separado.
4. **Reevaluar el Límite**: Evalúe el nuevo límite después de aplicar la regla de L'Hôpital. Si la forma indeterminada persiste, aplique la regla nuevamente.

## Conclusión
La regla de L'Hôpital es una técnica esencial para resolver límites con formas indeterminadas. Conocer cuándo y cómo aplicarla correctamente es crucial para evaluar estos límites de manera efectiva.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 4: Aplicaciones de la Derivada. Sección 4.4: Formas Indeterminadas y Regla de L'Hôpital.

## Ejercicios Propuestos
1. Resolver el límite $\lim_{x \to 0} \frac{\sin(x)}{x}$ usando la regla de L'Hôpital.
2. Determinar el valor de $\lim_{x \to \infty} \frac{e^x}{x^2}$ aplicando la regla de L'Hôpital.
3. Evaluar el límite $\lim_{x \to 0} \frac{\ln(1 + x)}{x}$ utilizando la regla de L'Hôpital.
4. Resolver $\lim_{x \to \infty} \frac{x - \ln(x)}{x + \ln(x)}$ aplicando la regla de L'Hôpital.
