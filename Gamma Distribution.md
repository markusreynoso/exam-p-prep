Given $X  \sim Gamma(k, \lambda)$

$$
f(x) = \frac{\lambda^k}{\Gamma(k)}x^{k-1}e^{-\lambda x}, \quad x>0
$$
where $\Gamma(\cdot)$ is the [[Gamma Function]]

$E[X] = \frac{k}{\lambda}$
$V[X] = \frac{k}{\lambda^2}$

## Edge Cases
### Exponential
$k = 1 \implies X \sim Exp(\lambda)$

## Tricks
Given $X  \sim Gamma(k, \lambda)$

### Moments
$$
E[X^2] = \frac{k(k+1)}{\lambda^2}
$$
### For integer k

If $k \in \mathbb{N}$, then

>$$P(X > x) = e^{{-\lambda x}} \sum_{i=0}^{k-1} \frac{(\lambda x)^i}{i!}$$

For example, if $k = 2$, then

$$P(X > x) = e^{2\lambda}\left(1 + \frac{(\lambda x)^2}{2} \right)$$


### Poisson Connection

>$$P(X > x) = P\big(Poi(\lambda x) < k\big)$$


### Parameter recovery

>$$ \frac{E[X]}{V[X]} = \lambda $$

>$$k = \lambda E[X] = \lambda^2V[X]$$

### Reproductivity
Given $X_i \sim Gamma(k_i, \lambda)$, then 

>	$$\sum_{i=1}^{n}X_i \sim Gamma\left(\sum_{i=1}^nk_i, \lambda\right)$$