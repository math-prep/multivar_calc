# Gradients - Composition

**Video URL**: https://www.youtube.com/watch?v=j9GZjr05Heg  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Constrained gradient $\nabla g(1,1)$ of $g(x,z) = f(x,y(x,z),z)$ with constraint $z = x^2 + y + 1$.

---

## 2. Key Formulas and Theorems

### Total Differentials Method
$$df = 2dx + dy - 3dz, \quad dz = 2xdx + dy \implies dy = dz - 2dx$$
$$df = 2dx + (dz - 2dx) - 3dz = -2dz \implies \nabla g(1,1) = \langle 0, -2 \rangle$$
