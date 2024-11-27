# **G-BO**

Implementation of Gaussian process regression based Bayesian optimisation (G-BO) using the emcee package (https://emcee.readthedocs.io/en/stable/).

For more information about the implementation of G-BO in optimising the Weather Research and Forecasting (WRF) model parameters, please refer to the paper - [Gaussian process regression-based Bayesian optimisation (G-BO) of model parameters - a WRF model case study of southeast Australia heat extremes](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024GL111074).

`G-BO_script.ipynb` implements the GPR based Bayesian optimisation using the Affine Invariant Markov chain Monte Carlo (MCMC) Ensemble sampler.

- **QMC_sobol_samples**: This file contains the 128 parameter samples across the parameter space of three sensitive parameters utilizing the Quasi Monte-Carlo (QMC) Sobol sequence design.
- **nmae_all_128_ens_T_Rh**: This file contains the normalised mean absolute error (NMAE) values of temperature (T) and relative humidity (Rh) of the 128 parameter sample WRF simulations. For more details, please refer to [this link](https://essopenarchive.org/doi/full/10.22541/essoar.171292045.52489731).

