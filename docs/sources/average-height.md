# Average height

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Average Value of a Function in 3D
- **Average Value Formula:**
  $$ar{f} = rac{1}{	ext{Volume}(R)} \iiint_R f(x, y, z) \, dV$$

### 2. Surface and Height Equations
- **Height Function (Distance to xy-plane):**
  $$f(x, y, z) = z$$

- **Plane through Vertices $(1,0,0)$, $(0,1,0)$, and $(0,0,1)$:**
  $$x + y + z = 1 \implies z = 1 - x - y$$

### 3. Triple Integral Integration and Evaluation
- **Iterated Integral Setup:**
  $$\iiint_R z \, dz \, dy \, dx = \int_0^1 \int_0^{1-x} \int_0^{1-x-y} z \, dz \, dy \, dx$$
  
- **Evaluation Steps:**
  1. Innermost ($z$): $\int_0^{1-x-y} z \, dz = rac{(1-x-y)^2}{2}$
  2. Middle ($y$): $\int_0^{1-x} rac{(1-x-y)^2}{2} \, dy = rac{(1-x)^3}{6}$
  3. Outermost ($x$): $\int_0^1 rac{(1-x)^3}{6} \, dx = rac{1}{24}$

### 4. Tetrahedron Volume and Average Height
- **Volume of Tetrahedron:**
  $$	ext{Volume} = rac{1}{3} 	imes 	ext{Base Area} 	imes 	ext{Height} = rac{1}{3} \left(rac{1}{2}ight) (1) = rac{1}{6}$$

- **Average Height Result:**
  $$ar{z} = rac{rac{1}{24}}{rac{1}{6}} = rac{1}{4}$$
