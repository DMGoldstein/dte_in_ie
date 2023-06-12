# Divergence-time estimation in Indo-European: The case of Latin

This repository contains the scripts and code for the paper "Divergence-estimation in Indo-European: The case of Latin." The folders `mcmc`, `lnl`, and `pps` folders contain the header files for the MCMC, marginal likelihood, and posterior-predictive simulation (PPS) analyses. The header files configure the settings for the analyses presented in the paper. The code for the various components of the models (i.e., tree model, clock model, character-change model) are housed in the folder `modules`.


To run the analyses, set the `path` argument in the file `path.Rev` to the location of the folder on your local machine (there is a unique version of this file in each of the `mcmc`, `lnl`, and `pps` folders). Open `RevBayes` and input `source("file_name.Rev")`, with `file_name.Rev` being the name of one of the header files in folders mentioned above. For instance, to run the MCMC analysis of the FBD F81 UCE model, issue the command `source("romance_broad_variable_dns_fbd_f81_uce_stem.Rev")`.

The organization of the directories follows the workflow laid out by Mike May in 
[this tutorial](https://revbayes.github.io/tutorials/ted_workflow/).
