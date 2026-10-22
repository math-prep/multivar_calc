# Change of Variables (Unbounded Region)

**Video URL**: https://www.youtube.com/watch?v=lCKxeRiBdjQ  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Setting up limits and integrand for $\iint_R \frac{1}{x^2} dx dy$ using $u = x^2 - y^2$ and $v = y/x$.

---

## 2. Key Formulas and Theorems

### Change of Variables Formula
$$\iint_R f(x,y) dx dy = \iint_{R_{uv}} f(x(u,v), y(u,v)) \left| \frac{\partial(x,y)}{\partial(u,v)} \right| du dv$$

### Jacobian Determinant Calculation
$$\frac{\partial(u,v)}{\partial(x,y)} = \begin{vmatrix} \frac{\partial u}{\partial x} & \frac{\partial u}{\partial y} \\ \frac{\partial v}{\partial x} & \frac{\partial v}{\partial y} \end{vmatrix} = \begin{vmatrix} 2x & -2y \\ -\frac{y}{x^2} & \frac{1}{x} \end{vmatrix} = 2 - \frac{2y^2}{x^2} = 2(1 - v^2)$$

### Inverse Jacobian Relation
$$\frac{\partial(x,y)}{\partial(u,v)} = \frac{1}{\frac{\partial(u,v)}{\partial(x,y)}} = \frac{1}{2(1 - v^2)}$$

### Integrand Transformation
Since $u = x^2 - y^2 \implies \frac{u}{x^2} = 1 - \frac{y^2}{x^2} = 1 - v^2$:
$$dx dy = \frac{du dv}{2(1 - v^2)} = \frac{du dv}{2 \left(\frac{u}{x^2}\right)} \implies \frac{dx dy}{x^2} = \frac{du dv}{2u}$$

### Integration Bounds
- $u$ ranges from $1$ to $\frac{1}{v} - v$
- $v$ ranges from $0$ to $a = \frac{-1 + \sqrt{5}}{2}$
- Final integral: $\int_0^a \int_1^{\frac{1}{v}-v} \frac{1}{2u} du dv$
