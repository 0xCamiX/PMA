## Objetivos de la Clase
- Comprender el concepto de optimización en el contexto de cálculo diferencial.
- Aprender a formular y resolver problemas de maximización y minimización.
- Aplicar técnicas de optimización a problemas prácticos.

## Introducción
La optimización es una rama del cálculo diferencial que se encarga de encontrar el valor máximo o mínimo de una función. Estos problemas son fundamentales en diversas disciplinas como la economía, la ingeniería, la biología y la logística.

## Conceptos Clave

### Función Objetivo
Es la función que queremos maximizar o minimizar. Se denota generalmente como \( f(x) \).

### Dominio
El conjunto de todos los posibles valores de \( x \) donde se puede evaluar la función.

### Intervalo de Optimización
El conjunto de valores de \( x \) donde se busca el máximo o mínimo de la función.

## Pasos para Resolver Problemas de Optimización

1. **Definir la Función Objetivo**:
   - Escribe la función \( f(x) \) que deseas maximizar o minimizar.

2. **Determinar el Dominio**:
   - Identifica las restricciones del problema y establece el dominio de la función.

3. **Encontrar las Derivadas**:
   - Calcula la primera derivada \( f'(x) \) para encontrar los puntos críticos.

4. **Resolver \( f'(x) = 0 \)**:
   - Resuelve la ecuación \( f'(x) = 0 \) para encontrar los posibles puntos críticos.

5. **Aplicar la Primera Derivada**:
   - Usa la primera derivada para determinar los puntos de máximo y mínimo. Utiliza la prueba de la primera derivada (intervalos de crecimiento y decrecimiento).

6. **Evaluar los Puntos Críticos y los Límite del Dominio**:
   - Evalúa \( f(x) \) en los puntos críticos y en los límites del dominio.

7. **Determinar el Valor Óptimo**:
   - Comparar los valores de \( f(x) \) en los puntos críticos y en los límites del dominio para encontrar el máximo y el mínimo.

## Ejemplo

**Problema**: Encontrar el valor máximo y mínimo de la función \( f(x) = x^3 - 6x^2 + 9x + 15 \).

### Paso 1: Definir la Función Objetivo
$$
f(x) = x^3 - 6x^2 + 9x + 15
$$

### Paso 2: Determinar el Dominio
El dominio es todo el conjunto de números reales \( \mathbb{R} \).

### Paso 3: Encontrar la Derivada
$$
f'(x) = 3x^2 - 12x + 9
$$

### Paso 4: Resolver \( f'(x) = 0 \)
$$
3x^2 - 12x + 9 = 0
$$
$$
x^2 - 4x + 3 = 0
$$
$$
(x - 1)(x - 3) = 0
$$
$$
x = 1, \quad x = 3
$$

### Paso 5: Aplicar la Primera Derivada
- **Para \( x < 1 \)**: \( f'(x) > 0 \) (función creciente).
- **Para \( 1 < x < 3 \)**: \( f'(x) < 0 \) (función decreciente).
- **Para \( x > 3 \)**: \( f'(x) > 0 \) (función creciente).

### Paso 6: Evaluar en los Puntos Críticos y los Límites
- Evaluamos en \( x = 1 \), \( x = 3 \) y en los límites del dominio.

$$
f(1) = 1^3 - 6(1)^2 + 9(1) + 15 = 19
$$
$$
f(3) = 3^3 - 6(3)^2 + 9(3) + 15 = 27
$$

### Paso 7: Determinar el Valor Óptimo
- **Máximo**: \( f(3) = 27 \).
- **Mínimo**: \( f(1) = 19 \).

## Aplicaciones de la Optimización

### En Ingeniería
- Diseño de estructuras y optimización de materiales.
- Minimización de costos y maximización de eficiencia.

### En Economía
- Maximización de beneficios y minimización de costos.
- Optimización de funciones de utilidad.

### En Ciencia y Tecnología
- Optimización de algoritmos y modelos matemáticos.
- Problemas de optimización en biología y química.

## Conclusión
La optimización es una herramienta esencial en el análisis matemático y en la solución de problemas reales. Entender cómo formular y resolver problemas de optimización te permitirá abordar una amplia gama de desafíos en diversas disciplinas.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 4: Aplicaciones de las Derivadas. Sección 4.6: Optimización.

## Ejercicios Propuestos
1. Maximizar o minimizar la función \( f(x) = -x^2 + 4x + 1 \).
2. Encontrar el valor máximo y mínimo de \( g(x) = x^2 - 4x + 4 \) en el intervalo \( [0, 4] \).
3. Determinar el valor máximo y mínimo de \( h(x) = x^3 - 9x + 5 \).
4. Optimizar la función \( f(x) = x^2 + 2x - 3 \) en el intervalo \( [-2, 2] \).
5. Resolver el problema de maximización de \( k(x) = \sqrt{4 - x^2} \) en el intervalo \( [-2, 2] \).
