# Extended Gauss' Theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Inverse-Square Vector Field
- **Definition:**
  $$ec{F} = rac{\langle x, y, z angle}{ho^3}, \quad 	ext{where } ho = \sqrt{x^2 + y^2 + z^2}$$

### 2. Divergence Calculation
- **Partial Derivatives:**
  $$rac{\partial ho}{\partial x} = rac{x}{ho}$$
  $$rac{\partial}{\partial x} \left( rac{x}{ho^3} ight) = rac{ho^3 - x \cdot 3ho^2 (x/ho)}{ho^6} = rac{ho^2 - 3x^2}{ho^5}$$
- **Sum of Partial Derivatives:**
  $$
abla \cdot ec{F} = rac{3ho^2 - 3(x^2 + y^2 + z^2)}{ho^5} = 0 \quad (	ext{for } ho 
eq 0)$$

### 3. Extended Gauss's (Divergence) Theorem
- **Theorem Statement for Multi-boundary Domain $D$ (between box $S$ and outer sphere $S_2$ of radius $R$):**
  $$\iiint_D (
abla \cdot ec{F}) \, dV = \iint_{S_2} ec{F} \cdot \hat{n} \, dS - \iint_S ec{F} \cdot \hat{n} \, dS$$

- **Flux Equivalence:**
  Since $
abla \cdot ec{F} = 0$ in $D$:
  $$\iint_S ec{F} \cdot \hat{n} \, dS = \iint_{S_2} ec{F} \cdot \hat{n} \, dS$$

### 4. Sphere Flux Calculation
- On sphere $S_2$ of radius $R$, $\|ec{F}\| = rac{1}{R^2}$ and $ec{F} \cdot \hat{n} = rac{1}{R^2}$:
  $$\iint_{S_2} ec{F} \cdot \hat{n} \, dS = rac{1}{R^2} 	ext{Area}(S_2) = rac{1}{R^2} (4\pi R^2) = 4\pi$$
- **Flux through Box $S$:** $4\pi$
