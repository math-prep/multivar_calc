# Flux through surfaces

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### Problem 1: Cylinder $x^2 + y^2 = a^2$ in 1st Octant ($0 \le z \le h, 0 \le 	heta \le \pi/2$)
- **Vector Field:** $ec{F} = \langle z, x, y angle$
- **Normal Vector & Surface Element:**
  $$\hat{n} = rac{\langle x, y, 0 angle}{a}, \quad dS = a \, d	heta \, dz$$
- **Integrand $ec{F} \cdot \hat{n}$:**
  $$ec{F} \cdot \hat{n} = rac{xz + xy}{a} = z \cos	heta + a \cos	heta \sin	heta$$
- **Flux Integral:**
  $$	ext{Flux} = \int_0^h \int_0^{\pi/2} (z \cos	heta + a \cos	heta \sin	heta) a \, d	heta \, dz = rac{a h^2}{2} + rac{a^2 h}{2}$$

---

### Problem 2: Sphere $x^2 + y^2 + z^2 = a^2$ in 1st Octant
- **Vector Field:** $ec{F} = \langle xz, yz, z^2 angle$
- **Normal Vector:**
  $$\hat{n} = rac{\langle x, y, z angle}{a}$$
- **Integrand $ec{F} \cdot \hat{n}$:**
  $$ec{F} \cdot \hat{n} = rac{x^2 z + y^2 z + z^3}{a} = rac{(x^2 + y^2 + z^2) z}{a} = rac{a^2 z}{a} = a z = a^2 \cos\phi$$
- **Spherical Surface Element:** $dS = a^2 \sin\phi \, d	heta \, d\phi$
- **Flux Integral:**
  $$	ext{Flux} = \int_0^{\pi/2} \int_0^{\pi/2} (a^2 \cos\phi) (a^2 \sin\phi) \, d	heta \, d\phi = rac{\pi a^4}{4}$$
