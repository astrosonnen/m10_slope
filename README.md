# A robust two-dimensional description of massive elliptical galaxies

This repository contains the main code used for the inference of the distribution in age, stellar velocity dispersion and halo mass as a function of $M_{*,10}$ and $\Gamma_{*,10}$, as well as the MCMC chains describing the posterior probability distribution of the model.

## Chains

The MCMC chains drawn from the posterior probability distribution of the various models can be found in `.hdf5` format in the `chains/` directory.

### Requirements ###

- Python 2
- emcee
- [This](https://github.com/astrosonnen/bayesian_hierarchical_wl) package for the calculation of the likelihood of the weak lensing measurements

