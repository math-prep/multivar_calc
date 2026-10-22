# Conservative fields and exact differentials

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Condition for Conservative Vector Field
- **Zero Curl Condition:**
  $$
abla 	imes ec{F} = ec{0}$$

- **Curl Formula for $ec{F} = \langle P, Q, R angle$:**
  $$
abla 	imes ec{F} = \left( rac{\partial R}{\partial y} - rac{\partial Q}{\partial z} ight) \hat{i} + \left( rac{\partial P}{\partial z} - rac{\partial R}{\partial x} ight) \hat{j} + \left( rac{\partial Q}{\partial x} - rac{\partial P}{\partial y} ight) \hat{k}$$

- **Application to Given Field $ec{F} = \langle y, x + byz, y^2 + 1 angle$:**
  $$
abla 	imes ec{F} = (2y - by)\hat{i} + (0 - 0)\hat{j} + (1 - 1)\hat{k} = (2 - b)y \hat{i} = ec{0} \implies b = 2$$

### 2. Potential Function $f(x, y, z)$
- **Definition:** $ec{F} = 
abla f$
- **Line Integral Method from Origin to $(x_1, y_1, z_1)$ along piecewise segments $C_1, C_2, C_3$:**
  $$f(x_1, y_1, z_1) = \int_{C_1} P(x, 0, 0) \, dx + \int_{C_2} Q(x_1, y, 0) \, dy + \int_{C_3} R(x_1, y_1, z) \, dz$$
  $$f(x_1, y_1, z_1) = 0 + \int_0^{y_1} x_1 \, dy + \int_0^{z_1} (y_1^2 + 1) \, dz = x_1 y_1 + z_1 (y_1^2 + 1) + C$$
  $$f(x, y, z) = xy + z(y^2 + 1) + C$$

### 3. Exact Differential Condition
- $ec{F} \cdot dec{r} = P\,dx + Q\,dy + R\,dz$ is exact because $ec{F}$ is conservative ($
abla 	imes ec{F} = ec{0}$) on the simply connected domain $\mathbb{R}^3$.
