# Line Integrals: Path Dependence

**Video URL**: https://www.youtube.com/watch?v=gBuIwfdoOn0  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Evaluating $\int_C \vec{F} \cdot d\vec{r}$ along straight line vs piecewise rectangular path connecting $(1,1)$ to $(2,4)$.

---

## 2. Key Formulas and Theorems

### Straight Line Path $C_a$
$$y = 3x - 2, \quad x \in [1,2] \implies \int_{C_a} \vec{F} \cdot d\vec{r} = 32$$

### Piecewise Path $C_b = C_1 + C_2$
- $C_1$: $(1,1) \to (1,4) \implies \int_{C_1} = 24$
- $C_2$: $(1,4) \to (2,4) \implies \int_{C_2} = 6$
- Total: $24 + 6 = 30$

### Path Dependence Principle
$32 \neq 30 \implies \vec{F}$ is **non-conservative** ($M_y = x \neq N_x = 2x$).
