---
title: Elliptic Curve Cryptography(ECC)
start: 2004
order: 6
---

The Elliptic Curve cryptography was first suggested by Neal Koblitz and Victor S. Mille in 1985 but was not widely used until 2004. 

Like other public-key ciphers, ECC also relies on the computer's inability to solve a mathematical problem: the _elliptic curve discrete logarithm problem_. The point _multiplication_ for an elliptic curve is easy to do for the computer, but the process is hard to reverse. 

The mechanism of ECC can be simplified as _nA = B_. In the equation, A is the _starting point_ on the curve, while B is the _resulting point_ after n times of multiplication. When doing one time of multiplication, the _tangent line_ through the original point is drawn, and its point of intersection on the elliptic curve is found, which is the result of _2*the original point_. 

![](https://i.stack.imgur.com/ygncy.png){:height="400px" width="450px"}

Image: How multiplication is done on an elliptic curve

Then the multiplier n is kept as the _private key_. It is extremely difficult for an adversary to find the private key given the starting point A and the ending point B. 

Compared to the RSA, ECC can achieve the same security level using keys with fewer bits, which means a lot since the devices we use often have limited memory. Given its high security and good efficiency, it is now widely applied to do the key exchange, make Digital Signature and implement cryptocurrencies like _Bitcoins_. 

However, there are some concerns about the current ECC standard. Some leaked documents indicate that the USA's National Security Agence(NSA) puts a backdoor in it and makes it unsafe.

[Source: Wikipedia page of _ECC_](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography)\\
[Source: A tutorial on ECC on YouTube](https://www.youtube.com/watch?v=muIv8I6v1aE)\\
[Source: The image](https://crypto.stackexchange.com/questions/48657/how-does-ecc-go-from-decimals-to-integers)
