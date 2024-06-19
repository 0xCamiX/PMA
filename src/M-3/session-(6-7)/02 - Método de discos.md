### Introducción
En cálculo, un sólido de revolución se forma cuando una región en el plano se rota alrededor de una línea (llamada eje de revolución). El método del disco es una técnica para encontrar el volumen de tales sólidos. En esta clase, aprenderemos cómo aplicar el método del disco para calcular el volumen de un sólido de revolución.

### Conceptos claves

- **Eje de Revolución**: La línea alrededor de la cual se rota una región para formar un sólido.
- **Método del Disco**: Una técnica de integración utilizada para calcular el volumen de un sólido de revolución generando discos infinitesimales perpendiculares al eje de revolución.

### Pasos del Método del Disco

#### Paso 1: Identificar la Región y el Eje de Revolución

Determina la región que se rota y el eje de revolución. La región suele estar delimitada por una función $y=f(x)$, el eje $x$, y dos líneas verticales $x=a$ y $x=b$.

#### Paso 2: Configurar el Elemento de Volumen

Para un pequeño espesor $dx$, el volumen de un disco es:
$$dV=\pi [f(x)]^2dx$$
Donde $\pi f^2(x)$ es el área del disco y $dx$ es el espesor.

#### Paso 3: Integrar para Encontrar el Volumen Total

El volumen total $V$ se encuentra integrando el elemento de volumen desde $x=a$ hasta $x=b$

$$V=\int_a^b  \pi [f(x)]^2dx $$
### Conceptos Clave

- **Sólido de Revolución**: Sólido formado al rotar una región alrededor de un eje.
- **Disco Infinitesimal**: Sección transversal del sólido, utilizada para aproximar su volumen.
- **Integral Definida**: Herramienta matemática para sumar volúmenes infinitesimales y encontrar el volumen total.

### Explicación de Conceptos Clave

- **Sólido de Revolución**: Estos sólidos se generan rotando una región bidimensional alrededor de un eje, produciendo una figura tridimensional simétrica.
- **Disco Infinitesimal**: En el método del disco, el sólido se descompone en discos delgados (o cilindros de grosor infinitesimal), y el volumen de cada disco se calcula para sumarlos y obtener el volumen total.
- **Integral Definida**: Es fundamental en el cálculo de volúmenes, permitiendo sumar todos los discos infinitesimales para encontrar el volumen del sólido de revolución.

### NOTA: Una sección transversal es una representación bidimensional obtenida al cortar un objeto tridimensional con un plano. Es similar a ver el interior de un objeto al hacer un corte limpio y observar la forma resultante en la superficie de ese corte. Este concepto es ampliamente utilizado en geometría, ingeniería, medicina (como en tomografías), y muchas otras disciplinas para analizar la estructura interna de un objeto.
