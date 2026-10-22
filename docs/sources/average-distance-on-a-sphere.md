# Average distance on a sphere

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Geometry and Coordinate Transformations
- **Sphere Equation:**
  $$x^2 + y^2 + (z - 1)^2 = 1$$
  Centered at $(0, 0, 1)$ with radius $R = 1$.
  
- **Spherical Coordinate Conversions:**
  $$x = ho \sin\phi \cos	heta, \quad y = ho \sin\phi \sin	heta, \quad z = ho \cos\phi$$
  $$r^2 = x^2 + y^2 = ho^2 \sin^2\phi$$
  $$dV = ho^2 \sin\phi \, dho \, d	heta \, d\phi$$

### 2. Region Boundaries in Spherical Coordinates
- **Outer Boundary (Sphere Surface):**
  $$ho = 2 \cos\phi$$
- **Inner Boundary (Plane $z = 1$):**
  $$ho = \sec\phi$$
- **Variable Bounds for Region $D$:**
  $$0 \le 	heta \le 2\pi, \quad 0 \le \phi \le rac{\pi}{4}, \quad \sec\phi \le ho \le 2\cos\phi$$

### 3. Average Value Formula
- **General Average Value of $f$ over Solid $D$:**
  $$ar{f} = rac{1}{	ext{Volume}(D)} \iiint_D f(ho, 	heta, \phi) \, dV$$
  
- **Distance Function from Origin:**
  $$f(x, y, z) = ho$$

- **Volume of Upper Hemisphere ($R = 1$):**
  $$	ext{Volume}(D) = rac{1}{2} \left( rac{4}{3}\pi (1)^3 ight) = rac{2}{3}\pi$$

- **Final Integral Setup:**
  $$ar{ho} = rac{1}{rac{2}{3}\pi} \int_0^{\pi/4} \int_0^{2\pi} \int_{\sec\phi}^{2\cos\phi} ho^3 \sin\phi \, dho \, d	heta \, d\phi$$
