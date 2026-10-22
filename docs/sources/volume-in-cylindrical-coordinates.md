# Formulas and Theorems: Volume in Cylindrical Coordinates

**Source Video:** *Volume in cylindrical coordinates | MIT 18.02SC Multivariable Calculus, Fall 2010*

---

## 1. Problem Overview
Compute the volume of the solid region bounded below by the paraboloid $z = x^2 + y^2$ and bounded above by the plane $z = 2y$.

---

## 2. Key Formulas & Definitions

### 1. Volume via Triple Integral
The volume $V$ of a 3D solid region $D$ is given by:
$$V = \iiint_D dV$$

---

### 2. Cylindrical Coordinate Transformations
Coordinate conversion equations:
$$x = r \cos\theta, \quad y = r \sin\theta, \quad z = z, \quad x^2 + y^2 = r^2$$

Differential volume element:
$$dV = r \, dz \, dr \, d\theta$$

---

### 3. Boundary Surface & Projection Formulas
1. **Paraboloid (Lower Bound):** $z = x^2 + y^2 \implies z = r^2$
2. **Plane (Upper Bound):** $z = 2y \implies z = 2r \sin\theta$
3. **Projection Curve in $xy$-Plane ($C$):** Intersecting surfaces gives:
   $$x^2 + y^2 = 2y \iff x^2 + (y - 1)^2 = 1$$
   *(Circle centered at $(0, 1)$ with radius $1$).*
4. **Polar Equation of Projection Curve:**
   $$r^2 = 2r \sin\theta \implies r = 2 \sin\theta \quad (\text{for } 0 \le \theta \le \pi)$$

---

## 3. Integral Setup & Integration Formulas

### Triple Integral Formulation
$$V = \int_{0}^{\pi} \int_{0}^{2\sin\theta} \int_{r^2}^{2r\sin\theta} r \, dz \, dr \, d\theta$$

### Step-by-Step Integration Formulas
1. **Inner Integral ($z$):**
   $$\int_{r^2}^{2r\sin\theta} r \, dz = r(2r\sin\theta - r^2) = 2r^2\sin\theta - r^3$$

2. **Middle Integral ($r$):**
   $$\int_{0}^{2\sin\theta} (2r^2\sin\theta - r^3) \, dr = \left[ \frac{2}{3}r^3\sin\theta - \frac{1}{4}r^4 \right]_{0}^{2\sin\theta} = \frac{4}{3} \sin^4\theta$$

3. **Outer Integral ($\theta$):**
   $$V = \frac{4}{3} \int_{0}^{\pi} \sin^4\theta \, d\theta$$

---

## 4. Trigonometric Reduction Identities Used

To integrate $\sin^4\theta$, double-angle / half-angle reduction identities are required:

1. **Half-Angle Identity for Sine:**
   $$\sin^2\theta = \frac{1 - \cos(2\theta)}{2}$$

2. **Double-Angle Identity for Cosine:**
   $$\cos^2(2\theta) = \frac{1 + \cos(4\theta)}{2}$$

### Final Evaluated Volume
$$V = \frac{\pi}{2}$$
