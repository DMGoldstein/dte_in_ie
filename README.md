# Divergence-time estimation in Indo-European: The case of Latin

This repository contains the scripts and code for the paper "Divergence-estimation in Indo-European: The case of Latin." The folders `mcmc`, `lnl`, and `pps` folders contain the header files for the MCMC, marginal likelihood, and posterior-predictive simulation (PPS) analyses. The header files configure the settings for the analyses presented in the paper. The code for the various components of the models (i.e., tree model, clock model, character-change model) are housed in the folder `modules`.

The `data` folder contains the following three files: 

1. `chang_romance_broad_variable.nex`
2. `romance_broad_variable_taxa_fbd.tsv`
3. `romance_broad_variable_taxa_fbdr_ancient.tsv`

The first contains the character matrix used in all of the analyses. The second and third contain the occurrence times and stratigraphic ranges for Latin. 

To run the analyses, set the `path` argument in the file `path.Rev` to the location of the folder `scripts_and_data` on your local machine. There is a unique version of this file in each of the `mcmc`, `lnl`, and `pps` folders. In each case it is located in the `/romance/broad_variable` folder. 

Once you have specified the path, open `RevBayes` and input `source("file_name.Rev")`, with `file_name.Rev` being the name of one of the header files in folders mentioned above. For instance, to run the MCMC analysis of the FBD F81 UCE model, issue the command `source("romance_broad_variable_dns_fbd_f81_uce_stem.Rev")`.

The organization of the directories follows the workflow laid out by Mike May in 
[this tutorial](https://revbayes.github.io/tutorials/ted_workflow/).

The analyses in the paper were conducted with [RevBayes 1.1.1](https://github.com/revbayes/revbayes/releases/tag/1.1.1).


