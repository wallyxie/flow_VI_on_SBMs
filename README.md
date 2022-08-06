# Code for "A framework for variational inference on soil biogeochemical models featuring state space approximation by normalizing flows" by Hua Xie, Debora Sujono, Tom Ryder, Erik Sudderth, and Steven Allison.

This repository contains the following:

* Modules constituting the mean-field variational inference with normalizing flow algorithm demonstrated in the paper in the top level of the repository.
* Various scripts with `learn_theta....py` file names for launching the specific approximated SCON-C and SCON-SS optimizations described in the paper results. 
* Python notebooks containing SCON-C and SCON-SS Euler-Maruyama data generating processes in the `python_notebooks` folder.
* The synthetic data sets generated from the notebooks that our experiments were conditioned on in the `generated_data` folder.

To run the code in its exact state, a CUDA device running CUDA version >= 10.2 with VRAM of 16 GB is needed. If GPU requirement is fulfilled, running the code is as simple as downloading the repository and then running any `learn_theta....py` script corresponding to your experiment of interest.
