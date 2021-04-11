---
title: NIST Post-Quantum Cryptography Competition
start: 2016
order: 7
---

For most of the public key cipher that we used today, such as RSA, Diffie-Hellman or ECC, the quantum computer's successful invention will be their doomsday. The difficult mathematical problems they rely on will no longer be infeasible for the computer to solve efficiently. 

To prepare for that day to come, the National Institute of Standards and Technology(NIST) of the USA held a competition to find suitable ciphers that can resist the attack from quantum computers and standardize them. Now the competition is in the third round. Three of the four remaining public key encryption candidates are lattice-based. 

![](https://i.loli.net/2021/04/11/uHtwndN23Wlfm8I.png){:height="200px" width="550px"}

Image: List of Round 3 Finalists

Lattice-based ciphers are constructed on high-dimension lattice problems. For example, finding the closest lattice point to a given location is easy in a two or three-dimensional lattice. But if the number of dimensions and basis vectors is as high as tens of thousands, the shortest vector problem becomes infeasible to solve even for a quantum computer. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/CVP.svg/330px-CVP.svg.png){:height="84px" width="165px"}

Image: 2D Closest vector problem (basis vectors in blue, external vector in green, closest vector in red)

[Source: Wikipedia page of "NIST Post-Quantum Cryptography Competition"](https://en.wikipedia.org/wiki/NIST_Post-Quantum_Cryptography_Competition)\\
[Source: Wikipedia page of "Lattice problem"](https://en.wikipedia.org/wiki/Lattice_problem)\\
[Source: PQC official website](https://csrc.nist.gov/Projects/post-quantum-cryptography/post-quantum-cryptography-standardization)\\
[Source: Round 3 Candidates' list](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-3-submissions)
