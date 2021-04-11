---
title: Data Encryption Standard(DES)
start: 1974
order: 1
---

In 1977, a symmetric-key algorithm invented by IBM became the standard for encrypting sensitive government data and was widely adapted internationally later on. As a block cipher, it divides the binary message into blocks with a length of 64-bit and uses 56-bit keys to encrypt them. 

The Feistel network is used in the algorithm, which means that the 64-bit input is evenly divided into two 32-bit half blocks and processed for 16 identical rounds. In each round, the operations on the blocks include:

Expansion: adding more bits into the blocks

Key-mixing: combining the blocks with the subkey that is derived from the key

Substitution: dividing the 32-bit blocks into 6-bit ones, substituting them with 4-bit blocks according to a fixed table

Permutation: rearranging the output of substitution according to a fixed permutation. 

![](https://gblobscdn.gitbook.com/assets%2F-LcH-QVg6rYxTtCdeD1x%2F-Lnvz31vIYnJQRresaDe%2F-Lnvz3zcSRpAj0WiA1di%2Fdes_structure.jpg?alt=media){:height="380px" width="350px"}

Image: Data Encryption Standard

As the computers become more capable, the cipher with keys of only 56 bits gradually became unsafe. It was proved to be vulnerable to the attacks that target its padding process. 3DES, a cipher that applies the DES three times to each data block, is developed later to enhance its security level. The AES replaced it in 2001. 

[Source: Wikipedia](https://en.wikipedia.org/wiki/Data_Encryption_Standard)\\
[Source: Think && Act(a blog in Chinese)](https://kysonlok.gitbook.io/blog/cryptography/data_encryption_standard)
