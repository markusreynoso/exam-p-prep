The means, medians, and modes of the different [[Discrete Distributions|discrete distributions]].

| Distribution           | Mean                          | Median                                                                            | Mode                                                |
| ---------------------- | ----------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------- |
| $Ber(p)$               | $p$                           | $0$ if $p<0.5$, $0$ and $1$ if $p=0.5$, $1$ if $p>0.5$                            | same as median                                      |
| $Bin(n, p)$            | $np$                          | no general formula (≈ $\lfloor np \rfloor$ or $\lceil np \rceil$)                 | $\lfloor (n+1)p \rfloor$                            |
| $Geo(p)$               | $\frac{1}{p}$                 | $\left\lceil \frac{\ln 0.5}{\ln (1-p)} \right\rceil$                              | $1$                                                 |
| $Poi(\lambda)$         | $\lambda$                     | no closed form (≈ $\lfloor \lambda + \frac{1}{3} - \frac{0.02}{\lambda} \rfloor$) | $\lfloor \lambda \rfloor$                           |
| $U(a, b)$              | $\frac{a+b}{2}$               | $\frac{a+b}{2}$                                                                   | any value in $[a, b]$                               |
| $Exp(\lambda)$         | $\frac{1}{\lambda}$           | $\frac{\ln 2}{\lambda}$                                                           | $0$                                                 |
| $N(\mu, \sigma^2)$     | $\mu$                         | $\mu$                                                                             | $\mu$                                               |
| $Gamma(\alpha, \beta)$ | $\alpha \beta$                | no general closed form                                                            | $(\alpha-1)\beta$, $\alpha \ge 1$                   |
| $Beta(\alpha, \beta)$  | $\frac{\alpha}{\alpha+\beta}$ | no general closed form                                                            | $\frac{\alpha-1}{\alpha+\beta-2}$, $\alpha,\beta>1$ |
