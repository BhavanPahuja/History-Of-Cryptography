---
title: RSA - a widely used algorithm for secure data transmission
start: 1977
order: 3
---

RSA was first publicly described by Ron Rivest, Adi Shamir, and Leonard Adleman in 1977.  As a highly secure and reliable asymmetrical cryptosystem, it plays an essential role in people's daily use of the internet. Examples include RSA digital signature and certificate, TLS, SSL, etc. 

Similar to the Diffie-Hellman protocol, the RSA makes good use of the modulo exponential because it is a one-way function that is easy to do in one direction but hard to reverse in the other.  Euler's totient function is used to construct a big prime with known prime factors, and the public and private keys are generated based on them.  

![](https://slidetodoc.com/presentation_image/3cc8399d4102e786d34cbc19c089149b/image-120.jpg){:height="400px" width="450px"}

Image: an example of generating public and private keys of RSA

The properly implemented RSA system is regarded as unbreakable now because of the computer's lack of efficient methods to find the factors of huge primes. Only RSA private keys with very short lengths were successfully broken in the past. However, the algorism may become insecure if the quantum computer is invented one day. It may be able to solve the mathematical problem it relies on efficiently.

[Source: Wikipedia](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Security_and_practical_considerations)\\
[Source: The original patent of RSA](https://patents.google.com/patent/US4405829)\\
[Source: The example from SlideToDoc](https://slidetodoc.com/part-1-instruction-of-network-security-3-3/)
