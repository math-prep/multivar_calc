# Formulas and Theorems: Extended Green's Theorem

**Source Video:** *Extended Green's Theorem | MIT 18.02SC Multivariable Calculus, Fall 2010*

---

## 1. Problem Overview
The video solves a two-part problem for the radial vector field:
$$\vec{F} = r^n (x\,\hat{i} + y\,\hat{j}) = r^n \langle x, y \rangle$$
where $r = \sqrt{x^2 + y^2}$.
1. Use **Extended Green's Theorem** to prove $\vec{F}$ is conservative for all integers $n$.
2. Derive a **potential function** $f(x, y)$ such that $\nabla f = \vec{F}$.

---

## 2. Key Formulas & Theorems

### 1. Two-Dimensional Curl Formula
For a vector field $\vec{F} = [M, N]$:
$$\text{curl } \vec{F} = N_x - M_y$$
* **Application:** For $\vec{F} = [r^n x, r^n y]$:
  $$M_y = n r^{n-2} x y, \quad N_x = n r^{n-2} x y \implies N_x - M_y = 0$$
  Therefore, $\text{curl } \vec{F} = 0$ everywhere except possibly at $r = 0$.

### 2. Definition of a Conservative Vector Field
A vector field $\vec{F}$ is conservative if the line integral over every simple closed curve $C$ vanishes:
$$\oint_C \vec{F} \cdot d\vec{r} = 0$$

### 3. Standard Green's Theorem
For a simply connected region $R$ bounded by a simple closed curve $C$:
$$\oint_C \vec{F} \cdot d\vec{r} = \iint_R \text{curl } \vec{F} \, dA$$
* **Application:** For any closed curve $C_1$ that does **not** enclose the origin, $\vec{F}$ is differentiable inside $C_1$, so:
  $$\oint_{C_1} \vec{F} \cdot d\vec{r} = \iint_{R_1} 0 \, dA = 0$$

### 4. Extended Green's Theorem (Regions with Holes)
For a region $R$ lying between an outer curve $C_2$ (enclosing the origin) and an inner boundary curve $C_3$:
$$\iint_R \text{curl } \vec{F} \, dA = \oint_{C_3} \vec{F} \cdot d\vec{r} - \oint_{C_2} \vec{F} \cdot d\vec{r}$$
Since $\text{curl } \vec{F} = 0$ throughout $R$:
$$\oint_{C_2} \vec{F} \cdot d\vec{r} = \oint_{C_3} \vec{F} \cdot d\vec{r}$$

### 5. Orthogonality Property on Concentric Circle
Taking $C_3$ to be a circle centered at the origin:
- $\vec{F} = r^n \langle x, y \rangle$ points strictly in the radial direction.
- The unit tangent vector $\hat{T}$ to the circle $C_3$ is perpendicular to the radial vector.
- $\vec{F} \cdot \hat{T} = 0 \implies \oint_{C_3} \vec{F} \cdot d\vec{r} = 0$.
- By Extended Green's Theorem, $\oint_{C_2} \vec{F} \cdot d\vec{r} = 0$ for any curve $C_2$ enclosing the origin, establishing that $\vec{F}$ is conservative for all integers $n$.

---

## 3. Potential Function Integration Formulas

To find potential function $f(x_1, y_1)$ such that $\nabla f = \vec{F}$, integrate $P\,dx + Q\,dy$ along a path starting at $(1, 1)$ to avoid origin singularities:

$$f(x_1, y_1) = \int_{1}^{y_1} Q(1, y)\,dy + \int_{1}^{x_1} P(x, y_1)\,dx$$

### Case 1: $n \neq -2$
Using $u$-substitution $u = x^2 + y^2$:
$$f(x, y) = \frac{(x^2 + y^2)^{(n+2)/2}}{n+2} + C = \frac{r^{n+2}}{n+2} + C$$

### Case 2: $n = -2$
Integrating $\frac{1}{x^2 + y^2}$ yields a logarithmic antiderivative:
$$f(x, y) = \frac{1}{2} \ln(x^2 + y^2) + C = \ln r + C$$
