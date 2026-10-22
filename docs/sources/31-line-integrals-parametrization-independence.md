# Line Integrals: Parametrization Independence

**Video URL**: https://www.youtube.com/watch?v=tkAgpKg-tPs  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Evaluating $\int_C \vec{F} \cdot d\vec{r}$ for $\vec{F} = \langle xy, x^2+y^2 \rangle$ along parabola $y=x^2$ from $(1,1)$ to $(2,4)$ using two different parametrizations:
1. $x=t, y=t^2, t \in [1,2]$
2. $x=e^t, y=e^{2t}, t \in [0, \ln 2]$

---

## 2. Key Formulas and Theorems

### Line Integral Definition
$$\int_C \vec{F} \cdot d\vec{r} = \int_C (M dx + N dy)$$

### Parametrization 1 Evaluation
$$\int_1^2 (t \cdot t^2 dt + (t^2 + t^4)(2t dt)) = \int_1^2 (3t^3 + 2t^5) dt = \left[ \frac{3t^4}{4} + \frac{t^6}{3} \right]_1^2 = \frac{129}{4}$$

### Parametrization 2 Evaluation
$$\int_0^{\ln 2} (3e^{4t} + 2e^{6t}) dt = \left[ \frac{3e^{4t}}{4} + \frac{e^{6t}}{3} \right]_0^{\ln 2} = \frac{129}{4}$$

### Invariance Theorem
Line integral value depend only on oriented path $C$, completely independent of parametrization.
