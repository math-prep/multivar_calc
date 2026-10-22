# Total Differentials and the Chain Rule

**Video URL**: https://www.youtube.com/watch?v=2bF6H_xu0ao  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Computing $\frac{\partial z}{\partial u}$ for $z = x^2 + y^2$ with $x = u^2 - v^2, y = uv$.

---

## 2. Key Formulas and Theorems

### Multivariable Chain Rule
$$\frac{\partial z}{\partial u} = \frac{\partial z}{\partial x} \frac{\partial x}{\partial u} + \frac{\partial z}{\partial y} \frac{\partial y}{\partial u} = (2x)(2u) + (2y)(v) = 4xu + 2vy$$

### Total Differential Substitution
$$dz = 2x dx + 2y dy = 2x(2u du - 2v dv) + 2y(v du + u dv) = (4xu + 2vy) du + (2yu - 4xv) dv$$
Coeff of $du$ is $\frac{\partial z}{\partial u} = 4xu + 2vy$.
