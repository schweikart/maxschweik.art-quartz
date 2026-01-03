---
title: Academia
---

I'm currently studying computer science at the
[Karlsruhe Institute of Technology](https://kit.edu).
On this page, you can find papers and slides I prepared either for courses I
took or for jobs I had there.

## ProvideQ Toolbox
*Aug 2022 - now*

With quantum algorithms, we can solve problems like prime factorization faster
than with any known classical (non-quantum) algorithm.
However, quantum computers are just becoming available to the public - and
they're hard to program!
The programming frameworks for quantum computers available today are similar to
writing assembler code for classical computers and in addition you have to know
your quantum mechanics to some extent.

With the tooling still in early development, it is hard to harness the power of
quantum computers today without having to become an expert in the field.
**ProvideQ** tackles this obstacle through a web service that allows solving
common problems in computer science like the SATisfiability problem.
Problems instances submitted to the ProvideQ toolbox will be solved either with
a classical or a quantum problem solver, depending the problem and what
available quantum computers are capable of.

- [Check out the toolbox source code on GitHub](https://github.com/ProvideQ)
- [Read the program profile from the funding Ministry](https://www.digitale-technologien.de/DT/Redaktion/EN/Standardartikel/Quanten-Computing/qc_projekt_provideq.html)
- [Learn more on the informational website about the project](https://www.provideq.org/)

---

## Fork() and Alternatives
*Apr 2022*

The `fork()` system call is the de-facto way of creating processes in Linux.
While it was designed to support the parallel execution of programs, it is today also often used for its copy-on-write capabilities.
Even though `fork()` is used in a wide variety of use cases both in desktop and server software, it performs poorly in memory-intensive programs and violates fundamental design principles for operating systems.
This paper summarizes alternative approaches to process creation and discusses them with regard to these problems.
We recommend to replace the `fork()` system call with a different set of system calls to create an API that has a reasonable complexity and respects security and memory management best practices.

- [Read the paper](/publications/fork-and-alternatives.pdf){external=true}

---

## ROSE
*Oct 2021 - Mar 2022*

ROSE is a graphical road system editor used to set up highway networks that can be exported to traffic simulation software.
It was created as a group project in the ["Praxis der Softwareentwicklung" (Software Engineering Practice)](https://pp.ipd.kit.edu/lehre/WS202122/pse/?lang=en) course at the Karlsruhe Institute of Technology.
The goal of PSE is to build a useful application using the [waterfall model](https://en.wikipedia.org/wiki/Waterfall_model).
This repository contains the documents that we submitted for the different phases of the project.

- [Source code of the application on GitHub](https://github.com/road-system-editor/rose)
- [Submitted documents and presentation slides on GitHub](https://github.com/road-system-editor/pse-documents)
