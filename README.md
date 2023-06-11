# Divergence-time estimation in Indo-European: The case of Latin

This repository contains the scripts and code for the paper "Divergence-estimation in Indo-European: The case of Latin." The folders `mcmc`, `lnl`, and `pps` folders contain the header files for the MCMC, marginal likelihood, and posterior-predictive simulation analyses. Within each of these folders there are header files that configure the settings for the analyses presented in the paper. To run the analyses, you will need to set the `path` argument in the file `path.Rev` to the location of the folder on your local machine (there is a unique version of this file in each of the `mcmc`, `lnl`, and `pps` folders).

The folder `modules` contains the code for the various components of the model (i.e., tree model, clock model, character-change model).
