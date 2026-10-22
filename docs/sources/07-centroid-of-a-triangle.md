# Coordinate Free Proofs: Centroid of a Triangle

**Video URL**: https://www.youtube.com/watch?v=AYixF5nY3Vc  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Proving using coordinate-free vector algebra that the three medians of a triangle intersect at a single point (centroid) that divides each median in a $2:1$ ratio.

---

## 2. Key Formulas and Theorems

### Midpoint Position Vector
$$\vec{OM} = \frac{1}{2}(\vec{OB} + \vec{OC})$$

### Point Trisecting a Median
$$\vec{OP} = \vec{OA} + \frac{2}{3}\vec{AM} = \vec{OA} + \frac{2}{3}(\vec{OM} - \vec{OA}) = \frac{1}{3}\vec{OA} + \frac{2}{3}\vec{OM} = \frac{1}{3}(\vec{OA} + \vec{OB} + \vec{OC})$$

### Centroid Symmetry
Since $\vec{OP} = \frac{1}{3}(\vec{OA} + \vec{OB} + \vec{OC})$ is symmetric in $A, B, C$, all three medians intersect at $P$.
