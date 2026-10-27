
## Example

The number of traffic accidents occurring on any given day in Coralville is Poisson distributed with mean 5. The probability that any such accident involves an uninsured driver is 0.25, independent of all other such accidents.

Calculate the probability that on a given day in Coralville there are no traffic accidents that involve an uninsured driver.

### Solution
Let $X$ be the number of accidents that involve an uninsured driver. By Poisson thinning, $X \sim Poi(5\cdot0.25)$. Solving for $P(X=0)$, we get $P(X=0) = e^{-0.125}$
