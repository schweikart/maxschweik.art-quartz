---
title: Fork() and Alternatives
date: 2022-04-01 # not sure about the day
tags:
- academia
---

The `fork()` system call is the de-facto way of creating processes in Linux.
While it was designed to support the parallel execution of programs, it is today also often used for its copy-on-write capabilities.
Even though `fork()` is used in a wide variety of use cases both in desktop and server software, it performs poorly in memory-intensive programs and violates fundamental design principles for operating systems.
This paper summarizes alternative approaches to process creation and discusses them with regard to these problems.
We recommend to replace the `fork()` system call with a different set of system calls to create an API that has a reasonable complexity and respects security and memory management best practices.

- 📜 [Read the paper](/publications/fork-and-alternatives.pdf)
<!-- TODO: upload -->
