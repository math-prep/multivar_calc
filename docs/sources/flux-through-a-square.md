# Flux through a square

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Surface Element for a Graph $z = f(x,y)$
- **Upward Normal Surface Vector Element:**
  $$\hat{n} \, dS = \langle -f_x, \, -f_y, \, 1 angle \, dx \, dy$$

- **Given Surface $z = f(x,y) = x^2 + y$:**
  $$f_x = 2x, \quad f_y = 1 \implies \hat{n} \, dS = \langle -2x, \, -1, \, 1 angle \, dx \, dy$$

### 2. Vector Field Dot Product
- **Vector Field $ec{F} = \langle z, \, 0, \, x angle$:**
  $$ec{F} \cdot (\hat{n} \, dS) = ig( z(-2x) + 0(-1) + x(1) ig) \, dx \, dy = (-2xz + x) \, dx \, dy$$

- **Substitute $z = x^2 + y$:**
  $$ec{F} \cdot \hat{n} \, dS = ig( -2x(x^2 + y) + x ig) \, dx \, dy = (-2x^3 - 2xy + x) \, dx \, dy$$

### 3. Integration Over Unit Square $[0,1] 	imes [0,1]$
$$	ext{Flux} = \int_0^1 \int_0^1 (-2x^3 - 2xy + x) \, dy \, dx$$
1. Integration wrt $y$: $\int_0^1 (-2x^3 - 2xy + x) \, dy = -2x^3 - x + x = -2x^3$
2. Integration wrt $x$: $\int_0^1 -2x^3 \, dx = \left[ -rac{x^4}{2} ight]_0^1 = -rac{1}{2}$

- **Upward Flux Result:** $-rac{1}{2}$ (Downward flux is $+rac{1}{2}$)
