---
title: RSA - a widely used algorithm for secure data transmission
start: 1977
order: 3
---

RSA was first publicly described by Ron Rivest, Adi Shamir, and Leonard Adleman in 1977.  As a highly secure and reliable asymmetrical cryptosystem, it plays an essential role in people's daily use of the internet. Examples include RSA digital signature and certificate, TLS, SSL, etc. 

Similar to the Diffie-Hellman protocol, the RSA makes good use of the modulo exponential because it is a one-way function that is easy to do in one direction but hard to reverse in the other.  Euler's totient function is used to construct a big prime with known prime factors, and the public and private keys are generated based on them.  

![](https://lh3.googleusercontent.com/proxy/dpEOAiyv3zhGBmXzzrjGZWuyTXLY90JcbabGIyBWgzhnWv15GtpcJCN5g6vpnvsCfW9sJ4C4rVi1BrukIvW7t-4du50MVnzNd6PSZxwf_L1kWg){:height="350px" width="450px"}

Image: An example of how RSA keys are generated

The properly implemented RSA system is regarded as unbreakable now because of the computer's lack of efficient methods to find the factors of huge primes. Only RSA private keys with very short lengths were successfully broken in the past. However, the algorism may become insecure if the quantum computer is invented one day. It may be able to solve the mathematical problem it relies on efficiently.

[Source: Wikipedia page of "RSA"](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Security_and_practical_considerations)\\
[Source: The original patent of RSA](https://patents.google.com/patent/US4405829)\\
[Source: The example](http://modafurstore.com/nantyr/rsa-example-p-17-q-11.php)
