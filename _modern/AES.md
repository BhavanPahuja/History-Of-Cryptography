---
title: AES - the symmetric cipher that is widely used today
start: 2001
order: 4
---

In 2001, the US government replaced the unsafe DES with the new Advanced Encryption Standard(AES) to encrypt electronic data. It uses blocks of 128 bits in length and keys of 128, 192 or 256 bits in length, significantly longer than what is used in DES.

The encryption operates on 4*4 arrays made up of bits of binary plaintext. Similar to DES, each data block go through multiple rounds of processing. The number of processing rounds for AES-128, AES-192 and AES-256 is 10, 12, 14, respectively. In each round, some complex substitutions and transpositions are done to the elements of the array. Rows and Columns are shifted and mixed and combined with the subkey derived from the key. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/AES-MixColumns.svg/1920px-AES-MixColumns.svg.png){:height="300px" width="320px"}

Image: MixColumns step of the AES

Nowadays, the AES is still widely used and is regarded to be highly secured when correctly implemented. No known attack can break it without any prior knowledge of the key. 

[Source: Wikipedia](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)\\
[Source: Announcement made by NIST](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf)
