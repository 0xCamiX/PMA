## Objetivos de la Clase
- Definir el concepto de continuidad en un punto y en un intervalo.
- Entender las condiciones necesarias para que una función sea continua en un punto.
- Aplicar la definición de continuidad a diferentes tipos de funciones.
- Identificar y clasificar diferentes tipos de discontinuidades.

## Introducción
La continuidad es una propiedad fundamental de las funciones en el cálculo. Intuitivamente, una función es continua si su gráfica puede ser dibujada sin levantar el lápiz del papel. Formalmente, la continuidad se puede entender mejor utilizando el concepto de límites.

## Definición de Continuidad

### Continuidad en un Punto
Una función $f(x)$ es continua en un punto $a$ si se cumplen las siguientes tres condiciones:
1. $f(a)$ está definida.
2. $\lim_{{x \to a}} f(x)$ existe.
3. $\lim_{{x \to a}} f(x) = f(a)$.

En otras palabras, el valor de la función en $a$ debe coincidir con el límite de la función cuando $x$ se aproxima a $a$.

### Notación
Para expresar que una función $f(x)$ es continua en un punto $a$, escribimos:
$$
f \text{ es continua en } a.
$$

### Continuidad en un Intervalo
Una función es continua en un intervalo si es continua en cada punto del intervalo.

### Tipos de Continuidad
- **Continuidad en un Punto:** $f(x)$ es continua en $a$.
- **Continuidad en un Intervalo Cerrado [a, b]:** $f(x)$ es continua en cada punto dentro del intervalo y en los extremos $a$ y $b$.
- **Continuidad en un Intervalo Abierto (a, b):** $f(x)$ es continua en cada punto dentro del intervalo.

## Ejemplos de Continuidad

### Ejemplo 1: Función Polinómica
Los polinomios son continuos en todos los números reales.

### Ejemplo 2: Función Racional
La función $f(x) = \frac{1}{x}$ no es continua en $x = 0$ porque $f(0)$ no está definida.

## Tipos de Discontinuidades

### Discontinuidad Evitable
Una discontinuidad evitable ocurre si $\lim_{{x \to a}} f(x)$ existe, pero $f(a)$ no está definida o $\lim_{{x \to a}} f(x) \neq f(a)$. Se puede "arreglar" definiendo adecuadamente $f(a)$.

### Discontinuidad de Salto
Una discontinuidad de salto ocurre si los límites laterales existen pero no son iguales:
$$
\lim_{{x \to a^-}} f(x) \neq \lim_{{x \to a^+}} f(x)
$$

### Discontinuidad Infinita
Una discontinuidad infinita ocurre si $f(x)$ se aproxima a infinito positivo o negativo al acercarse a $a$.

## Ejemplos de Discontinuidades

### Ejemplo 3: Discontinuidad Evitable
$$
f(x) = 
\begin{cases} 
\frac{x^2 - 1}{x - 1} & \text{si } x \neq 1 \\
2 & \text{si } x = 1 
\end{cases}
$$
La discontinuidad en $x = 1$ es evitable porque $\lim_{{x \to 1}} f(x) = 2$.

### Ejemplo 4: Discontinuidad de Salto
$$
f(x) = 
\begin{cases} 
x + 2 & \text{si } x < 1 \\
3 - x & \text{si } x \geq 1 
\end{cases}
$$
La discontinuidad en $x = 1$ es de salto porque $\lim_{{x \to 1^-}} f(x) \neq \lim_{{x \to 1^+}} f(x)$.

### Ejemplo 5: Discontinuidad Infinita
$$
f(x) = \frac{1}{x - 2}
$$
Hay una discontinuidad infinita en $x = 2$.

## Propiedades de Funciones Continuas

### Teorema del Valor Intermedio
Si $f(x)$ es continua en el intervalo cerrado $[a, b]$ y $N$ es cualquier número entre $f(a)$ y $f(b)$, entonces existe al menos un número $c$ en el intervalo $(a, b)$ tal que $f(c) = N$.

### Teorema de Weierstrass
Si $f(x)$ es continua en el intervalo cerrado $[a, b]$, entonces $f(x)$ alcanza un máximo y un mínimo en ese intervalo.

## Conclusión
La continuidad es una propiedad clave de las funciones que tiene aplicaciones importantes en el cálculo y en la comprensión del comportamiento de las funciones. Reconocer los diferentes tipos de discontinuidades y saber cómo tratar con ellas es esencial para un estudio más avanzado de la matemática.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 2: Límites y Derivadas. Sección 2.5: Continuidad.

## Ejercicios Propuestos
1. Determinar si la función $f(x) = \frac{x^2 - 4}{x - 2}$ es continua en $x = 2$.
2. Evaluar la continuidad de $f(x) = |x|$ en $x = 0$.
3. Encontrar y clasificar las discontinuidades de $f(x) = \frac{1}{x^2 - 1}$.
4. Verificar la continuidad de la función $f(x) = x^3$ en todo $\mathbb{R}$.
5. Utilizar el teorema del valor intermedio para demostrar que la ecuación $x^3 + x - 1 = 0$ tiene al menos una solución real en el intervalo $(0, 1)$.