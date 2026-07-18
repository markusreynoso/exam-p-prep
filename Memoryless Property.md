#Property

If you've already been waiting for $s$ long and you're wondering what is the probability that it will take another $t$ long, then that is the same probability as if you had just started waiting.

$$
P(X > s + t \mid X > s) = P(X >t)
$$
# Derivation
By definition of the conditional expectation
$$
\begin{align*}
P(X > s+t \mid X > s) 
&= \frac{P(X > s+t \;\;\cap\;\; X > s)}{P(X >s)} \\
&= \frac{P(X > s+t)}{P(X>s)} \\
&= \frac{e^{-(s+t)x}}{e^{-(s)x}} \\
&= e^{-tx} \\
&= P(X > t)
\end{align*}
$$

# Consequences
## 1
Let $X$ denote the lifetime of an object which is modeled by the exponential distribution with parameter $\lambda$. Let $s$ be the unit of time that has already elapsed. Finally, let $R = X - s$ be the remaining lifetime of the object. It follows that

$$
R \sim Exp(\lambda)
$$
### Proof
$$
\begin{align*}
P(R > r) 
&= P(X - s > r \mid X > s) \\
&= P(X > r +s  \mid X > s) \\
&= P(X>r) \;\;\text{from the argument above}
\end{align*} 
$$
and clearly, $R \sim Exp(\lambda) \;\;\blacksquare{}$.


One application would be for deductibles. If $X \sim Exp(\lambda)$, it follows that the expected payout given that the loss exceeds the deductible is

>$$
E[X - d \mid X > d] = E[X]
$$

By letting $R = X-d$, and remembering that $R \sim Exp(\lambda)$, we get

$$
\begin{align*}
E[X - d \mid X > d] &= E[R \mid R > 0] \\
&= E[R] \\
&= E[X]
\end{align*}
$$
