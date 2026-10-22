# Area of a Parallelogram

**Video URL**: https://www.youtube.com/watch?v=oET16XXfcCI  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Computing the area of a parallelogram in the 2D plane defined by four vertex points $P_1(1,1), P_2(7,2), P_3(6,3)$, and $P_4(12,4)$.

---

## 2. Key Formulas and Theorems

### Vector Differences from Base Point
Determinants are computed on edge vectors, not raw point coordinates:
$$\vec{v}_1 = P_2 - P_1 = \langle 7-1, 2-1 \rangle = \langle 6, 1 \rangle$$
$$\vec{v}_2 = P_3 - P_1 = \langle 6-1, 3-1 \rangle = \langle 5, 2 \rangle$$

### Area of a Parallelogram via 2D Determinant
$$\text{Area} = |\det(\vec{v}_1, \vec{v}_2)| = \left| \begin{matrix} v_{1x} & v_{1y} \\ v_{2x} & v_{2y} \end{matrix} \right| = |v_{1x}v_{2y} - v_{1y}v_{2x}|$$

### Specific Evaluation
$$\det = (6)(2) - (5)(1) = 12 - 5 = 7$$
$$\text{Area} = 7$$
