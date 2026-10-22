# Stokes' Theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### Theorem Statement
$$\oint_C ec{F} \cdot dec{r} = \iint_S (
abla 	imes ec{F}) \cdot \hat{n} \, dS$$
where $S$ is the upper hemisphere $x^2 + y^2 + z^2 = 1, z \ge 0$, and $C$ is the boundary unit circle in the xy-plane.

---

### 1. Line Integral $\oint_C ec{F} \cdot dec{r}$
- **Field:** $ec{F} = \langle 2z, \, x, \, y angle$
- **Parametrization of $C$ ($z = 0$):**
  $$x = \cos t, \quad y = \sin t, \quad z = 0, \quad t \in [0, 2\pi]$$
- **Evaluation:**
  $$\oint_C ec{F} \cdot dec{r} = \int_0^{2\pi} x \, dy = \int_0^{2\pi} \cos t (\cos t \, dt) = \int_0^{2\pi} \cos^2 t \, dt = \pi$$

---

### 2. Surface Integral $\iint_S (
abla 	imes ec{F}) \cdot \hat{n} \, dS$
- **Curl Calculation:**
  $$
abla 	imes ec{F} = \langle 1, \, 2, \, 1 angle$$
- **Unit Normal on Unit Sphere:**
  $$\hat{n} = \langle x, \, y, \, z angle$$
- **Dot Product:**
  $$(
abla 	imes ec{F}) \cdot \hat{n} = x + 2y + z$$
- **Symmetry Simplification:**
  By symmetry over upper hemisphere, $\iint_S x \, dS = 0$ and $\iint_S 2y \, dS = 0$.
- **Spherical Coordinate Integration ($z = \cos\phi, dS = \sin\phi \, d\phi \, d	heta$):**
  $$\iint_S z \, dS = \int_0^{2\pi} \int_0^{\pi/2} \cos\phi \sin\phi \, d\phi \, d	heta = 2\pi \left[ rac{\sin^2\phi}{2} ight]_0^{\pi/2} = \pi$$

---

### Verification
Line Integral ($\pi$) = Surface Integral ($\pi$).
