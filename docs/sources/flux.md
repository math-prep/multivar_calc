# Flux

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Divergence Theorem Application
$$\iint_S ec{F} \cdot \hat{n} \, dS + \iint_{S_2} ec{F} \cdot \hat{n} \, dS = \iiint_D (
abla \cdot ec{F}) \, dV$$
where:
- $S$: Right hemisphere $x^2 + y^2 + z^2 = R^2, y \ge 0$.
- $S_2$: Flat disk $y = 0, x^2 + z^2 \le R^2$ in xz-plane.
- $D$: Solid hemisphere bounded by $S \cup S_2$.

### 2. Divergence Calculation
- **Field:** $ec{F} = \langle 0, y, 0 angle$
- **Divergence:**
  $$
abla \cdot ec{F} = rac{\partial 0}{\partial x} + rac{\partial y}{\partial y} + rac{\partial 0}{\partial z} = 1$$

### 3. Disk Integral
- On disk $S_2$ ($y = 0$), $ec{F} = \langle 0, 0, 0 angle$:
  $$\iint_{S_2} ec{F} \cdot \hat{n} \, dS = 0$$

### 4. Volume Integral & Result
- **Volume of Solid Hemisphere $D$:**
  $$\iiint_D 1 \, dV = 	ext{Volume}(D) = rac{2}{3}\pi R^3$$

- **Flux Through Hemisphere $S$:**
  $$	ext{Flux} = rac{2}{3}\pi R^3 - 0 = rac{2}{3}\pi R^3$$
