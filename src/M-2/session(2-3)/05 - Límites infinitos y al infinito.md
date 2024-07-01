## Objetivos de la Clase
- Definir los conceptos de límites infinitos y límites al infinito.
- Entender la notación y el significado de estos límites.
- Aplicar técnicas para calcular límites infinitos y al infinito.
- Reconocer la importancia de estos conceptos en el análisis de funciones.

## Introducción
En cálculo, es común encontrarse con situaciones donde las funciones crecen sin límite o tienden a un valor a medida que la variable independiente se hace muy grande o muy pequeña. Los límites infinitos y los límites al infinito nos ayudan a describir este comportamiento.

## Límites Infinitos

### Definición de Límite Infinito
Si $f(x)$ crece sin límite cuando $x$ se aproxima a un valor $a$, decimos que el límite de $f(x)$ cuando $x$ tiende a $a$ es infinito, y escribimos:
$$
\lim_{{x \to a}} f(x) = \infty
$$
Si $f(x)$ decrece sin límite (hacia menos infinito) cuando $x$ se aproxima a un valor $a$, escribimos:
$$
\lim_{{x \to a}} f(x) = -\infty
$$

### Notación y Ejemplos

#### Ejemplo 1: Límite Infinito
Calcular $\lim_{{x \to 0}} \frac{1}{x^2}$.

#### Solución:
Cuando $x$ se aproxima a 0, $\frac{1}{x^2}$ crece sin límite positivo:
$$
\lim_{{x \to 0}} \frac{1}{x^2} = \infty
$$

## Límites al Infinito

### Definición de Límite al Infinito
Si $f(x)$ tiende a un valor $L$ cuando $x$ crece sin límite (ya sea positivo o negativo), decimos que el límite de $f(x)$ cuando $x$ tiende a infinito es $L$, y escribimos:
$$
\lim_{{x \to \infty}} f(x) = L
$$
$$
\lim_{{x \to -\infty}} f(x) = L
$$

### Notación y Ejemplos

#### Ejemplo 2: Límite al Infinito
Calcular $\lim_{{x \to \infty}} \frac{1}{x}$.

#### Solución:
Cuando $x$ crece sin límite, $\frac{1}{x}$ se aproxima a 0:
$$
\lim_{{x \to \infty}} \frac{1}{x} = 0
$$

### Ejemplo 3: Límite al Infinito de una Función Polinómica
Calcular $\lim_{{x \to \infty}} (3x^2 + 2x - 5)$.

#### Solución:
Cuando $x$ crece sin límite, el término dominante es $3x^2$:
$$
\lim_{{x \to \infty}} (3x^2 + 2x - 5) = \infty
$$

## Asintotas Horizontales y Verticales

### Asintotas Horizontales
Una función $f(x)$ tiene una asíntota horizontal si:
$$
\lim_{{x \to \infty}} f(x) = L \quad \text{o} \quad \lim_{{x \to -\infty}} f(x) = L
$$

#### Ejemplo 4: Asíntota Horizontal
Determinar la asíntota horizontal de $f(x) = \frac{2x}{x+1}$.

#### Solución:
$$
\lim_{{x \to \infty}} \frac{2x}{x+1} = 2
$$
La función $f(x) = \frac{2x}{x+1}$ tiene una asíntota horizontal en $y = 2$.

### Asintotas Verticales
Una función $f(x)$ tiene una asíntota vertical en $x = a$ si:
$$
\lim_{{x \to a}} f(x) = \infty \quad \text{o} \quad \lim_{{x \to a}} f(x) = -\infty
$$

#### Ejemplo 5: Asíntota Vertical
Determinar la asíntota vertical de $f(x) = \frac{1}{x-2}$.

#### Solución:
$$
\lim_{{x \to 2}} \frac{1}{x-2} = \infty
$$
La función $f(x) = \frac{1}{x-2}$ tiene una asíntota vertical en $x = 2$.

## Técnicas para Calcular Límites Infinitos y al Infinito

### Dominio de Funciones
Al analizar los límites al infinito, es importante considerar el término dominante en la función, especialmente para funciones polinómicas y racionales.

#### Ejemplo 6: Límite al Infinito de una Función Racional
Calcular $\lim_{{x \to \infty}} \frac{3x^3 - x + 4}{2x^3 + x^2 - 5}$.

#### Solución:
El término dominante en ambos el numerador y el denominador es $x^3$:
$$
\lim_{{x \to \infty}} \frac{3x^3 - x + 4}{2x^3 + x^2 - 5} = \frac{3}{2}
$$

### L'Hôpital
Para ciertos límites infinitos e indeterminados, se puede aplicar la regla de L'Hôpital.

#### Ejemplo 7: Aplicación de L'Hôpital
Calcular $\lim_{{x \to \infty}} \frac{\sin(x)}{x}$.

#### Solución:
$$
\lim_{{x \to \infty}} \frac{\sin(x)}{x} = 0 \quad (\text{aplicando L'Hôpital})
$$

## Conclusión
Los límites infinitos y los límites al infinito son conceptos clave en el cálculo que nos permiten describir el comportamiento de funciones en situaciones extremas. Son fundamentales para entender asíntotas y el comportamiento global de funciones.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 2: Límites y Derivadas. Sección 2.6: Límites al Infinito e Infinitos.

## Ejercicios Propuestos
1. Calcular $\lim_{{x \to 3^+}} \frac{1}{x-3}$.
2. Determinar $\lim_{{x \to -\infty}} (x^2 - 5x + 6)$.
3. Evaluar $\lim_{{x \to \infty}} \frac{2x^2 - x + 1}{x^2 + 3x + 2}$.
4. Encontrar las asíntotas horizontales y verticales de $f(x) = \frac{4x}{x^2 - 1}$.
5. Aplicar L'Hôpital para calcular $\lim_{{x \to \infty}} \frac{e^x}{x^2}$.