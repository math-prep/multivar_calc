# Determinants

**Video URL**: https://www.youtube.com/watch?v=PxkEoEbCJT8  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Computing determinants for $2 \times 2$ and $3 \times 3$ matrices using diagonal expansion and Laplace cofactor expansion.

---

## 2. Key Formulas and Theorems

### $2 \times 2$ Determinant
$$\begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$$

### $3 \times 3$ Laplace Expansion
$$\det(A) = \sum_{j=1}^3 a_{ij} C_{ij} = \sum_{j=1}^3 a_{ij} (-1)^{i+j} M_{ij}$$

### Evaluation Example
$$\det\begin{pmatrix} -1 & 0 & 4 \\ 1 & 2 & 2 \\ 3 & -2 & 1 \end{pmatrix} = -1(2+4) - 0 + 4(-2-6) = -6 - 32 = -38$$
