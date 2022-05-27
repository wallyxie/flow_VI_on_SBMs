# Code for "A framework for variational inference on soil biogeochemical models featuring state space approximation by normalizing flows" by Hua Xie, Debora Sujono, Tom Ryder, Erik Sudderth, and Steven Allison.

This repository contains the following:

* Modules making up the mean-field VI on flow SDE approximations demonstrated in the paper.
* Python notebooks containing SCON-C and SCON-SS Euler-Maruyama data generating processes.
* The synthetic data sets generated from the notebooks that our experiments were conditioned on.

To run the code in its exact state, a CUDA device running CUDA version >= 10.2 with VRAM of 16 GB is needed. If GPU requirement is fulfilled, running the code is as simple as downloading the repository and then running any `learn_....py` script corresponding to your experiment of interest.
