# Application of Green's Theorem

**Video URL**: https://www.youtube.com/watch?v=grns_GNYWe4  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
The video addresses minimizing a line integral $\oint_C M dx + N dy$ over a positively oriented simple closed curve $C$ enclosing a region $R$, where:
$$M = -(x^2 y + 3x - 2y), \quad N = 4y^2 x - 2x$$

---

## 2. Key Formulas and Theorems

### Green's Theorem (Tangential Form)
Relates a closed line integral over curve $C$ to a double integral over the region $R$ it encloses:
$$\oint_C M dx + N dy = \iint_R \left( \frac{\partial N}{\partial x} - \frac{\partial M}{\partial y} \right) dx dy$$

### Integrand Computation
$$\frac{\partial N}{\partial x} = 4y^2 - 2$$
$$\frac{\partial M}{\partial y} = -(x^2 - 2) = -x^2 + 2$$
$$\frac{\partial N}{\partial x} - \frac{\partial M}{\partial y} = (4y^2 - 2) - (-x^2 + 2) = x^2 + 4y^2 - 4$$

### Minimization Criterion
To make the integral $\iint_R (x^2 + 4y^2 - 4) dA$ as negative as possible, the region $R$ must include all points where the integrand is negative ($x^2 + 4y^2 - 4 < 0$) and stop where it becomes zero ($x^2 + 4y^2 - 4 = 0$).

### Optimal Boundary Equation
$$x^2 + 4y^2 = 4 \implies \frac{x^2}{4} + y^2 = 1$$
This defines an **ellipse** centered at the origin with semi-major axis $a=2$ and semi-minor axis $b=1$.
