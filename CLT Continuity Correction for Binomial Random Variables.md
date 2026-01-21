If we wish to use normal approximation (via [[Central Limit Theorem|CLT]]) on a binomial random variable, we must perform the following:

| Binomial event | Normal approximation | How to remember                         |
| -------------- | -------------------- | --------------------------------------- |
| $P(X \leq k)$  | $P(Y \leq k + 0.5)$  | “Less than → include top half of k”     |
| $P(X < k)$     | $P(Y \leq k - 0.5)$  | “Strictly less → stop just before k”    |
| $P(X \geq k)$  | $P(Y \geq k - 0.5)$  | “Greater → start just below k”          |
| $P(X > k)$     | $P(Y \geq k + 0.5)$  | “Strictly greater → start just above k” |
