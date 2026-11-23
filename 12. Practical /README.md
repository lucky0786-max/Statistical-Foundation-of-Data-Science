# PRACTICAL 12 – Metropolis Algorithm and Bayesian Parameter Estimation

### Aim
To implement the Metropolis Algorithm for probability distribution sampling and use Bayesian estimation to estimate parameters of a logistic growth model.

### What I Did
1. Implemented the Metropolis Algorithm to generate samples from a bimodal Gaussian distribution.
2. Compared different proposal step sizes using acceptance rate and autocorrelation.
3. Plotted histograms, trace plots and autocorrelation graphs.
4. Calculated Effective Sample Size (ESS) and checked convergence using the Gelman-Rubin diagnostic.
5. Implemented a deterministic logistic growth model using `solve_ivp()`.
6. Generated noisy observations from the logistic growth model.
7. Used the Metropolis Algorithm to estimate the growth rate (r) and carrying capacity (K).
8. Compared actual and estimated parameters using graphs and posterior statistics.

### Conclusion
In this practical, I learned how the Metropolis Algorithm works and how it is used for sampling and Bayesian parameter estimation. I successfully estimated the logistic growth parameters close to their actual values using noisy data.
