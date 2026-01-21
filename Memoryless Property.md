#Property

> If you've already been waiting for $s$ long and you're wondering what is the probability that it will take another $t$ long, then that is the same probability as if you had just started waiting.

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

