## Objetivos de la Clase
- Definir el concepto de límites laterales.
- Comprender la notación y el significado de los límites laterales.
- Aplicar técnicas para calcular límites laterales.
- Identificar la relación entre límites laterales y límites generales.

## Introducción
Los límites laterales son una herramienta fundamental en el análisis de funciones, especialmente cuando se estudian discontinuidades y el comportamiento de funciones en puntos críticos. Un límite lateral es el valor al que se aproxima una función cuando la variable independiente se acerca a un punto desde un solo lado: ya sea desde la izquierda (límite lateral izquierdo) o desde la derecha (límite lateral derecho).

## Definición de Límites Laterales

### Límite Lateral Derecho
El límite de $f(x)$ cuando $x$ tiende a $a$ desde la derecha (valores mayores que $a$) se denota como:
$$
\lim_{{x \to a^+}} f(x)
$$

### Límite Lateral Izquierdo
El límite de $f(x)$ cuando $x$ tiende a $a$ desde la izquierda (valores menores que $a$) se denota como:
$$
\lim_{{x \to a^-}} f(x)
$$

### Relación con el Límite General
El límite general de $f(x)$ cuando $x$ tiende a $a$ existe si y solo si ambos límites laterales existen y son iguales:
$$
\lim_{{x \to a}} f(x) = L \iff \lim_{{x \to a^+}} f(x) = \lim_{{x \to a^-}} f(x) = L
$$

## Notación y Ejemplos de Límites Laterales

### Ejemplo 1: Límite Lateral Derecho
Calcular $\lim_{{x \to 2^+}} \frac{1}{x - 2}$.

### Ejemplo 2: Límite Lateral Izquierdo
Calcular $\lim_{{x \to 2^-}} \frac{1}{x - 2}$.

#### Solución:
- Para $x \to 2^+$, $x$ se aproxima a 2 desde valores mayores, entonces $x - 2$ es positivo y $\frac{1}{x - 2} \to \infty$.
- Para $x \to 2^-$, $x$ se aproxima a 2 desde valores menores, entonces $x - 2$ es negativo y $\frac{1}{x - 2} \to -\infty$.

Por lo tanto:
$$
\lim_{{x \to 2^+}} \frac{1}{x - 2} = \infty
$$
$$
\lim_{{x \to 2^-}} \frac{1}{x - 2} = -\infty
$$

## Cálculo de Límites Laterales

### Procedimiento
1. **Identificar el Punto de Interés:**
   Determinar el punto $a$ hacia el cual $x$ se aproxima.

2. **Elegir el Lado de Aproximación:**
   Decidir si se está calculando el límite desde la derecha ($x \to a^+$) o desde la izquierda ($x \to a^-$).

3. **Evaluar la Función:**
   Analizar el comportamiento de $f(x)$ conforme $x$ se aproxima a $a$ desde el lado seleccionado.

### Ejemplo 3: Límite en una Función a Trozos
Calcular $\lim_{{x \to 1^+}} f(x)$ y $\lim_{{x \to 1^-}} f(x)$ donde $f(x)$ está definida por:
$$
f(x) = 
\begin{cases} 
x^2 & \text{si } x < 1 \\
2x + 1 & \text{si } x \geq 1 
\end{cases}
$$

#### Solución:
- Para $x \to 1^+$, usar $f(x) = 2x + 1$:
  $$
  \lim_{{x \to 1^+}} f(x) = \lim_{{x \to 1^+}} (2x + 1) = 3
  $$

- Para $x \to 1^-$, usar $f(x) = x^2$:
  $$
  \lim_{{x \to 1^-}} f(x) = \lim_{{x \to 1^-}} x^2 = 1
  $$

Los límites laterales no son iguales, por lo que el límite general $\lim_{{x \to 1}} f(x)$ no existe.

## Relación entre Límites Laterales y Continuidad
Una función $f(x)$ es continua en un punto $a$ si:
1. $f(a)$ está definida.
2. $\lim_{{x \to a}} f(x)$ existe.
3. $\lim_{{x \to a}} f(x) = f(a)$.

Para que el límite general exista y la función sea continua en $a$, ambos límites laterales deben ser iguales y coincidir con $f(a)$:
$$
\lim_{{x \to a^+}} f(x) = \lim_{{x \to a^-}} f(x) = f(a)
$$

## Conclusión
El cálculo de límites laterales es una técnica esencial para entender el comportamiento de funciones cerca de puntos críticos. Permite determinar discontinuidades y analizar la continuidad de funciones.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 2: Límites y Derivadas. Sección 2.3: Límites Laterales y Continuidad.

## Ejercicios Propuestos
1. Calcular $\lim_{{x \to 0^+}} \frac{1}{x}$ y $\lim_{{x \to 0^-}} \frac{1}{x}$.
2. Determinar $\lim_{{x \to -3^+}} \sqrt{x + 3}$.
3. Evaluar $\lim_{{x \to 1^-}} (3x - 2)$.
4. Calcular los límites laterales de la función $f(x)$ donde $f(x) = x^2 - 4$ si $x < 2$ y $f(x) = 2x - 1$ si $x \geq 2$, en $x = 2$.
5. Analizar la continuidad de $g(x) = \frac{|x|}{x}$ en $x = 0$ usando límites laterales.