# Tangent Planes

**Video URL**: https://www.youtube.com/watch?v=6paZkmBMZwQ  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
1. Tangent plane to $z = x^3 + 3xy^2$ at $(1,2,13)$.
2. Tangent line to $x^3 + 2xy + y^2 = 9$ at $(1,2)$.

---

## 2. Key Formulas and Theorems

### Level Surface Gradient Normal
$$w(x,y,z) = x^3 + 3xy^2 - z = 0 \implies \vec{N} = \nabla w = \langle 3x^2 + 3y^2, 6xy, -1 \rangle$$
At $(1,2,13)$: $\vec{N} = \langle 15, 12, -1 \rangle$
$$15(x - 1) + 12(y - 2) - 1(z - 13) = 0$$

### 2D Level Curve Tangent Line
$$\nabla f(1,2) = \langle 3x^2 + 2y, 2x + 2y \rangle|_{(1,2)} = \langle 7, 6 \rangle$$
$$7(x - 1) + 6(y - 2) = 0$$
