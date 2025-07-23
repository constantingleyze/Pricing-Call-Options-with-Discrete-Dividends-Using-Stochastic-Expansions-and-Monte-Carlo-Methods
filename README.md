# Pricing-Call-Options-with-Discrete-Dividends-Using-Stochastic-Expansions-and-Monte-Carlo-Methods

This notebook implements and compares three methods for pricing Call Options with discrete dividends, where the dividends are modeled as having both fixed and proportional components. The date for the dividends can be random, as well as the level of the dividends. 

- A Monte Carlo approach simulating the full underlying asset paths including discrete dividends,
- A Monte Carlo approach simulating only the underlying asset price at maturity with discrete dividends,
- Stochastic expansions of the Call option price with discrete dividends up to orders 1, 2, and 3.


For the first two methods, we also added an adaptative anthitetic variance reduction algorithm to improve the convergence. 

> **The specific stochastic expansions are from the following paper:**  
> Pierre Etoré, Emmanuel Gobet. Stochastic expansion for the pricing of call options with discrete
dividends. Applied Mathematical Finance, 2012, 19 (3), pp.233-264. ff10.1080/1350486X.2011.620397ff.
ffhal-00507787f

The proofs of all the results and theorems used in this notebook can be found in the paper above.

