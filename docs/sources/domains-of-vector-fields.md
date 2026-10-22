# Formulas and Theorems: Domains of Vector Fields

**Source Video:** *Domains of vector fields | MIT 18.02SC Multivariable Calculus, Fall 2010*

---

## 1. Problem Overview
The core task is to analyze four vector fields $\vec{F}(x,y)$ in $\mathbb{R}^2$ to:
1. Determine the domain $D \subseteq \mathbb{R}^2$ where each vector field is both **defined** and **continuously differentiable**.
2. Determine whether that domain $D$ forms a **simply connected region**.

---

## 2. Key Definitions & Theorems

### Definition: Continuous Differentiability Conditions
- **Square Root Function ($\sqrt{u}$):**
  - Defined for $u \ge 0$.
  - Continuously differentiable for $u > 0$.
- **Reciprocal Square Root ($\frac{1}{\sqrt{u}}$):**
  - Defined and continuously differentiable for $u > 0$.
- **Natural Logarithm ($\ln(u)$):**
  - Defined and continuously differentiable for $u > 0$.

### Definition: Simply Connected Region
A region $D \subseteq \mathbb{R}^2$ is **simply connected** if for every simple closed curve $C$ lying entirely inside $D$, all points on the interior of $C$ also belong to $D$ (intuitively, the region has "no holes").

---

## 3. Analysis of Vector Fields

### Vector Field A: $\vec{F} = \sqrt{x}\,\hat{i} + \sqrt{y}\,\hat{j}$
* **Domain Condition:**
  $$x > 0 \quad \text{and} \quad y > 0$$
* **Region Geometry:** The open first quadrant of the $xy$-plane (excluding coordinate axes).
* **Simply Connected:** **Yes**. Any closed curve drawn in the open first quadrant encloses only points in the first quadrant.

### Vector Field B: $\vec{F} = \frac{\hat{i} + \hat{j}}{\sqrt{1 - x^2 - y^2}}$
* **Domain Condition:**
  $$1 - x^2 - y^2 > 0 \implies x^2 + y^2 < 1$$
* **Region Geometry:** The open interior of the unit circle centered at the origin.
* **Simply Connected:** **Yes**. The interior of a circle contains no holes, so any enclosed curve contains only interior points.

### Vector Field C: $\vec{F} = \frac{\hat{i} + \hat{j}}{\sqrt{x^2 + y^2 - 1}}$
* **Domain Condition:**
  $$x^2 + y^2 - 1 > 0 \implies x^2 + y^2 > 1$$
* **Region Geometry:** All points outside the unit circle.
* **Simply Connected:** **No**. A closed curve enclosing the unit disk (e.g., circle of radius 2) surrounds points in $x^2 + y^2 \le 1$ that do not belong to the domain.

### Vector Field D: $\vec{F} = (\hat{i} + \hat{j})\ln(x^2 + y^2)$
* **Domain Condition:**
  $$x^2 + y^2 > 0 \implies (x, y) \neq (0,0)$$
* **Region Geometry:** The entire plane $\mathbb{R}^2$ except the single point at the origin $(0,0)$.
* **Simply Connected:** **No**. Any closed curve surrounding the origin contains $(0,0)$ in its interior, which is excluded from the domain.
