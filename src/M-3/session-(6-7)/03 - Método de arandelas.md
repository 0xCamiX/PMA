### Introducción

El método de arandelas es una técnica utilizada para calcular el volumen de un sólido de revolución cuando la región que rota para crea una forma con un agujero (como una arandela). Este método se aplica cuando se rota una región alrededor de un eje que no es uno de sus bordes, creando una forma hueca.

### Conceptos Clave

1. **Eje de Revolución**: La línea alrededor de la cual se rota una región para formar un sólido.
2. **Método de Arandelas**: Una técnica de integración para encontrar el volumen de sólidos de revolución con huecos, mediante la suma de volúmenes de discos concéntricos.

### Pasos del Método de Arandelas

#### Paso 1: Identificar la Región y el Eje de Revolución

Determina la región que rota y el eje de revolución. La región suele estar delimitada por dos funciones $y=f(x$) y $y=g(x)$, y los límites de integración $x=a$ y $x=b$.

#### Paso 2: Configurar el Elemento de Volumen

Para un pequeño espesor $dx$, el volumen de una arandela es:

$$V=π([R(x)]^2−[r(x)]^2)dx$$

Donde $R(x)$ es el radio exterior y $r(x)$ es el radio interior.

#### Paso 3: Integrar para Encontrar el Volumen Total

El volumen total $V$ se encuentra integrando el elemento de volumen desde $x=a$ hasta $x=b$

$$V=∫_a ^b \pi([R(x)]^2−[r(x)]^2)dx$$

**Arandela Infinitesimal**: En el método de arandelas, el sólido se descompone en arandelas delgadas (o discos con huecos), y el volumen de cada arandela se calcula para sumarlos y obtener el volumen total.