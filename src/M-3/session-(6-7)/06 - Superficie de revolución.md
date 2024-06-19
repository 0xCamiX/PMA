
### Objetivos de la Clase
- Comprender el concepto de superficies de revolución.
- Aprender a generar una superficie de revolución a partir de una curva.
- Calcular el área de una superficie de revolución usando integrales.

### Introducción
Las superficies de revolución son superficies generadas al rotar una curva alrededor de un eje fijo. Este concepto es fundamental en el cálculo y tiene aplicaciones en diversas áreas de la ciencia y la ingeniería. En esta clase, exploraremos cómo se generan estas superficies y cómo se calcula su área.

#### Concepto de Superficie de Revolución
Una superficie de revolución se forma al girar una curva alrededor de un eje. Por ejemplo, al rotar la curva $y = f(x)$ alrededor del eje  $x$, obtenemos una superficie en tres dimensiones.

**Definición:** Una superficie de revolución es la superficie obtenida al rotar una curva $y = f(x)$, definida en el intervalo $[a, b]$, alrededor del eje $x$.

#### Área de una Superficie de Revolución
Para encontrar el área de una superficie de revolución generada por la curva $y=f(x)$ alrededor del eje $x$, usamos la fórmula de integración:

$$A = 2\pi \int_{a}^{b} f(x) \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx$$
**Ejemplo 2:** Calcular el área de la superficie generada al rotar $y = \sqrt{x}$ desde $[0,1]$  alrededor del eje $x$.

1. **Curva original:** $y = \sqrt{x}$
2. **Derivada:** $\frac{dy}{dx} = \frac{1}{2\sqrt{x}}$
3. **Área:**
   $$
   A = 2\pi \int_{0}^{1} \sqrt{x} \sqrt{1 + \left(\frac{1}{2\sqrt{x}}\right)^2} \, dx
   $$
4. **Simplificación:**
   $$
   A = 2\pi \int_{0}^{1} \sqrt{x} \sqrt{1 + \frac{1}{4x}} \, dx = 2\pi \int_{0}^{1} \sqrt{x} \sqrt{\frac{4x+1}{4x}} \, dx = \pi \int_{0}^{1} \sqrt{4x^2 + x} \, dx
$$
5. **Evaluación del integral:** Este integral puede ser resuelto usando métodos de integración avanzada, como sustitución trigonométrica o numéricamente.

#### Tarea para Practicar
1. Calcular el área de la superficie generada al rotar la curva $y = x^3$ desde $[0,1]$ alrededor del eje $x$.
2. Generar y visualizar la superficie de revolución de la función $y=sin(x)$ desde $[0, \pi]$.
3. 
#### Referencias
- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.
- Capítulo 8: Aplicaciones de la Integración. Sección 8.3: Superficies de Revolución y el Teorema de Pappus.

#### Conclusión
Las superficies de revolución son una aplicación poderosa de la integración en el cálculo. Comprender cómo se generan y cómo calcular su área es fundamental para estudiantes de matemáticas y ciencias aplicadas. La práctica con ejemplos específicos fortalecerá tu habilidad para trabajar con estos conceptos.