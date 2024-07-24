## Objetivos de la Clase
- Comprender el concepto de funciones logarítmicas y exponenciales.
- Aprender a identificar y representar funciones logarítmicas y exponenciales.
- Conocer los métodos para resolver ecuaciones que involucren logaritmos y exponentes.

## Introducción
Las funciones logarítmicas y exponenciales son fundamentales en matemáticas y tienen aplicaciones en diversas disciplinas como física, biología, economía, entre otras. Comprender estas funciones y cómo resolver ecuaciones que las involucren es esencial para el estudio avanzado de matemáticas.

## Conceptos Clave

### Funciones Exponenciales
Una función exponencial es una función de la forma:
$$
f(x) = a \cdot b^x
$$
donde \(a\) es una constante, \(b\) es la base (un número positivo distinto de 1), y \(x\) es el exponente.

#### Propiedades de las Funciones Exponenciales
1. **Dominio**: El dominio de una función exponencial es todos los números reales, \((-\infty, \infty)\).
2. **Rango**: El rango de una función exponencial es \((0, \infty)\) para \(a > 0\).
3. **Crecimiento/Decrecimiento**: Si \(b > 1\), la función crece exponencialmente; si \(0 < b < 1\), la función decrece exponencialmente.
4. **Asintota Horizontal**: La función tiene una asintota horizontal en \(y = 0\).

#### Ejemplo
La función \(f(x) = 2 \cdot 3^x\) es una función exponencial. Su dominio es \((-\infty, \infty)\) y su rango es \((0, \infty)\).

### Funciones Logarítmicas
Una función logarítmica es la inversa de una función exponencial y se define como:
$$
f(x) = \log_b(x)
$$
donde \(b\) es la base del logaritmo (un número positivo distinto de 1) y \(x\) es el argumento del logaritmo.

#### Propiedades de las Funciones Logarítmicas
1. **Dominio**: El dominio de una función logarítmica es \((0, \infty)\).
2. **Rango**: El rango de una función logarítmica es \((-\infty, \infty)\).
3. **Crecimiento/Decrecimiento**: Si \(b > 1\), la función crece logarítmicamente; si \(0 < b < 1\), la función decrece logarítmicamente.
4. **Asintota Vertical**: La función tiene una asintota vertical en \(x = 0\).

#### Ejemplo
La función \(f(x) = \log_2(x)\) es una función logarítmica. Su dominio es \((0, \infty)\) y su rango es \((-\infty, \infty)\).

### Propiedades y Reglas Importantes

#### Propiedades de los Logaritmos
1. \(\log_b(xy) = \log_b(x) + \log_b(y)\)
2. \(\log_b\left(\frac{x}{y}\right) = \log_b(x) - \log_b(y)\)
3. \(\log_b(x^c) = c \cdot \log_b(x)\)
4. \(\log_b(b) = 1\)
5. \(\log_b(1) = 0\)

#### Cambio de Base
Para cambiar la base de un logaritmo:
$$
\log_b(x) = \frac{\log_k(x)}{\log_k(b)}
$$
donde \(k\) es la nueva base (generalmente 10 o \(e\)).

### Resolución de Ecuaciones Exponenciales y Logarítmicas

#### Ecuaciones Exponenciales
Para resolver ecuaciones exponenciales, se utilizan logaritmos:
1. Aislar la parte exponencial.
2. Aplicar logaritmo a ambos lados de la ecuación.
3. Usar propiedades de logaritmos para simplificar y resolver para \(x\).

#### Ejemplo
Resuelve \(3^x = 81\):
1. Aislar la parte exponencial:
   $$
   3^x = 81
   $$
2. Aplicar logaritmo a ambos lados (usaremos \(\log\) base 3):
   $$
   \log_3(3^x) = \log_3(81)
   $$
3. Simplificar usando propiedades de logaritmos:
   $$
   x = \log_3(81)
   $$
   Dado que \(81 = 3^4\), entonces:
   $$
   x = 4
   $$

#### Ecuaciones Logarítmicas
Para resolver ecuaciones logarítmicas, se utilizan exponentes:
1. Aislar el logaritmo.
2. Aplicar la exponencial correspondiente a ambos lados de la ecuación.
3. Usar propiedades de los exponentes para simplificar y resolver para \(x\).

#### Ejemplo
Resuelve \(\log_2(x) = 3\):
1. Aislar el logaritmo:
   $$
   \log_2(x) = 3
   $$
2. Aplicar la exponencial correspondiente a ambos lados (base 2):
   $$
   2^{\log_2(x)} = 2^3
   $$
3. Simplificar usando propiedades de los exponentes:
   $$
   x = 8
   $$

## Conclusión
Las funciones logarítmicas y exponenciales son esenciales en muchas áreas de las matemáticas y sus aplicaciones. Comprender cómo trabajar con estas funciones y resolver ecuaciones que las involucren es fundamental para el estudio avanzado de matemáticas y ciencias aplicadas.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 1: Fundamentos. Sección 1.6: Funciones Exponenciales y Logarítmicas.

## Ejercicios Propuestos
1. Encuentra el dominio y rango de la función \(f(x) = 2^x\).
2. Simplifica la expresión \(\log_3(27) + \log_3(9)\).
3. Resuelve la ecuación exponencial \(5^{2x} = 125\).
4. Resuelve la ecuación logarítmica \(\log(x - 2) = 1\).
5. Utiliza la propiedad de cambio de base para calcular \(\log_5(25)\) usando logaritmos comunes (base 10).
