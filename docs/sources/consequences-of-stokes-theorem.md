# Consequences of Stokes' Theorem

**Source:** MIT 18.02SC Multivariable Calculus, Fall 2010

---

## Key Formulas and Theorems

### 1. Vector Field and Definitions
- **Radial Vector Field:**
  $$ec{F} = \langle x, y, z angle$$

### 2. Stokes' Theorem
- **Classical Statement:**
  $$\oint_C ec{G} \cdot dec{r} = \iint_S (
abla 	imes ec{G}) \cdot \hat{n} \, dS$$

### 3. Proof by Contradiction Method
- **Premise:** Assume $ec{F} = 
abla 	imes ec{G}$ for some field $ec{G}$.
- **Closed Curve $C$ on Sphere of Radius $b$:**
  - $C$ divides sphere into upper cap $S_1$ and lower cap $S_2$.
  - For $S_1$ (outward normal $\hat{n}$):
    $$\oint_C ec{G} \cdot dec{r} = \iint_{S_1} (
abla 	imes ec{G}) \cdot \hat{n} \, dS = \iint_{S_1} ec{F} \cdot \hat{n} \, dS$$
    Since $ec{F} \cdot \hat{n} = b$:
    $$\oint_C ec{G} \cdot dec{r} = b \cdot 	ext{Area}(S_1) > 0$$

  - For $S_2$ (with boundary $-C$ for outward normal $\hat{n}$):
    $$-\oint_C ec{G} \cdot dec{r} = \iint_{S_2} (
abla 	imes ec{G}) \cdot \hat{n} \, dS = \iint_{S_2} ec{F} \cdot \hat{n} \, dS = b \cdot 	ext{Area}(S_2) > 0$$

- **Contradiction:** The line integral $\oint_C ec{G} \cdot dec{r}$ cannot be both positive and negative. Thus, $ec{F} = \langle x, y, z angle$ is **not** the curl of any vector field $ec{G}$.
