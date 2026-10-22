# More Stokes' Theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Vector Field Definition
$$ec{F} = ho^n \langle x, y, z angle, \quad 	ext{where } ho = \sqrt{x^2 + y^2 + z^2}$$

### 2. Partial Derivatives of $ho$
$$rac{\partial ho}{\partial x} = rac{x}{ho}, \quad rac{\partial ho}{\partial y} = rac{y}{ho}, \quad rac{\partial ho}{\partial z} = rac{z}{ho}$$

### 3. Curl Calculation
- Components $M = xho^n, N = yho^n, P = zho^n$:
  $$rac{\partial P}{\partial y} = z \cdot n ho^{n-1} rac{y}{ho} = n y z ho^{n-2}$$
  $$rac{\partial N}{\partial z} = y \cdot n ho^{n-1} rac{z}{ho} = n y z ho^{n-2}$$
  $$\implies rac{\partial P}{\partial y} - rac{\partial N}{\partial z} = 0$$

- By symmetry across components:
  $$
abla 	imes ec{F} = ec{0}$$

### 4. Gradient Field Criterion
- **Domain Analysis:**
  - $n \ge 0$: Domain is all of $\mathbb{R}^3$ (simply connected).
  - $n < 0$: Domain is $\mathbb{R}^3 \setminus \{(0,0,0)\}$ (which remains simply connected in 3D).
- **Conclusion:** Since $
abla 	imes ec{F} = ec{0}$ on a simply connected domain in 3D, $ec{F}$ is a **gradient field** ($ec{F} = 
abla f$).
