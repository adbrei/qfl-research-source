---
title: "Classical versus Quantum Computing" 
author: "Anneliese Brei"
tags: ["Quantum Computing"] 
date: "2021-06-02" 
lastchange: "2021-06-03"
---
-----------------------------
*(Last updated: June 3, 2021)*


There exist a plethora of methods of computation. The most commonly used computation is classical computation. Here, we explore the basic differences between classical and quantum.

### Classical Computing

Also known as binary computing, classical computing is a system of computation that uses bits (represented by 0 and 1) to logically store and manipulate information. Historically, all computers from Babbage's theoretical "analytical machine" to the supercomputers produced by Hewlett Packard Enterprise's subsidiary, Cray Inc., have operated according to classical computing [^1]. Classical computers have overcome massive computation feats, made increasingly possible by small and faster transitors. Consequently, we seek to solve harder problems that require greater amounts of computing power. But soon this won't be possible to achieve with classical computers. Moore's Law is becoming less of a reality[^2],  and when we are no longer able to reduce the size of transitors, we must look beyond classical computers for new ways of solving increasingly complex problems.[^3]

### Quantum Computing

Quantum computing is a system of computation that uses qubits (represented by 0, 1, or both in a phenenma called superposition) to store and manipulate information. Instead of relying on classical mechanics, this system is based on quantum mechanics, where each qubit is a spin. We can express many properties of quantum computing using linear algebra and matrix multiplication.[^3] For example, if we consider qubits as vectors, then 0 ("spin up" represented as |0> ) and 1 ("spin down" represented as |1> ) are the two basis states [^4]. It is possible to have a superposition of these states, where the general state of all the qubits is a unit vector in 2^n-dimensional complex space, where n is the number of qubits [^1].

The properties of quantum mechanics gives a new perspective of complex calculations. For a subset of special cases, it drastically improves performance. For this reason, quantum computing has seen a boom in the last few years and has generated a vast field of promising research [^3].

### Comparison:
Table of Classical versus Quantum Computing: [^5]

>|               | Classical Computing   | Quantum Computing
----            | :----                  | :----
Used by:        | large-scale computers | high-speed quantum computers
Info stored in: | bits                  | qubits
Number states:  | 2 (0 or 1)            | infinite
Calculations:   | deterministic         | probabilistic 
Data processing carried out by: &emsp;&emsp;&emsp;&emsp;| logic (sequentially)   | quantum logic (parallel-ly)
Operations defined by:  | Boolean algebra               |Linear algebra over Hilbert space
Circuit behavior:       | defined by classical physics &emsp;&emsp;&emsp;&emsp; | defined by quantum mechanics



### References:
[^1]: Kitaev, A. Yu, et al. Classical and Quantum Computation. American Mathematical Society, 2002.
[^2]: Moore's Law (Wikipedia): https://en.wikipedia.org/wiki/Moore%27s_law
[^3]: Matthews, David. “How to Get Started in Quantum Computing.” Nature News, Nature Publishing Group, 1 Mar. 2021, www.nature.com/articles/d41586-021-00533-x.
[^4]: Andy Matuschak and Michael A. Nielsen, “Quantum Computing for the Very Curious”, https://quantum.country/qcvc, San Francisco (2019).
[^5]: https://whatis.techtarget.com/definition/classical-computing
