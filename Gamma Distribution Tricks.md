#Trick


---

### 5. Recover Parameters (very common)

Given mean $$ m $$ and variance $$ v $$:

$$
\theta = \frac{v}{m}, \quad \alpha = \frac{m}{\theta}
$$

---

### 6. Sums of Gammas

If independent and same $$ \theta $$:

$$
X_1 \sim \text{Gamma}(\alpha_1, \theta), \quad
X_2 \sim \text{Gamma}(\alpha_2, \theta)
$$

$$
X_1 + X_2 \sim \text{Gamma}(\alpha_1 + \alpha_2, \theta)
$$

---

### 7. Expectation Identities

$$
E[X] = \alpha \theta
$$

$$
E[X^2] = \alpha(\alpha + 1)\theta^2
$$

---

### 8. What They Usually Test

- Recover $$ \alpha, \theta $$ from mean/variance  
- Recognize integer $$ \alpha $$ → use survival shortcut  
- Compute $$ P(X > x) $$ without tables  
- Use sum of Gammas  
- Occasionally use Poisson connection  

---

### 9. Minimal Exam Workflow

1. Solve for $$ \alpha, \theta $$  
2. Check if $$ \alpha $$ is a small integer  
3. If yes → use shortcut formula  
4. Avoid integrals unless absolutely necessary