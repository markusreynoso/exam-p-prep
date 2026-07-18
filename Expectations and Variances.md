# Expectation
## Law of Total Expectation
This is similar to the [[Bayesian Statistics#^7bd8aa |Law of Total Probability]]

$$
E[X] = E[X \mid A_1]P(A_1) + E[X \mid A_2]P(A_2) + \cdots + E[X \mid A_n]P(A_n)
$$

# Variance

## Variance Sum

$$
V[X + Y] = V[X] + V[Y] + 2Cov(X, Y)
$$

## Variance Product
If $X$ and $Y$ are independent, then
$$
\begin{align*}
V[XY] &= E[X^2]E[Y^2] - E[X]^2E[Y]^2 \\
&\approx E[X]^2V[Y] + E[Y]^2V[X] \\
&= E[X]^2V[Y] + E[Y]^2V[X] + V[X]V[Y]
\end{align*}
$$
## Law of Total Variance
$$
V[X] = E[V[X \mid Y]] + V[E[X \mid Y]]$$
# Covariance
$$
Cov(X, Y) = E[XY] - E[X]E[Y]
$$