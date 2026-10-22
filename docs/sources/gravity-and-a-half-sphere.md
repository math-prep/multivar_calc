# Gravity and a half-sphere

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Gravitational Force Formula
- **Infinitesimal Force Magnitude:**
  $$dF = rac{G m_0 \, dm}{ho^2}$$
- **Direction Unit Vector (Z-component):**
  $$\hat{u}_z = rac{z}{ho} = \cos\phi$$
- **Symmetry:** By symmetry, $F_x = 0$ and $F_y = 0$.

### 2. Mass Element $dm$
- **Density:** $\delta = \sqrt{x^2 + y^2} = r = ho \sin\phi$
- **Mass Element:**
  $$dm = \delta \, dV = (ho \sin\phi)(ho^2 \sin\phi \, dho \, d\phi \, d	heta) = ho^3 \sin^2\phi \, dho \, d\phi \, d	heta$$

### 3. Z-Component Force Integral
$$F_z = \iiint rac{G m_0 z}{ho^3} \, dm = \int_0^{2\pi} \int_0^{\pi/2} \int_0^a rac{G m_0 (ho \cos\phi)}{ho^3} (ho^3 \sin^2\phi) \, dho \, d\phi \, d	heta$$
$$F_z = G m_0 \int_0^{2\pi} d	heta \int_0^{\pi/2} \cos\phi \sin^2\phi \, d\phi \int_0^a ho \, dho$$

### 4. Evaluation Steps
1. $ho$-integral: $\int_0^a ho \, dho = rac{a^2}{2}$
2. $\phi$-integral: $\int_0^{\pi/2} \sin^2\phi \cos\phi \, d\phi = \left[ rac{\sin^3\phi}{3} ight]_0^{\pi/2} = rac{1}{3}$
3. $	heta$-integral: $\int_0^{2\pi} d	heta = 2\pi$

- **Final Force Vector:**
  $$ec{F} = \left\langle 0, 0, rac{G m_0 a^2 \pi}{3} ightangle$$
