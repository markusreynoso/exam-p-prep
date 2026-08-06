The geometric distribution is either one of two discrete probability distributions

The first one (sometimes called the *shifted geometric distribution*) is the distribution of the number of [[Bernoulli Distribution|Bernoulli trials]] before the first success, with probability mass function

$$
P(X=x) = (1-p)^{k-1}p, \quad x \in \{1,2,3,\ldots\}
$$
This formula can be read as the probability of the failure event occurring $k-1$ times consecutively followed by a success, constituting a total of $k$ trials. In this case, we have

$$
\begin{align*}
E[X] &= \frac{1}{p} \\
V[X] &= \frac{1-p}{p^2}
\end{align*}
$$

The second one models the number of failures before the first success, with probability mass function
$$
P(X=x) = (1-p)^{k}p, \quad x \in \{0,1,2,3,\ldots\}
$$
This formula is more straightforward wherein we ask the probability of the failure event occurring $k$ times consecutively. In this case, we have
$$
\begin{align*}
E[X] &= \frac{1-p}{p} \\
V[X] &= \frac{1-p}{p^2}
\end{align*}
$$
