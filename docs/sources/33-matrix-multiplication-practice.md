# Matrix Multiplication Practice

**Video URL**: https://www.youtube.com/watch?v=P6fOgkC5kvc  
**Course**: MIT 18.02SC Multivariable Calculus, Fall 2010

---

## 1. Problem Overview
Matrix multiplication compatibility and computation for $A_{2 \times 2}, B_{2 \times 3}, C_{3 \times 2}$.

---

## 2. Key Formulas and Theorems

### Dimension Compatibility Condition
$A_{m \times n} \cdot B_{p \times q}$ is defined $\iff n = p$. Result dimension is $m \times q$.

### Entry Formula
$$(AB)_{ij} = \sum_k A_{ik} B_{kj}$$

### Results
- $A_{2\times 2} B_{2\times 3} \implies \text{Defined } (2\times 3)$
- $B_{2\times 3} A_{2\times 2} \implies \text{Undefined } (3 \neq 2)$
- $B_{2\times 3} C_{3\times 2} \implies \text{Defined } (2\times 2)$
- $A_{2\times 2} C_{3\times 2} \implies \text{Undefined } (2 \neq 3)$
