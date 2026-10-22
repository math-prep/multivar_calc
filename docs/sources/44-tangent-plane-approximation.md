# Tangent Plane Approximation

**Video URL**: https://www.youtube.com/watch?v=idNIKTaBEaI  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Approximating area $A(x,y) = xy$ near $(2,3)$ for $x=2.1, y=2.8$.

---

## 2. Key Formulas and Theorems

### Linearization / Tangent Plane Formula
$$A(x,y) \approx A(x_0,y_0) + A_x(x_0,y_0)(x - x_0) + A_y(x_0,y_0)(y - y_0)$$
$$A(2,3) = 6, \quad A_x(2,3) = 3, \quad A_y(2,3) = 2$$
$$A(2.1, 2.8) \approx 6 + 3(0.1) + 2(-0.2) = 6 + 0.3 - 0.4 = 5.9$$

### Sensitivity Analysis
$A_x = 3 > A_y = 2 \implies$ Changes in $x$ have greater effect than equal changes in $y$.
