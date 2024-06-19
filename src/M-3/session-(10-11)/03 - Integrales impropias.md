## Objetivos de la Clase
- Comprender el concepto de integrales impropias.
- Conocer los diferentes casos de integrales impropias.
- Aplicar métodos para evaluar integrales impropias.

## Introducción
Las integrales impropias son integrales que involucran límites infinitos o integrandos que tienen discontinuidades. Estas integrales se extienden más allá de las integrales definidas estándar y requieren técnicas especiales para su evaluación.

## Casos de Integrales Impropias

### Caso 1: Integrales en Intervalos Infinitos
Cuando el intervalo de integración es infinito, la integral se llama impropia de primera especie. Existen dos subcasos:

#### Subcaso 1.1: Integrales con un Límite de Integración Infinito
$$
\int_a^{\infty} f(x) \, dx = \lim_{b \to \infty} \int_a^b f(x) \, dx
$$

#### Subcaso 1.2: Integrales con ambos Límites de Integración Infinitos
$$
\int_{-\infty}^{\infty} f(x) \, dx = \lim_{a \to -\infty} \int_a^c f(x) \, dx + \lim_{b \to \infty} \int_c^b f(x) \, dx
$$
donde $c$ es un punto intermedio elegido convenientemente.

### Caso 2: Integrales con Discontinuidades en el Intervalo de Integración
Cuando el integrando tiene una discontinuidad en el intervalo de integración, la integral se llama impropia de segunda especie. Existen dos subcasos:

#### Subcaso 2.1: Discontinuidad en el Límite de Integración
$$
\int_a^b f(x) \, dx \quad \text{donde } f(x) \text{ tiene una discontinuidad en } x = b
$$
Se evalúa como:
$$
\int_a^b f(x) \, dx = \lim_{c \to b^-} \int_a^c f(x) \, dx
$$

#### Subcaso 2.2: Discontinuidad Dentro del Intervalo de Integración
$$
\int_a^b f(x) \, dx \quad \text{donde } f(x) \text{ tiene una discontinuidad en } x = c, \text{ con } a < c < b
$$
Se evalúa como:
$$
\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx
$$
Cada integral se trata como una integral impropia de segunda especie con límites apropiados:
$$
\int_a^c f(x) \, dx = \lim_{d \to c^-} \int_a^d f(x) \, dx
$$
$$
\int_c^b f(x) \, dx = \lim_{e \to c^+} \int_e^b f(x) \, dx
$$
## Procedimiento General para Evaluar Integrales Impropias
1. **Identificar la Naturaleza de la Integral**: Determine si la integral es impropia de primera o segunda especie.
2. **Reescribir la Integral**: Exprese la integral utilizando los límites adecuados según el caso correspondiente.
3. **Evaluar los Límites**: Calcule las integrales definidas y luego evalúe los límites correspondientes.
4. **Determinar la Convergencia**: Verifique si los límites existen y son finitos para determinar si la integral impropia converge o diverge.

## Conclusión
Las integrales impropias amplían el concepto de integración para incluir intervalos infinitos y funciones con discontinuidades. Comprender los diferentes casos y aplicar los métodos adecuados es esencial para evaluar estas integrales correctamente.

### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 7: Técnicas de Integración. Sección 7.8: Integrales Impropias.

## Ejercicios Propuestos
1. Evaluar la integral impropia $\int_1^{\infty} \frac{1}{x^2} \, dx$.
2. Determinar si la integral $\int_{0}^{1} \frac{1}{\sqrt{x}} \, dx$ converge o diverge.
3. Evaluar la integral $\int_{-\infty}^{\infty} e^{-x^2} \, dx$.
4. Evaluar la integral $\int_1^3 \frac{1}{(x-2)^2} \, dx$.
