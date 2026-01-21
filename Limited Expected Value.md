#Trick
The expected payout for a loss with a deductible $d$ capped at $u$. The insurer pays the portion of the loss exceeding $d$ but only up to $u$.
$$
E[\min(\max(L-d, 0), u)] = \int_d^{d+u}P(L>t)dt
$$
