# Second Derivative Test

**Video URL**: https://www.youtube.com/watch?v=oQgHo7acids  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Classifying critical points of $w(x,y) = x^3 - 3xy + y^3$.

---

## 2. Key Formulas and Theorems

### Critical Points ($w_x = 0, w_y = 0$)
$$w_x = 3x^2 - 3y = 0 \implies y = x^2$$
$$w_y = -3x + 3y^2 = 0 \implies -3x + 3x^4 = 0 \implies x(x^3 - 1) = 0 \implies (0,0) \text{ and } (1,1)$$

### Second Derivative Test Discriminant $D$
$$D = w_{xx} w_{yy} - (w_{xy})^2 = (6x)(6y) - (-3)^2 = 36xy - 9$$
- At $(0,0)$: $D = -9 < 0 \implies \textbf{Saddle Point}$.
- At $(1,1)$: $D = 27 > 0, w_{xx} = 6 > 0 \implies \textbf{Local Minimum}$.
