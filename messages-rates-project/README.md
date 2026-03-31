# Bayesian Modeling of Message Rates

Estimate the average number of messages received per hour using **Bayesian Inference** with a Gamma–Poisson model.

* Prior: ( \lambda \sim \text{Gamma}(10, 2) )
* Data: 7, 3, 8, 9, 10, 12
* Posterior: ( \lambda \mid y \sim \text{Gamma}(59, 8) )

**Result:** posterior mean ≈ 7.37 messages/hour, with reduced uncertainty after observing data.

**Tools:** R, Quarto, `bayesrules`
