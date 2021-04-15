---
title: RSA - a widely used algorithm for secure data transmission
start: 1977
order: 3
---

RSA was first publicly described by Ron Rivest, Adi Shamir, and Leonard Adleman in 1977.  As a highly secure and reliable asymmetrical cryptosystem, it plays an essential role in people's daily use of the internet. Examples of its application include RSA digital signature and certificate, TLS, SSL, etc. 

Similar to the Diffie-Hellman protocol, the RSA makes good use of the _modulo exponential_ because it is a one-way function that is easy to do in one direction but hard to reverse in the other.  

The RSA algorithm uses _Euler's theorem_ to generate public and private key pairs. The _Euler's totient function_ is also applied to construct a big number with a known number of smaller numbers that are prime to it.

![](https://ae04.alicdn.com/kf/U730ccab0ff604702807e7f3238bf980co.png){:height="300px" width="450px"}

Image 1: An example of how RSA keys are generated

Encryption and decryption of messages are much easier to understand than generating keys. They only involve simple modular exponentiation with encrypted or plaintext messages and the keys. 

![](https://ae03.alicdn.com/kf/U331252f558da4f0f86e52522eadf132aw.png){:height="300px" width="450px"}

Image 2: An example of RSA encryption and decryption

The security level the RSA can achieve depends on the length of keys. Today people often use RSA keys of 1,536 to 4,096 bits to make it secure. However, it has been proved to be not _quantum-resistant_. People may need to replace it with new cryptosystems before the practical quantum computer becomes a reality.


[Source: Wikipedia page of _RSA_](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Security_and_practical_considerations)\\
[Source: The original patent of RSA](https://patents.google.com/patent/US4405829)\\
[Source: Image 1&2](https://www.bilibili.com/video/BV14y4y1272w?from=search&seid=12112992112251625934)
