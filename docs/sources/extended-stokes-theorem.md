# Extended Stokes' Theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Vector Field and Curl
- **Vector Field:**
  $$ec{F} = \langle 2xz - 2y, \, 2yz + 2x, \, x^2 + y^2 + z^2 angle$$

- **Curl Calculation:**
  $$
abla 	imes ec{F} = egin{vmatrix} \hat{i} & \hat{j} & \hat{k} \ rac{\partial}{\partial x} & rac{\partial}{\partial y} & rac{\partial}{\partial z} \ 2xz - 2y & 2yz + 2x & x^2 + y^2 + z^2 \end{vmatrix} = 0\hat{i} + 0\hat{j} + 4\hat{k} = 4\hat{k}$$

### 2. Surface Integral on Cylinder Surface
- **Cylinder $x^2 + y^2 = b^2$ Normal Vector:**
  $\hat{n}$ is radial in the xy-plane $\implies \hat{n} \cdot \hat{k} = 0$.
  $$\iint_S (
abla 	imes ec{F}) \cdot \hat{n} \, dS = \iint_S (4\hat{k} \cdot \hat{n}) \, dS = 0$$

### 3. Extended Stokes' Theorem
- **Boundary Relationship:**
  $$\iint_S (
abla 	imes ec{F}) \cdot \hat{n} \, dS = \oint_{C_1} ec{F} \cdot dec{r} - \oint_C ec{F} \cdot dec{r} = 0 \implies \oint_C ec{F} \cdot dec{r} = \oint_{C_1} ec{F} \cdot dec{r}$$
  where $C_1$ is the circle of radius $b$ in the plane $z = 0$.

### 4. Line Integral Calculation over $C_1$
- **Parametrization of $C_1$ ($z = 0$):**
  $$x = b \cos	heta, \quad y = b \sin	heta, \quad dx = -b \sin	heta \, d	heta, \quad dy = b \cos	heta \, d	heta$$
- **Integral:**
  $$\oint_{C_1} ec{F} \cdot dec{r} = \int_0^{2\pi} (-2y \, dx + 2x \, dy) = \int_0^{2\pi} (2b^2 \sin^2	heta + 2b^2 \cos^2	heta) \, d	heta = 4\pi b^2$$
- **Final Result:** $\oint_C ec{F} \cdot dec{r} = 4\pi b^2$
