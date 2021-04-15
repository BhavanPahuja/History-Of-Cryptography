---
title: Data Encryption Standard (DES)
start: 1974
order: 1
---

As mentioned above, the One-time Pad (OTP) is regarded as a cryptosystem of perfect secrecy. Unfortunately, the OTP is not easy to implement in practice because the pad needs to be as long as the plaintext, and it cannot be reused. If you can transmit the pad safely without being intercepted by the adversary, then why bother using the cipher in the first place?

Nevertheless, we can sacrifice some degree of secrecy that the OTP provides in exchange for some efficiency. _Block ciphers_ wereinvented for that purpose. They divide the plaintext message into blocks of the same length, and encrypt them using the same keys.

Created by IBM in 1974, _Data Encryption Standard_(DES) became the benchmark for encrypting sensitive US government data and was widely applied internationally later on. As a block cipher, it divides the binary message into blocks with a length of 64-bit, and uses 56-bit keys to encrypt them. 

The _Feistel network_ is used in the algorithm, which means that the 64-bit input is evenly divided into two 32-bit half blocks and they are processed for 16 identical rounds. In each round, the operations on the blocks include:

_Expansion_: adding more bits into the blocks

_Key-mixing_: combining the blocks with the subkey that is derived from the key

_Substitution_: dividing the 32-bit blocks into 6-bit ones, substituting them with 4-bit blocks according to a fixed table

_Permutation_: rearranging the output of substitution according to a fixed permutation

![](https://gblobscdn.gitbook.com/assets%2F-LcH-QVg6rYxTtCdeD1x%2F-Lnvz31vIYnJQRresaDe%2F-Lnvz3zcSRpAj0WiA1di%2Fdes_structure.jpg?alt=media){:height="380px" width="380px"}

Image: Procedure described by DES

As the computers became more capable, the DES with keys of only 56 bits gradually became unsafe. It was proved to be vulnerable to the attacks that targeted its padding process. _3DES_, a cipher that applies the DES three times to each data block, was developed later to enhance its security level. The _AES_ replaced it as the US government standard in 2001. 

[Source: Wikipedia page of _Data Encryption Standard_](https://en.wikipedia.org/wiki/Data_Encryption_Standard)\\
[Source: Image](https://gblobscdn.gitbook.com/assets%2F-LcH-QVg6rYxTtCdeD1x%2F-Lnvz31vIYnJQRresaDe%2F-Lnvz3zcSRpAj0WiA1di%2Fdes_structure.jpg?alt=media)
