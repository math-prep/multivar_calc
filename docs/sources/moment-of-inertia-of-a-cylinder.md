# Moment of inertia of a cylinder

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Definition of Moment of Inertia
$$I_z = \iiint_D r^2 \delta \, dV$$
where $r$ is the distance to the central z-axis, and density $\delta = 1$.

### 2. Cylindrical Coordinate System Setup
- **Volume Element:** $dV = r \, dz \, dr \, d	heta$
- **Cylinder Bounds:** $0 \le z \le h, \quad 0 \le r \le b, \quad 0 \le 	heta \le 2\pi$
- **Integral:**
  $$I_z = \int_0^{2\pi} \int_0^b \int_0^h r^2 \cdot (r \, dz \, dr \, d	heta) = \int_0^{2\pi} \int_0^b \int_0^h r^3 \, dz \, dr \, d	heta$$

### 3. Evaluation Steps
1. $z$-integral: $\int_0^h r^3 \, dz = h r^3$
2. $r$-integral: $\int_0^b h r^3 \, dr = rac{h b^4}{4}$
3. $	heta$-integral: $\int_0^{2\pi} rac{h b^4}{4} \, d	heta = rac{\pi h b^4}{2}$

### 4. Expressed in Terms of Mass
- Mass of cylinder $M = 	ext{Volume} 	imes \delta = \pi b^2 h$:
  $$I_z = rac{1}{2} M b^2$$
