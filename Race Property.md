#Property
Similar to the [[Memoryless Property]], this only applies to the [[Geometric Distribution]] and the [[Exponential Distribution]] 
Given $X \sim Geo(p)$ and $Y \sim Geo(q)$

$$
P(X < Y) = \frac{p(1-q)}{p+q-pq} 
$$
On the other hand, if $X \sim Exp(p)$ and $Y \sim Exp(q)$, then simply

$$
P(X < Y) = \frac{p}{p+q}
$$
The latter is an application of the property of the [[Exponential Distribution#Minimum|minimum of exponential random variables]] wherein we are asking $P(\min(X, Y) = X)$.
