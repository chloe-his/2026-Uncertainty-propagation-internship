Description
===========

This folder contains the sources of the report of the Master's degree internship of Chloé His on the topic

  "Uncertainty propagation effects in epidemiological models"

made under the supervision of Olga Mula in 2026.

Required software
=================
Python >= 3.9

Required packages: scipy, numpy, matplotlib, torch, seaborn, sklearn, os, ot, warnings

Parameters of the algorithms
=====================================================

The parameters are the following:
- t_span: studied interval over time
- x0: initial condition
- h: step in time
- R: parameters of the equation
- n_particles: number of particles to approximate probability laws
- cov: covariance matrix of the initial distribution
- precision: precision parameter for reducing automatic step in marginal plots
- X0: list of initial conditions for a GMM
- COV: list of covariance matrices of the initial distribution for a GMM
- omega: list of weights for each gaussian of the GMM
- n_components: number of gaussian distributions of the desired GMM

How to test other ODEs
======================
- Add a new class `MY_NEW_ODE`
- Define the new ODE system in a Python function called ODE
- Call the existing functions of the parent class Evolution

Licence
=======
Licensing information can be found in the accompanying file [COPYING.md](COPYING.md).
Copyright (c) 2026, Chloé His (University of Rennes & ENS Rennes) and Olga Mula (University of Vienna).
