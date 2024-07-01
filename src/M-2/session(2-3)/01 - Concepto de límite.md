## Objetivos de la Clase
- Definir el concepto de límite en matemáticas.
- Comprender la notación y el significado del límite.
- Conocer las propiedades básicas de los límites.
- Aplicar el concepto de límite para resolver problemas matemáticos.

## Introducción
El concepto de límite es fundamental en cálculo y análisis matemático. Permite describir el comportamiento de una función a medida que su argumento se acerca a un valor específico. Los límites son esenciales para definir la continuidad, las derivadas y las integrales.

## Definición de Límite

### Definición Intuitiva
El límite de una función $f(x)$ cuando $x$ tiende a un valor $a$ es el valor que $f(x)$ se aproxima cuando $x$ se acerca a $a$.

**Enunciado:**
$$
\lim_{{x \to a}} f(x) = L
$$
donde $L$ es el valor al que se aproxima $f(x)$ cuando $x$ se acerca a $a$.

### Definición Formal (Épsilon-Delta)
Para todo $\epsilon > 0$, existe un $\delta > 0$ tal que si $0 < |x - a| < \delta$, entonces $|f(x) - L| < \epsilon$.

**Enunciado:**
$$
\forall \epsilon > 0, \exists \delta > 0 : 0 < |x - a| < \delta \implies |f(x) - L| < \epsilon
$$

## Notación de Límites
- **Límite lateral por la derecha:**
  $$
  \lim_{{x \to a^+}} f(x)
  $$
- **Límite lateral por la izquierda:**
  $$
  \lim_{{x \to a^-}} f(x)
  $$

Si ambos límites laterales existen y son iguales, se dice que el límite existe:
$$
\lim_{{x \to a}} f(x) = L \iff \lim_{{x \to a^+}} f(x) = \lim_{{x \to a^-}} f(x) = L
$$

## Propiedades de los Límites

### Límite de una Suma
$$
\lim_{{x \to a}} [f(x) + g(x)] = \lim_{{x \to a}} f(x) + \lim_{{x \to a}} g(x)
$$

### Límite de un Producto
$$
\lim_{{x \to a}} [f(x) \cdot g(x)] = \lim_{{x \to a}} f(x) \cdot \lim_{{x \to a}} g(x)
$$

### Límite de un Cociente
$$
\lim_{{x \to a}} \left[\frac{f(x)}{g(x)}\right] = \frac{\lim_{{x \to a}} f(x)}{\lim_{{x \to a}} g(x)}, \quad \text{si } \lim_{{x \to a}} g(x) \neq 0
$$

### Límite de una Constante
$$
\lim_{{x \to a}} c = c
$$

### Límite de una Función Identidad
$$
\lim_{{x \to a}} x = a
$$

## Casos de Uso del Concepto de Límite

### Caso 1: Determinación de la Continuidad
Una función $f(x)$ es continua en un punto $a$ si:
$$
\lim_{{x \to a}} f(x) = f(a)
$$

### Caso 2: Cálculo de Derivadas
La derivada de una función $f(x)$ en un punto $a$ se define como el límite:
$$
f'(a) = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
$$

### Caso 3: Evaluación de Límites Indeterminados
Para evaluar límites que resultan en formas indeterminadas como $\frac{0}{0}$ o $\frac{\infty}{\infty}$, se utilizan técnicas especiales como factorización, racionalización o la regla de L'Hôpital.

**Enunciado:**
Evaluar $\lim_{{x \to 1}} \frac{x^2 - 1}{x - 1}$.

## Conclusión
El concepto de límite es crucial para el análisis matemático y el cálculo. Permite describir el comportamiento de funciones, definir continuidad y derivadas, y resolver problemas complejos.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 2: Límites y Derivadas. Sección 2.2: El Concepto de Límite.

## Ejercicios Propuestos
1. Evaluar $\lim_{{x \to 3}} (2x + 5)$.
2. Determinar si la función $f(x) = \frac{x^2 - 4}{x - 2}$ es continua en $x = 2$.
3. Calcular $\lim_{{x \to 0}} \frac{\sin(x)}{x}$.
4. Utilizar la definición formal de límite para demostrar que $\lim_{{x \to 1}} (3x + 2) = 5$.
5. Evaluar $\lim_{{x \to \infty}} \frac{1}{x}$.
