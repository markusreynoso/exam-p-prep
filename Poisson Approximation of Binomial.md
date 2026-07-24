
>If $X \sim Bin(n,p)$, then $X \approx Poi(\lambda=np)$

This is useful because for large values of $n$ and small values of $p$, it is easier to use the [[Poisson Distribution|Poisson pdf]] than the [[Binomial Distribution|binomial pdf]]

Example:

*An insurance company has found that 1% of all applicants for life insurance have diabetes. Calculate the probability that five or fewer of 200 randomly selected applicants have diabetes.*

The problem essentially asks for the probability of at most $5$ successes in $200$ attempts with a $1\%$ probability of success. In this scenario, it is relatively more expensive to compute

$$
\sum_{x=0}^5 {200\choose x}(0.01)^x(0.99)^{200-x}
$$
than

$$
\sum_{x=0}^5 \frac{e^{-2}2^x}{x!}
$$
