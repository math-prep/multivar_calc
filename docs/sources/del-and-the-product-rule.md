# Del and the product rule

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Vector Identity (Product Rule for Divergence)
$$
abla \cdot (u ec{F}) = (
abla u) \cdot ec{F} + u (
abla \cdot ec{F})$$
where $u(x,y,z)$ is a scalar function and $ec{F} = \langle P, Q, R angle$ is a vector field.

### 2. Proof Derivation Steps
- **Component Form:**
  $$u ec{F} = \langle uP, uQ, uR angle$$

- **Divergence Definition:**
  $$
abla \cdot (u ec{F}) = rac{\partial(uP)}{\partial x} + rac{\partial(uQ)}{\partial y} + rac{\partial(uR)}{\partial z}$$

- **Applying Scalar Product Rule:**
  $$rac{\partial(uP)}{\partial x} = u_x P + u P_x$$
  $$rac{\partial(uQ)}{\partial y} = u_y Q + u Q_y$$
  $$rac{\partial(uR)}{\partial z} = u_z R + u R_z$$

- **Regrouping Terms:**
  $$
abla \cdot (u ec{F}) = (u_x P + u_y Q + u_z R) + u (P_x + Q_y + R_z)$$
  $$
abla \cdot (u ec{F}) = \langle u_x, u_y, u_z angle \cdot \langle P, Q, R angle + u (
abla \cdot ec{F})$$
  $$
abla \cdot (u ec{F}) = (
abla u) \cdot ec{F} + u (
abla \cdot ec{F})$$
