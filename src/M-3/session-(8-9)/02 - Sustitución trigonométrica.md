### Objetivos de la Clase

- Comprender la técnica de sustitución trigonométrica.

- Aplicar sustituciones trigonométricas para resolver integrales con raíces cuadradas.

- Aprender trucos y técnicas para abordar integrales difíciles.

## Introducción

La sustitución trigonométrica es una técnica poderosa para resolver integrales que involucran raíces cuadradas. Esta técnica se basa en las identidades trigonométricas y es particularmente útil para integrales que contienen expresiones de la forma $\sqrt{a^2 - x^2}$, $\sqrt{x^2 - a^2}$, y $\sqrt{a^2 + x^2}$.

## Sustituciones Trigonométricas

### 1. Forma $\sqrt{a^2 - x^2}$

Para integrales que contienen $\sqrt{a^2 - x^2}$, usamos la sustitución $x = a \sin(\theta)$, donde $dx = a \cos(\theta) \, d\theta$.

**Identidad Trigonométrica:**

$$

\sin^2(\theta) + \cos^2(\theta) = 1

$$
**Ejemplo:**

$$

\int \sqrt{4 - x^2} \, dx

$$
1. Sustitución: $x = 2 \sin(\theta)$, $dx = 2 \cos(\theta) \, d\theta$

2. Integral en términos de $\theta$:
   $$

   \int \sqrt{4 - (2 \sin(\theta))^2} \cdot 2 \cos(\theta) \, d\theta = \int \sqrt{4 - 4 \sin^2(\theta)} \cdot 2 \cos(\theta) \, d\theta

   $$

   $$

   = \int \sqrt{4 (1 - \sin^2(\theta))} \cdot 2 \cos(\theta) \, d\theta = \int \sqrt{4 \cos^2(\theta)} \cdot 2 \cos(\theta) \, d\theta

   $$
   $$

   = \int 2 \cos(\theta) \cdot 2 \cos(\theta) \, d\theta = 4 \int \cos^2(\theta) \, d\theta

   $$


3. Use la identidad $\cos^2(\theta) = \frac{1 + \cos(2\theta)}{2}$:   $$

   4 \int \cos^2(\theta) \, d\theta = 4 \int \frac{1 + \cos(2\theta)}{2} \, d\theta = 2 \int (1 + \cos(2\theta)) \, d\theta
   $$
   $$
   = 2 \left( \theta + \frac{\sin(2\theta)}{2} \right) + C = 2 \theta + \sin(2\theta) + C
   $$
  
4. Revierta la sustitución:

   $\theta = \sin^{-1}\left(\frac{x}{2}\right)$, $\sin(2\theta) = 2 \sin(\theta) \cos(\theta)$

   $$

   \sin(2\theta) = 2 \left(\frac{x}{2}\right) \sqrt{1 - \left(\frac{x}{2}\right)^2} = x \sqrt{1 - \frac{x^2}{4}}

   $$

5. La solución final:   $$

   2 \sin^{-1}\left(\frac{x}{2}\right) + x \sqrt{1 - \frac{x^2}{4}} + C

   $$
### 2. Forma $\sqrt{a^2 + x^2}$

Para integrales que contienen $\sqrt{a^2 + x^2}$, usamos la sustitución $x = a \tan(\theta)$, donde $dx = a \sec^2(\theta) \, d\theta$.

**Identidad Trigonométrica:**

$$

1 + \tan^2(\theta) = \sec^2(\theta)

$$
**Ejemplo:**

$$

\int \sqrt{1 + x^2} \, dx

$$


1. Sustitución: $x = \tan(\theta)$, $dx = \sec^2(\theta) \, d\theta$

2. Integral en términos de $\theta$:
   $$

   \int \sqrt{1 + \tan^2(\theta)} \cdot \sec^2(\theta) \, d\theta = \int \sqrt{\sec^2(\theta)} \cdot \sec^2(\theta) \, d\theta

   $$

   $$

   = \int \sec^3(\theta) \, d\theta

   $$

  

3. La integral de $\sec^3(\theta)$ es más compleja y se puede resolver usando integración por partes o métodos avanzados. Sin embargo, es importante conocer el enfoque:

  

   La integral de $\sec^3(\theta)$ se puede descomponer usando:

   $$

   \int \sec^3(\theta) \, d\theta = \frac{1}{2} \sec(\theta) \tan(\theta) + \frac{1}{2} \ln|\sec(\theta) + \tan(\theta)| + C

   $$

  

4. Revierta la sustitución:

   $$

   \sec(\theta) = \sqrt{1 + \tan^2(\theta)} = \sqrt{1 + x^2}, \quad \tan(\theta) = x

   $$

  

5. La solución final:

   $$

   \frac{1}{2} x \sqrt{1 + x^2} + \frac{1}{2} \ln|x + \sqrt{1 + x^2}| + C

   $$

  

### 3. Forma $\sqrt{x^2 - a^2}$

Para integrales que contienen $\sqrt{x^2 - a^2}$, usamos la sustitución $x = a \sec(\theta)$, donde $dx = a \sec(\theta) \tan(\theta) \, d\theta$.

  

**Identidad Trigonométrica:**

$$

\sec^2(\theta) - 1 = \tan^2(\theta)

$$

  

**Ejemplo:**

$$

\int \sqrt{x^2 - 4} \, dx

$$

  

1. Sustitución: $x = 2 \sec(\theta)$, $dx = 2 \sec(\theta) \tan(\theta) \, d\theta$

2. Integral en términos de $\theta$:

   $$

   \int \sqrt{(2 \sec(\theta))^2 - 4} \cdot 2 \sec(\theta) \tan(\theta) \, d\theta = \int \sqrt{4 \sec^2(\theta) - 4} \cdot 2 \sec(\theta) \tan(\theta) \, d\theta

   $$

   $$

   = \int \sqrt{4 (\sec^2(\theta) - 1)} \cdot 2 \sec(\theta) \tan(\theta) \, d\theta = \int \sqrt{4 \tan^2(\theta)} \cdot 2 \sec(\theta) \tan(\theta) \, d\theta

   $$

   $$

   = \int 2 \tan(\theta) \cdot 2 \sec(\theta) \tan(\theta) \, d\theta = 4 \int \tan^2(\theta) \sec(\theta) \, d\theta

   $$

  

3. Use la identidad $\tan^2(\theta) = \sec^2(\theta) - 1$:

   $$

   4 \int (\sec^2(\theta) - 1) \sec(\theta) \, d\theta = 4 \int \sec^3(\theta) \, d\theta - 4 \int \sec(\theta) \, d\theta

   $$

  

4. La integral de $\sec^3(\theta)$ ya fue discutida, y $\int \sec(\theta) \, d\theta = \ln|\sec(\theta) + \tan(\theta)| + C$.

  

5. Revierta la sustitución:

   $$

   \sec(\theta) = \frac{x}{2}, \quad \tan(\theta) = \sqrt{\left(\frac{x}{2}\right)^2 - 1} = \frac{\sqrt{x^2 - 4}}{2}

   $$

  

6. La solución final:

   $$

   4 \left( \frac{1}{2} \frac{x}{2} \sqrt{x^2 - 4} + \frac{1}{2} \ln\left|\frac{x}{2} + \frac{\sqrt{x^2 - 4}}{2}\right| \right) + C = x \sqrt{x^2 - 4} + \ln\left| x + \sqrt{x^2 - 

  

4} \right| + C

   $$

## Conclusión

La integración por sustitución trigonométrica y otros trucos son técnicas fundamentales para resolver una amplia variedad de integrales. Con la práctica y el uso de estos métodos y trucos, se pueden abordar incluso las integrales más desafiantes.

### Referencias

- Stewart, J. (2015). Calculus: Early Transcendentals (8th Edition). Brooks Cole.

- Capítulo 7: Técnicas de Integración. Sección 7.3: Sustitución Trigonométrica.

## Ejercicios Propuestos

1. Usa la sustitución trigonométrica para resolver $\int \sqrt{9 - x^2} \, dx$.

2. Aplica la sustitución para resolver $\int \sqrt{x^2 + 16} \, dx$.

3. Resuelve $\int \frac{dx}{\sqrt{x^2 - 4}}$ usando sustitución trigonométrica.