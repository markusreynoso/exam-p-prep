#Distribution 
Given $X \sim Exp(\lambda)$, the pdf is

$$
f(x) = \lambda e^{\lambda x}, \quad x>0
$$
with

$E[X]  = \frac{1}{\lambda}$
$V[X] = \frac{1}{\lambda^2}$
Median = $\frac{\ln2}{\lambda}$

The exponential distribution is a special case of the [[Gamma Distribution]], that is, if 
## CDF
$$
P(X \leq k) = 1-e^{-\lambda k}
$$
## Survival function
$$P(X \geq k) = e^{-\lambda k}$$
## Two-sided

$$
P(a \leq X \leq b) = e^{-\lambda a} - e^{-\lambda b}
$$
## Tricks

### Moments
>$$ E[X^n] = \frac{n!}{\lambda^n}$$

### Truncated exponential formula
Given $X \sim Exp(\lambda)$

>$$E[X \mid X < t] = \frac{1}{\lambda} - \frac{te^{-\lambda t}}{1-e^{-\lambda t}}$$

### Expected payment net of a deductible
Given $X \sim Exp(\lambda)$

>$$E[\max(X - d, 0)] = \frac{1}{\lambda} e^{-\lambda d}$$

This gives us the expected payout net of a deductible. Generally speaking,

>$$E[\max(X-d, 0)^n] = e^{-\lambda d}\frac{n!}{\lambda^n}$$

Meanwhile [[Memoryless Property|the expected payout given that the loss already exceeds the deductible is simply:]]
 >$$ E[X - d \mid X > d] = E[X] = \frac{1}{\lambda} $$
because the excess also behaves like a fresh exponential. 

### Conditional expectation and variance ($\geq$)
>$$\begin{align}E[X \mid X \geq k] &= k \; + \; E[X] \\V[X \mid X \geq k] &= V[X]\end{align}$$

### Minimum
Given $X_{1} \sim Exp(\lambda_{1}), \; \ldots \; , X_n \sim Exp(\lambda_n)$, then

>$$\min(X_1, \ldots, X_n) \sim Exp(\lambda_1 + \cdots + \lambda_n)$$

### Limited Deductible Subject Expected Value
This is an applied case of the [[Limited Deductible Subject Expected Value]] trick.
>$$E[\min(\max(X-d, 0), u)] = \frac{1}{\lambda}(e^{-\lambda d} - e^{-\lambda u-\lambda d})$$

### Memoryless Property
[[Memoryless Property]]

### Race Property
[[Race Property]]
