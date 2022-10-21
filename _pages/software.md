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

## Fine-Tuning Accelerated Nudged Elastic Band Methods - `NEBtuna`

I am leading the development of NEBtuna, which is currently in development. NEBtuna is another active learning package, this time using pre-trained models for the on-the-fly acceleration of nudged elastic band methods (NEBs).

Codebase: [github.com/ulissigroup/nebtuna](https://github.com/ulissigroup/nebtuna)
