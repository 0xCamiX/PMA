## Objetivos de la Clase
- Comprender cómo calcular límites usando métodos numéricos, analíticos y gráficos.
- Aplicar cada método a diferentes tipos de funciones y situaciones.
- Identificar cuál método es más adecuado según el contexto del problema.

## Introducción
El cálculo de límites es una habilidad fundamental en cálculo. Hay tres métodos principales para calcular límites: numéricamente, analíticamente y gráficamente. Cada método tiene sus ventajas y aplicaciones específicas.

## Cálculo de Límites Numéricamente

### Definición
El cálculo numérico de límites implica evaluar la función en puntos cercanos al valor de interés y observar el comportamiento de las evaluaciones.

### Procedimiento
1. Elegir una serie de valores de $x$ que se acerquen al valor $a$ desde la izquierda y desde la derecha.
2. Evaluar la función $f(x)$ en esos valores.
3. Observar los valores de $f(x)$ para determinar hacia qué valor se aproxima.

### Ejemplo
Calcular $\lim_{{x \to 2}} f(x)$ donde $f(x) = \frac{x^2 - 4}{x - 2}$.

#### Tabla de Valores:
| $x$   | $1.9$ | $1.99$ | $1.999$ | $2.001$ | $2.01$ | $2.1$ |
|-------|-------|--------|---------|---------|--------|-------|
| $f(x)$| $3.9$ | $3.99$ | $3.999$ | $4.001$ | $4.01$ | $4.1$ |

Observamos que $f(x)$ se aproxima a $4$ cuando $x$ se aproxima a $2$.

## Cálculo de Límites Analíticamente

### Definición
El cálculo analítico de límites implica usar propiedades algebraicas y teoremas para encontrar el valor del límite.

### Procedimiento
1. Simplificar la función si es posible.
2. Aplicar propiedades de límites y teoremas (como límites de suma, producto, cociente, etc.).
3. Evaluar el límite directamente o usar técnicas como factorización, racionalización o la regla de L'Hôpital.

### Ejemplo
Calcular $\lim_{{x \to 2}} \frac{x^2 - 4}{x - 2}$.

#### Solución:
1. Factorizar el numerador:
   $$
   \frac{x^2 - 4}{x - 2} = \frac{(x - 2)(x + 2)}{x - 2}
   $$
2. Cancelar el factor común:
   $$
   \frac{(x - 2)(x + 2)}{x - 2} = x + 2
   $$
3. Evaluar el límite:
   $$
   \lim_{{x \to 2}} (x + 2) = 4
   $$

## Cálculo de Límites Gráficamente

### Definición
El cálculo gráfico de límites implica observar el comportamiento de la función en su representación gráfica cerca del punto de interés.

### Procedimiento
1. Dibujar o usar una gráfica de la función $f(x)$.
2. Observar el comportamiento de $f(x)$ a medida que $x$ se aproxima al valor $a$ desde la izquierda y desde la derecha.
3. Determinar el valor hacia el cual se aproxima $f(x)$.

### Ejemplo
Calcular $\lim_{{x \to 2}} f(x)$ donde $f(x) = \frac{x^2 - 4}{x - 2}$ usando la gráfica.

#### Gráfica:
![Gráfica de \( f(x) = \frac{x^2 - 4}{x - 2} \)](https://www.desmos.com/calculator).

Al observar la gráfica, vemos que cuando $x$ se aproxima a $2$ (tanto desde la izquierda como desde la derecha), $f(x)$ se aproxima a $4$.

## Comparación de Métodos

### Ventajas y Desventajas

| Método         | Ventajas                                | Desventajas                              |
|----------------|-----------------------------------------|------------------------------------------|
| Numérico       | Fácil de aplicar con calculadoras.      | Puede ser impreciso.                     |
| Analítico      | Preciso y exacto.                       | Puede requerir técnicas avanzadas.       |
| Gráfico        | Visualmente intuitivo.                  | Depende de la precisión de la gráfica.   |

### Cuándo Usar Cada Método
- **Numérico:** Cuando se necesita una aproximación rápida.
- **Analítico:** Cuando se requiere precisión y exactitud.
- **Gráfico:** Cuando se desea una comprensión visual del comportamiento de la función.

## Conclusión
El cálculo de límites es una herramienta fundamental en matemáticas. Conocer y aplicar los tres métodos (numérico, analítico y gráfico) permite abordar una amplia variedad de problemas y comprender mejor el comportamiento de las funciones.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 2: Límites y Derivadas. Sección 2.2: El Concepto de Límite.

## Ejercicios Propuestos
1. Calcular $\lim_{{x \to 3}} (x^2 - 9)$ numéricamente.
2. Calcular $\lim_{{x \to 1}} \frac{x^2 - 1}{x - 1}$ analíticamente.
3. Utilizar una gráfica para determinar $\lim_{{x \to 0}} \sin(x)/x$.
4. Simplificar $\lim_{{x \to 4}} \frac{x^2 - 16}{x - 4}$ usando métodos analíticos.
5. Evaluar $\lim_{{x \to 5}} (3x + 2)$ numéricamente, analíticamente y gráficamente.
