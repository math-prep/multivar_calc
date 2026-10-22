# Line integral on a helix

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Helix Parametrization
$$ec{r}(t) = \langle \cos t, \, \sin t, \, t angle, \quad 	ext{for } 0 \le t \le \pi$$
- Starts at $(1, 0, 0)$ and ends at $(-1, 0, \pi)$.

### 2. Vector Field and Differentials
- **Vector Field:** $ec{F} = \langle zx, \, zy, \, x angle$
- **Parametric Components:**
  $$x = \cos t \implies dx = -\sin t \, dt$$
  $$y = \sin t \implies dy = \cos t \, dt$$
  $$z = t \implies dz = dt$$

### 3. Line Integral Setup & Simplification
$$\oint_C ec{F} \cdot dec{r} = \int_0^\pi (P \, dx + Q \, dy + R \, dz)$$
$$\oint_C ec{F} \cdot dec{r} = \int_0^\pi \Big( (t \cos t)(-\sin t) + (t \sin t)(\cos t) + (\cos t) \Big) \, dt$$
$$\oint_C ec{F} \cdot dec{r} = \int_0^\pi \Big( -t \sin t \cos t + t \sin t \cos t + \cos t \Big) \, dt = \int_0^\pi \cos t \, dt$$

### 4. Integration
$$\int_0^\pi \cos t \, dt = [\sin t]_0^\pi = 0 - 0 = 0$$
