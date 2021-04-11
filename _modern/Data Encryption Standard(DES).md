---
title: Data Encryption Standard (DES)
start: 1974
order: 1
---

Created by IBM in 1974, Data Encryption Standard(DES) became the standard for encrypting sensitive US government data and was widely applied internationally later on. As a block cipher, it divides the binary message into blocks with a length of 64-bit and uses 56-bit keys to encrypt them. 

The Feistel network is used in the algorithm, which means that the 64-bit input is evenly divided into two 32-bit half blocks and they are processed for 16 identical rounds. In each round, the operations on the blocks include:

Expansion: adding more bits into the blocks

Key-mixing: combining the blocks with the subkey that is derived from the key

Substitution: dividing the 32-bit blocks into 6-bit ones, substituting them with 4-bit blocks according to a fixed table

Permutation: rearranging the output of substitution according to a fixed permutation. 

![](https://gblobscdn.gitbook.com/assets%2F-LcH-QVg6rYxTtCdeD1x%2F-Lnvz31vIYnJQRresaDe%2F-Lnvz3zcSRpAj0WiA1di%2Fdes_structure.jpg?alt=media){:height="380px" width="380px"}

Image: Procedure described by DES

As the computers become more capable, the DES with keys of only 56 bits gradually became unsafe. It was proved to be vulnerable to the attacks that target its padding process. 3DES, a cipher that applies the DES three times to each data block, is developed later to enhance its security level. The AES replaced it as a US government standard in 2001. 

[Source: Wikipedia page of "Data_Encryption_Standard"](https://en.wikipedia.org/wiki/Data_Encryption_Standard)\\
[Source: Think && Act(a technology blog)](https://kysonlok.gitbook.io/blog/cryptography/data_encryption_standard)
