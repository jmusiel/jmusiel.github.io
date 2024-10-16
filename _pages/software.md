---
permalink: /software/
title: "Software"
---

## Fine-Tuning Accelerated Molecular Simulations - `Finetuna`

I am the lead developer of [`Finetuna`](https://github.com/ulissigroup/finetuna), an active learning package which makes use of transfer learning methods to accelerate atomistic relaxations on-the-fly by adapting large pre-trained graph neural network potentials from ['ocp'](https://github.com/Open-Catalyst-Project/ocp). These active-learning-accelerated relaxations are able to stably and reliably replicate the expected behavior of VASP, while reducing the number of DFT calculations required by more than 90%, due to the sophisticated representation learned by the graph model during pre-training, and the fine-tuning methods used to preserve this information. 

This package also implements a VASP replacement wrapper, which enables a one line replacement command to perform VASP relaxations with the given input files. And we have demonstrated that it supports other DFT codes and functionals, such as Quantum Espresso and BEEF-vdw.

Paper: [FINETUNA: fine-tuning accelerated molecular simulations](https://iopscience.iop.org/article/10.1088/2632-2153/ac8fe0)  
Codebase: [github.com/ulissigroup/finetuna](https://github.com/ulissigroup/finetuna)  
Data: [github.com/ulissigroup/finetuna_manuscript](https://github.com/ulissigroup/finetuna_manuscript)

## Uncertainty Quantification for Open Catalyst Project Models - `UQOCP`
I am the lead developer of [`UQOCP`](https://github.com/ulissigroup/uqocp), a package containing tools and dataset generation for benchmarking and implementing uncertainty quantification methods for OCP graph models.

Paper: [Improved Uncertainty Estimation of Graph Neural Network Potentials Using Engineered Latent Space Distances](https://arxiv.org/abs/2407.10844)  
Codebase: [github.com/ulissigroup/uqocp](https://github.com/ulissigroup/uqocp)  

## Predicting and Applying Hessians with Graph Neural Network Potentials - `Gibby`
I am a co-developer of [`Gibby`](https://github.com/jmusiel/gibby), a package which implements tools for benchmarking Hessian predictions, and using them for Gibbs free energy prediction, transition state finding, and potential energy surface characterization among other things.

Paper: [Accessing Numerical Energy Hessians with Graph Neural Network Potentials and Their Application in Heterogeneous Catalysis](https://arxiv.org/abs/2410.01650)  
Codebase: [github.com/jmusiel/gibby](https://github.com/jmusiel/gibby)  

## Fine-Tuning Accelerated Nudged Elastic Band Methods - `NEBtuna`

I am leading the development of NEBtuna, which is currently in development. NEBtuna is another active learning package, this time using pre-trained models for the on-the-fly acceleration of nudged elastic band methods (NEBs).

Codebase: [github.com/ulissigroup/nebtuna](https://github.com/ulissigroup/nebtuna)
