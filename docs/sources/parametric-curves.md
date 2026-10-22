# Formulas and Theorems: Parametric Curves

**Source Video:** *Parametric curves: velocity, acceleration, length | MIT 18.02SC Multivariable Calculus, Fall 2010*

---

## 1. Problem Overview
Given the position vector of a particle in 3D space:
$$\vec{r}(t) = \langle 1 - 2t^2, \; t^2, \; -2 + 2t^2 \rangle$$

The objectives are to compute:
1. Velocity vector $\vec{v}(t)$
2. Speed $|\vec{v}(t)|$
3. Acceleration vector $\vec{a}(t)$
4. Unit tangent vector $\hat{T}(t)$
5. Arc length $s$ of the trajectory from $t = 0$ to $t = 2$

---

## 2. Key Formulas & Definitions

### 1. Velocity Vector Formula
The velocity vector is the first derivative of the position vector with respect to time $t$:
$$\vec{v}(t) = \vec{r}'(t) = \left\langle \frac{dx}{dt}, \frac{dy}{dt}, \frac{dz}{dt} \right\rangle$$

* **Calculated Result:**
  $$\vec{v}(t) = \langle -4t, \; 2t, \; 4t \rangle$$

---

### 2. Speed (Magnitude of Velocity) Formula
Speed is the scalar norm/length of the velocity vector:
$$|\vec{v}(t)| = \sqrt{\vec{v}(t) \cdot \vec{v}(t)} = \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2 + \left(\frac{dz}{dt}\right)^2}$$

* **Calculated Result:**
  $$|\vec{v}(t)| = \sqrt{(-4t)^2 + (2t)^2 + (4t)^2} = \sqrt{16t^2 + 4t^2 + 16t^2} = \sqrt{36t^2} = 6t \quad (\text{for } t \ge 0)$$

---

### 3. Acceleration Vector Formula
The acceleration vector is the derivative of the velocity vector with respect to $t$:
$$\vec{a}(t) = \vec{v}'(t) = \vec{r}''(t) = \left\langle \frac{d^2x}{dt^2}, \frac{d^2y}{dt^2}, \frac{d^2z}{dt^2} \right\rangle$$

* **Calculated Result:**
  $$\vec{a}(t) = \langle -4, \; 2, \; 4 \rangle$$
  *(Note: Acceleration is constant in time).*

---

### 4. Unit Tangent Vector Formula
The unit tangent vector $\hat{T}(t)$ normalizes the velocity vector:
$$\hat{T}(t) = \frac{\vec{v}(t)}{|\vec{v}(t)|}$$

* **Calculated Result:**
  $$\hat{T}(t) = \frac{1}{6t} \langle -4t, 2t, 4t \rangle = \left\langle -\frac{2}{3}, \; \frac{1}{3}, \; \frac{2}{3} \right\rangle$$

---

### 5. Arc Length Formula
The arc length $s$ of a parametric curve over $t \in [t_1, t_2]$ is the integral of speed:
$$s = \int_{t_1}^{t_2} |\vec{v}(t)| \, dt = \int_{t_1}^{t_2} \frac{ds}{dt} \, dt$$

* **Calculated Result for $t \in [0, 2]$:**
  $$s = \int_{0}^{2} 6t \, dt = \left[ 3t^2 \right]_{0}^{2} = 3(2)^2 - 0 = 12 \text{ units}$$
