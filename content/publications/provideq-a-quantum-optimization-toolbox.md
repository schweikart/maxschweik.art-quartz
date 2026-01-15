---
title: "ProvideQ: A Quantum Optimization Toolbox"
date: 2025-07-11 # date of the talk according to https://services.conferences.computer.org/2025/qsw-program/
tags:
- academia
- quantum
- web-dev
---
*Domenik Eichhorn, Nick Poser, Maximilian Schweikart, Ina Schaefer.*

In our third [ProvideQ](/projects/provideq) paper, we put focus on the technical
realisation of the toolbox.
This paper was presented at IEEE's QSW 2025 conference.

# Abstract
> Hybrid solvers for combinatorial optimization problems combine the advantages
> of classical and quantum computing to overcome difficult computational
> challenges.
> Although their theoretical performance seems promising, their practical
> applicability is challenging due to the lack of a technological stack that can
> seamlessly integrate quantum solutions with existing classical optimization
> frameworks.
> We tackle this challenge by introducing the ProvideQ toolbox, a software tool
> that enables users to easily adapt and configure hybrid solvers via
> Meta-Solver strategies.
> A Meta-Solver strategy implements decomposition techniques, which splits
> problems into classical and quantum subroutines.
> The ProvideQ toolbox enables the interactive creation of such
> decompositions via a Meta-Solver configuration tool.
> It combines well-established classical optimization techniques with quantum
> circuits that are seamlessly executable on multiple backends.
> This paper introduces the technical details of the ProvideQ toolbox, explains
> its architecture, and demonstrates possible applications for several
> real-world use cases.
> Our proof of concept shows that Meta-Solver strategies already enable the
> application of quantum subroutines today, however, more sophisticated hardware
> is required to make their performance competitive.

# Read'n'cite
We have uploaded a recent preprint to the
[arXiv](https://arxiv.org/abs/2507.07649) and you can get the official
publication from
[the publisher's page](https://doi.org/10.1109/QSW67625.2025.00032).

> [!cite]- Cite
> 
> ```bibtex
> @INPROCEEDINGS{11134346,
>   author={Eichhorn, Domenik and Poser, Nick and Schweikart, Maximilian and Schaefer, Ina},
>   booktitle={2025 IEEE International Conference on Quantum Software (QSW)}, 
>   title={ProvideQ: A Quantum Optimization Toolbox}, 
>   year={2025},
>   volume={},
>   number={},
>   pages={206-214},
>   keywords={Quantum algorithm;Algorithms;Quantum mechanics;Computer architecture;Hardware;Software tools;Quantum circuit;Optimization;quantum computing;quantum software;quantum algorithm;hybrid optimization},
>   doi={10.1109/QSW67625.2025.00032}
> }
> ```
> *Source: [IEEE Xplore](https://ieeexplore.ieee.org/document/11134346)*

# Further links
* 🖱️ [Try the ProvideQ Toolbox online](https://provideq.kit.edu)
* 👩‍💻 [Get the code from GitHub](https://github.com/ProvideQ)
* 📄 [Read the API docs](https://api.provideq.kit.edu/)
