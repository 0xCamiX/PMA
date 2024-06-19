### Introducción

El método de capas, también conocido como método de cascarones cilíndricos, es una técnica utilizada para calcular el volumen de un sólido de revolución. Este método es especialmente útil cuando el sólido se genera al rotar una región alrededor de un eje que no es uno de sus bordes.

### Conceptos Clave

1. **Eje de Revolución**: La línea alrededor de la cual se rota una región para formar un sólido.
2. **Método de Capas**: Una técnica de integración que utiliza cascarones cilíndricos para calcular el volumen de sólidos de revolución.

### Pasos del Método de Capas

#### Paso 1: Identificar la Región y el Eje de Revolución

Determina la región que se rota y el eje de revolución. La región suele estar delimitada por una función $y=f(x)$ o $x=g(y)$, y los límites de integración correspondientes.

#### Paso 2: Configurar el Elemento de Volumen

Para un pequeño espesor $dx$ o $dy$, el volumen de un cascarón cilíndrico es:

$$dV=2π(radio)(altura)(espesor)$$

Dependiendo del eje de revolución, se eligen las expresiones adecuadas para radio y altura.

#### Paso 3: Integrar para Encontrar el Volumen Total

El volumen total $V$ se encuentra integrando el elemento de volumen en el intervalo adecuado.

### Ejemplo Detallado

Supongamos que queremos encontrar el volumen del sólido generado al rotar la región entre $y=x^2$ ,  $y=4$ alrededor del eje $y$.

#### Paso 1: Identificar la Región y el Eje de Revolución

- Función inferior: $y=x^2$
- Función superior: $y=4$
- Eje de revolución: Eje $y$

#### Paso 2: Configurar el Elemento de Volumen

Para $y=x^2$, $y=4$, usamos $dy$ como el espesor. Entonces:

- Radio: $x=\sqrt{y}$.
- Altura: $4-y=x$

El volumen de un cascarón cilíndrico es:

$$dV=2π(\sqrt{y})(4−y)dy$$
#### Paso 3: Integrar para Encontrar el Volumen Total

$$V = \int _{0} ^{4} 2\pi(\sqrt{y})(4-y)dy$$
