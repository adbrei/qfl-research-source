---
title: "First Pass: ''TensorFlow Quantum'' Paper"
author: "Anneliese Brei"
tags: ["Quantum Computing", "Federated Learning", "Classical Computing", "Performing Research"] 
date: "2021-06-15" 
---
-----------------------------
*(Last updated: June 15, 2021)*

In my last post, I summarized ["How to Read a Paper"](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)[^1] with the Three-Pass method. Now, I would like to apply this algorithm to one paper especially significant to my research: [“TensorFlow Quantum: A Software Framework for Quantum Machine Learning.”](https://arxiv.org/pdf/2003.02989.pdf)[^2].
In this post, I perform the first pass. This paper is worth a second pass, since it is directly relevant to my research.

----------

### Review of First Pass (from previous post)
Without reading details or illustrations, get a general understanding of the paper's topic and how it will approach the topic. Determine the paper's category, context, correctness, contributions, and clarity (the 5 C's). After this pass, you should be able to determine whether or not the paper is worth the second pass.

1. Read title, abstract, introduction
2. Read section, subsection headings
3. Read conclusions
4. Glance at references

### 1. Read Title, Abstract, Introduction
#### Title:
"TensorFlow Quantum: A Software Framework for Quantum Machine Learning"

#### Abstract:
TensorFlow := open source library that allows you to create hybrid quantum-classical machine learning models

This paper introduces the software architecture and building blocks behind TensorFlow and the theory of (hybrid) quantum-classical machine learning (via neural networks). The paper applies the TensorFlow tools to supervised learning for quantum classification, control, and approximate optimization.


#### Introduction:
The introduction has four sections: 
1. Quantum Machine Learning
>An overview of machine learning and how quantum computing can be used to solve machine learning problems that are practically impossible for classical computers to solve.
2. Hybrid Quantum-Classical Models
>The reasons why hybrid models are currently more effective than purely quantum models: quantum processors are still near-term (not completely fault tolerant) and are primarily used as computational accelerators.
3. Quantum Data
>What quantum data is, and four different classes: quantum simulations, quantum communication networks, quantum metrology, quantum control.
4. TensorFlow Quantum
>The role of TensorFlow in building quantum models: a bridge between machine learning and quantum computing communities.

### 2. Read Section, Subsection Headings
The relatively long paper (39 pages) has a table of contents with five main sections before the closing remarks, acknowledgements, and references.
1. Introduction (see above)
2. "Software Architecture & Building Blocks": An introduction to Cirq language and TensorFlow to build quantum circuits
3. "Theory of Hybrid Quantum-Classical Machine Learning": An overview of the mathematical equations behind hybrid machine learning.
4. "Basic Quantum Applications": Examples of how to use TensorFlow features on *basic applications*
5. "Advanced Quantum Applications": Examples of how to use TensorFlow features on *advanced applications*

### 3. Read Conclusions
The Closing Remarks is a short paragraph that places TensorFlow into the real-world environment of quantum hardware development.

### 4. Glance at References
There are 129 references from textbooks, papers and conferences. I will continue to look at this list as the need arises.

### References
[^1]: Keshav, S. “How to Read a Paper.” ACM SIGCO>MM Computer Communication Review, vol. 37, no. 3, 2007, pp. 83–84., doi:10.1145/1273445.1273458. 
[^2]: Broughton, Michael, et al. “TensorFlow Quantum: A Software Framework for Quantum Machine Learning.” ArXiv.org, 6 Mar. 2020, arxiv.org/abs/2003.02989.
