# Non-Conservative Vector Fields

**Video URL**: https://www.youtube.com/watch?v=n9gSOBwauRw  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Showing $\vec{F} = \frac{-y \hat{i} + x \hat{j}}{x^2+y^2}$ is non-conservative despite zero curl.

---

## 2. Key Formulas and Theorems

### Zero Curl
$$\text{curl}(\vec{F}) = \frac{\partial N}{\partial x} - \frac{\partial M}{\partial y} = 0 \quad \text{for } (x,y) \neq (0,0)$$

### Domain Constraint
Zero curl implies conservative ONLY on simply connected domains (no holes/singularities). Origin $(0,0)$ is a puncture hole.

### Non-Zero Closed Line Integral Test
On unit circle $x=\cos\theta, y=\sin\theta$:
$$\oint_{\text{unit circle}} \vec{F} \cdot d\vec{r} = \int_0^{2\pi} d\theta = 2\pi \neq 0 \implies \vec{F} \text{ is non-conservative.}$$
