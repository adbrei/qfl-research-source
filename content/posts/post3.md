---
title: "Literature Review: ''How to get started in quantum computing'' "
author: "Anneliese Brei"
tags: ["Quantum Computing", "Classical Computing"] 
date: "2021-06-03" 
---
-----------------------------
*(Last updated: June 3, 2021)*

### Summary

David Matthews' paper "How to get started in quantum computing," by Nature News, is an excellent survey paper of today's state of computing. Published online just a few months ago on 4 March 2021, it summarizes fundamental ideas behind quantum computing motivating new research. The paper names leading companies and institutions who have been contributing to the swiftly growing field, and it distinguishes a few broad aspects of their approach. Beginners can use this paper as a springboard into the world of quantum computing. Below, I summarize a few key points.[^1]

### Exploring Ideas Behind Quantum Computing

Quantum circuits consist of gates that operate on qubits, the quantum computer's equivalent of a classical bit. These qubits use quantum properties with the potential to speed up calculations for special classes of problems. Right now, their use is extremely limited, and we don't know the extent to which they might improve our computational situation. We are in the early stages, since we don't yet have a computer with more than 100 qubits, and most of our problems will require computers with thousands of qubits. Hence, most research has been theoretical; only a few experiements have been conducted on real quantum machines. 

> "The stage of quantum computers now is something like classical computing in the late 1980s... Most of the work done now is to prove that quantum, in the future, may have the ability to solve interesting problems." ~ Sara Metwalli, quantum-computing researcher at Keio University, Tokyo

The digital logic behind qubits is more complex than the logic behind bits. Instead of operating under the rules of Boolean Algebra, it has been modeled with linear algebra:

> "Quantum computing is essentially matrix vector multiplication - it's linear algebra underneath the hood." ~ Krysta Svore, principal manager of quantum-computing group at Microsoft Research

### Important Dates/Milestones

- 2019: Google demonstrated landmark quantum speedup: their 54-qubit quantum computer took minutes to solve a solution that would take a classical computer over 10,000 years to solve

- 2021: IBM hopes to produce a 1,000 qubit machine

### Online Learning

- Quantum Country: https://quantum.country
- IBM's interactive toolkit for Qiskit quantum language: https://qiskit.org/textbook/preface.html

### Programming Resources

Emulator:
- IBM's Quantum Experience: https://quantum-computing.ibm.com
> - Create simulations of quantum circuits in web browser
> - May run remotely on real quantum computer

Languages/Environments Developed by Technology Giants:
- Q# (Microsoft)
- Qiskit (IBM)
- Cirq (Google)

Languages/Environments Developed by Non-Giants:
- Forest (Rigetti Computing in Berkeley, CA)
- tket (Cambridge Quantum Computing, UK)
- Silq (Swiss Federal Institute of Technology (ETH), Zurich)
> - Based on 'uncomputation'
- Quipper (Dalhousie University?)
> - Less user friendly: functional language, not based on Python (imperative)

### Where Are the Physical Computers?
Note, it is highly recommended that researchers test their circuits on emulators before trying them out on a real quantum machine.
- IBM
> - 5-qubit machine freely available
> - More powerful machines available to IBM's Quantum Network
- Microsoft
> - Offers limited free access to other firms' quantum computers through Azure Quantum platform 
- Amazon Web Services
> - Cloud-computing platform that utilizes other firm's quantum devices for $1 per quantum circuit

### References
[^1]: Matthews, David. “How to Get Started in Quantum Computing.” Nature News, Nature Publishing Group, 1 Mar. 2021, www.nature.com/articles/d41586-021-00533-x.

