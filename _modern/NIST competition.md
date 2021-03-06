---
title: NIST Post-Quantum Cryptography Competition
start: 2016
order: 7
---

For most _public-key ciphers_ that we use today, such as RSA, Diffie-Hellman or ECC, the _quantum computer_'s successful implementation will be their doomsday. The difficult mathematical problems they rely on will become feasible for the computer to solve efficiently. 

To cope with the threat that the quantum computer may pose to data security, the National Institute of Standards and Technology (NIST), which is part of the United States Department of Commerce, holds a competition to find ciphers that can resist the attacks from quantum computers, and standardizes them. 

Now the competition is in its third round, and the NIST is yet to decide on the new standard. Three of the four remaining public key encryption candidates are _lattice-based_. 

![](https://i.loli.net/2021/04/11/uHtwndN23Wlfm8I.png){:height="200px" width="550px"}

Image 1: List of Round 3 candidates

_Lattice-based ciphers_ are constructed on high-dimensional lattice problems. For example, finding the closest lattice point to a given location is easy in a two or three-dimensional lattice. But if the number of dimensions is as high as tens of thousands, the _shortest vector problem(SVP)_ becomes infeasible to solve even for a quantum computer. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/CVP.svg/330px-CVP.svg.png){:height="84px" width="165px"}

Image 2: 2D closest vector problem (basis vectors in blue, external vector in green, closest vector in red)

[Source: Wikipedia page of _NIST Post-Quantum Cryptography Competition_](https://en.wikipedia.org/wiki/NIST_Post-Quantum_Cryptography_Competition)\\
[Source: Wikipedia page of _Lattice-based cryptography_](https://en.wikipedia.org/wiki/Lattice-based_cryptography)\\
[Source: Wikipedia page of _Lattice problem_](https://en.wikipedia.org/wiki/Lattice_problem)\\
[Source: PQC official website](https://csrc.nist.gov/Projects/post-quantum-cryptography/post-quantum-cryptography-standardization)\\
[Source: Round 3 Candidates' list](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-3-submissions)\\
[Source: Image 1](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-3-submissions)\\
[Source: Image 2](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/CVP.svg/330px-CVP.svg.png)
