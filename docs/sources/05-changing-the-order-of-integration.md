# Changing the Order of Integration

**Video URL**: https://www.youtube.com/watch?v=p06QDsAPY4g  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Evaluating $\int_0^{1/4} \int_{\sqrt{t}}^{1/2} \frac{e^u}{u} du dt$ by reversing the order of integration.

---

## 2. Key Formulas and Theorems

### Fubini's Theorem (Swapping Limits)
Original region: $0 \le t \le 1/4$ and $\sqrt{t} \le u \le 1/2$.
Reversed limits: $0 \le u \le 1/2$ and $0 \le t \le u^2$.
$$\int_0^{1/4} \int_{\sqrt{t}}^{1/2} \frac{e^u}{u} du dt = \int_0^{1/2} \int_0^{u^2} \frac{e^u}{u} dt du$$

### Inner Integration
$$\int_0^{u^2} dt = u^2 \implies \int_0^{1/2} \frac{e^u}{u} (u^2) du = \int_0^{1/2} u e^u du$$

### Integration by Parts
$$\int u e^u du = u e^u - \int e^u du = (u - 1)e^u + C$$

### Definite Evaluation
$$\left[ (u - 1)e^u \right]_0^{1/2} = \left( \frac{1}{2} - 1 \right) e^{1/2} - (0 - 1) e^0 = -\frac{\sqrt{e}}{2} + 1 = 1 - \frac{\sqrt{e}}{2}$$
