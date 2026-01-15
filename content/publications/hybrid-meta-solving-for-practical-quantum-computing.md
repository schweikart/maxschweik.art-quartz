---
title: Hybrid Meta-Solving for Practical Quantum Computing
date: 2024-09-17 # paper presentation date, source: https://qce.quantum.ieee.org/2024/wp-content/uploads/sites/8/2024/09/QCE24_Technical_Paper-Tracks__Final_Agenda_v157-with-best-papers-v2.pdf
tags:
- academia
- quantum
---
*Domenik Eichhorn, Maximilian Schweikart, Nick Poser, Frederik Fiand, Benedikt Poggel, Jeanette Miriam Lorenz.*

After having established the vision of the
[ProvideQ Toolbox](/projects/provideq) in our
[first paper](/publications/providing-quantum-readiness-the-vision-of-the-provideq-toolbox.md),
this work introduces **Meta-Solving** as the underlying theory for the tool.

# Abstract
> The advent of quantum algorithms has initiated a discourse on the potential
> for quantum speedups for optimization problems.
> However, several factors still hinder a practical realization of the potential
> benefits.
> These include the lack of advanced, error-free quantum hardware, the absence
> of accessible software stacks for seamless integration and interaction, and
> the lack of methods that allow us to leverage the theoretical advantages to
> real-world use cases.
> This paper works towards the creation of an accessible hybrid software stack
> for solving optimization problems, aiming to create a fundamental platform
> that can utilize quantum technologies to enhance the solving process.
> We introduce a novel approach that we call Hybrid Meta-Solving, which combines
> classical and quantum optimization techniques to create customizable and
> extensible hybrid solvers.
> We decompose mathematical problems into multiple sub-problems that can be
> solved by classical or quantum solvers, and propose techniques to
> semi-automatically build the best solver for a given problem.
> Implemented in our ProvideQ toolbox prototype, Meta-Solving provides
> interactive workflows for accessing quantum computing capabilities.
> Our evaluation demonstrates the applicability of Meta-Solving in industrial
> use cases.
> It shows that we can reuse state-of-the-art classical algorithms and extend
> them with quantum computing techniques.
> Our approach is designed to be at least as efficient as state-of-the-art
> classical techniques, while having the potential to outperform them if future
> advances in the quantum domain are made.

# Read'n'cite
The official publication is available on the
[publisher's website](https://doi.org/10.1109/QCE60285.2024.00056).
You can find a recent preprint on [arXiv](https://arxiv.org/abs/2405.09115).

> [!cite]- Cite
> 
> ```bibtex
> @INPROCEEDINGS{10821252,
>   author={Eichhorn, Domenik and Schweikart, Maximilian and Poser, Nick and Fiand, Frederik and Poggel, Benedikt and Lorenz, Jeanette Miriam},
>   booktitle={2024 IEEE International Conference on Quantum Computing and Engineering (QCE)}, 
>   title={Hybrid Meta-Solving for Practical Quantum Computing}, 
>   year={2024},
>   volume={01},
>   number={},
>   pages={421-431},
>   keywords={Quantum computing;Quantum algorithm;Vehicle routing;Prototypes;Full stack;Quantum mechanics;Rendering (computer graphics);Software;Hardware;Optimization;hybrid quantum-classical computing;hybrid optimization;hybrid software framework},
>   doi={10.1109/QCE60285.2024.00056}
> }
> ```
> *Source: [IEEE Xplore](https://ieeexplore.ieee.org/document/10821252)*
