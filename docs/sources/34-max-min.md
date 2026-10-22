# Max/Min

**Video URL**: https://www.youtube.com/watch?v=ImzS_gSbjK4  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Minimizing cardboard area $f(x,y)$ for open-top box with volume $V = xyz = 3$.

---

## 2. Key Formulas and Theorems

### Cost Function
$$z = \frac{3}{xy} \implies f(x,y) = 3xy + 2xz + 4yz = 3xy + \frac{6}{y} + \frac{12}{x}$$

### Critical Points ($f_x = 0, f_y = 0$)
$$f_x = 3y - \frac{12}{x^2} = 0 \implies y = \frac{4}{x^2}$$
$$f_y = 3x - \frac{6}{y^2} = 0 \implies 3x - \frac{6}{(4/x^2)^2} = 0 \implies x^3 = 8 \implies x = 2, y = 1$$

### Global Minimum Verification
As $x,y \to 0^+$ or $\infty$, $f(x,y) \to \infty$. Global min is at $(x,y,z) = (2,1,1.5)$ with $18$ sq units.
