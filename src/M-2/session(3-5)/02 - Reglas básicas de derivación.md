## Objetivos de la Clase
- Aprender las reglas fundamentales para derivar funciones.
- Practicar la aplicación de estas reglas en ejemplos específicos.
- Comprender la importancia de estas reglas en el cálculo diferencial.

## Introducción
Las reglas de derivación básicas son herramientas fundamentales en el cálculo que permiten encontrar la derivada de diversas funciones de manera rápida y eficiente. Estas reglas son esenciales para el análisis y la resolución de problemas en matemáticas, física, ingeniería, y otras disciplinas.

## Regla de la Constante
Si $f(x)$ es una constante $c$, entonces la derivada de $f(x)$ es cero:
$$
\frac{d}{dx}[c] = 0
$$

### Ejemplo
$$
\frac{d}{dx}[5] = 0
$$

## Regla de la Potencia
Si $f(x) = x^n$, donde $n$ es un número real, entonces la derivada de $f(x)$ es:
$$
\frac{d}{dx}[x^n] = nx^{n-1}
$$

### Ejemplo
$$
\frac{d}{dx}[x^3] = 3x^2
$$

## Regla de la Suma
Si $f(x) = g(x) + h(x)$, entonces la derivada de $f(x)$ es la suma de las derivadas de $g(x)$ y $h(x)$:
$$
\frac{d}{dx}[g(x) + h(x)] = g'(x) + h'(x)
$$

### Ejemplo
$$
\frac{d}{dx}[x^2 + 3x] = 2x + 3
$$

## Regla del Producto
Si $f(x) = g(x) \cdot h(x)$, entonces la derivada de $f(x)$ es:
$$
\frac{d}{dx}[g(x) \cdot h(x)] = g'(x) \cdot h(x) + g(x) \cdot h'(x)
$$

### Ejemplo
$$
\frac{d}{dx}[x \cdot \sin(x)] = 1 \cdot \sin(x) + x \cdot \cos(x) = \sin(x) + x \cos(x)
$$

## Regla del Cociente
Si $f(x) = \frac{g(x)}{h(x)}$, entonces la derivada de $f(x)$ es:
$$
\frac{d}{dx}\left[\frac{g(x)}{h(x)}\right] = \frac{g'(x) \cdot h(x) - g(x) \cdot h'(x)}{[h(x)]^2}
$$

### Ejemplo
$$
\frac{d}{dx}\left[\frac{x^2}{x+1}\right] = \frac{2x \cdot (x+1) - x^2 \cdot 1}{(x+1)^2} = \frac{2x^2 + 2x - x^2}{(x+1)^2} = \frac{x^2 + 2x}{(x+1)^2}
$$

## Regla de la Cadena
Si $y = f(u)$ y $u = g(x)$, entonces la derivada de $y$ con respecto a $x$ es:
$$
\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}
$$

### Ejemplo
Si $y = \sin(u)$ y $u = x^2$, entonces:
$$
\frac{dy}{dx} = \frac{d}{dx}[\sin(x^2)] = \cos(x^2) \cdot 2x = 2x \cos(x^2)
$$

## Derivadas de Funciones Trigonométricas
- $\frac{d}{dx}[\sin(x)] = \cos(x)$
- $\frac{d}{dx}[\cos(x)] = -\cos(x)$
- $\frac{d}{dx}[\tan(x)] = \sec^2(x)$

### Ejemplos
$$
\frac{d}{dx}[\sin(x)] = \cos(x)
$$
$$
\frac{d}{dx}[\cos(x)] = -\sin(x)
$$
$$
\frac{d}{dx}[\tan(x)] = \sec^2(x)
$$

## Conclusión
Las reglas de derivación básicas son esenciales para el cálculo diferencial y permiten derivar una amplia variedad de funciones de manera sistemática. La práctica y la familiarización con estas reglas son fundamentales para el dominio del cálculo.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 3: Derivadas. Secciones 3.2 y 3.3: Reglas de Derivación.

## Ejercicios Propuestos
1. Calcular la derivada de $f(x) = 7x^5 - 4x^3 + 2x - 1$.
2. Encontrar $f'(x)$ para $f(x) = \frac{3x^2 - 2x + 1}{x+2}$.
3. Utilizar la regla del producto para hallar la derivada de $f(x) = (x^2 + 1)(\sin(x))$.
4. Aplicar la regla de la cadena para derivar $f(x) = e^{3x^2}$.
5. Determinar la derivada de $f(x) = \tan(x^2)$ utilizando la regla de la cadena.
