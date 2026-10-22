# Change of Variables (Linear Transformation)

**Video URL**: https://www.youtube.com/watch?v=G534bz09B4A  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Evaluating $\iint_R (4x^2 - y^2)^4 dx dy$ over a triangular region using linear substitution $u = 2x - y$ and $v = 2x + y$.

---

## 2. Key Formulas and Theorems

### Algebraic Simplification of Integrand
$$4x^2 - y^2 = (2x - y)(2x + y) = u \cdot v$$
$$(4x^2 - y^2)^4 = (uv)^4$$

### Jacobian Matrix and Scaling Factor
$$J = \begin{vmatrix} \frac{\partial u}{\partial x} & \frac{\partial u}{\partial y} \\ \frac{\partial v}{\partial x} & \frac{\partial v}{\partial y} \end{vmatrix} = \begin{vmatrix} 2 & -1 \\ 2 & 1 \end{vmatrix} = (2)(1) - (-1)(2) = 4$$
$$du dv = |J| dx dy = 4 dx dy \implies dx dy = \frac{du dv}{4}$$

### Area Scaling
$$\text{Area}(R_{uv}) = |J| \cdot \text{Area}(R_{xy}) = 4 \times \frac{1}{2} = 2$$

### Transformed Iterated Integral
$$\int_0^2 \int_{-v}^0 \frac{u^4 v^4}{4} du dv$$
