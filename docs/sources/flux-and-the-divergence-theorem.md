# Flux and the divergence theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Divergence Theorem (Gauss's Theorem)
$$\iint_S ec{F} \cdot \hat{n} \, dS = \iiint_D (
abla \cdot ec{F}) \, dV$$
where $S = \partial D$ is the boundary of the solid cylinder $D$.

### 2. Divergence Calculation
- **Vector Field:**
  $$ec{F} = \langle x^4 y, \, -2x^3 y^2, \, z^2 angle$$

- **Divergence:**
  $$
abla \cdot ec{F} = rac{\partial}{\partial x}(x^4 y) + rac{\partial}{\partial y}(-2x^3 y^2) + rac{\partial}{\partial z}(z^2) = 4x^3 y - 4x^3 y + 2z = 2z$$

### 3. Cylindrical Coordinates Integration
- **Volume Element:** $dV = r \, dz \, dr \, d	heta$
- **Bounds:** $0 \le z \le h, \quad 0 \le r \le R, \quad 0 \le 	heta \le 2\pi$
- **Triple Integral Evaluation:**
  $$	ext{Flux} = \int_0^{2\pi} \int_0^R \int_0^h 2z \cdot r \, dz \, dr \, d	heta$$
  1. Inner ($z$): $\int_0^h 2z r \, dz = h^2 r$
  2. Middle ($r$): $\int_0^R h^2 r \, dr = rac{1}{2} h^2 R^2$
  3. Outer ($	heta$): $\int_0^{2\pi} rac{1}{2} h^2 R^2 \, d	heta = \pi h^2 R^2$

- **Final Flux Result:** $\pi h^2 R^2$
