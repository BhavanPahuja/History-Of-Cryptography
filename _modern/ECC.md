---
title: Elliptic Curve Cryptography(ECC)
start: 2004
order: 6
---

The Elliptic Curve cryptography is first suggested by Neal Koblitz and Victor S. Mille in 1985 but is not widely used until 2004. As its name suggests, its security is based on the Elliptic Curve. 

Like other public-key ciphers, ECC also relies on the computer's inability to solve a mathematical problem: the elliptic curve discrete logarithm problem. The point multiplication for an elliptic curve is easy to do for the computer, but the process is hard to reverse. 

![](https://i.stack.imgur.com/ygncy.png){:height="400px" width="450px"}

Image: How multiplication is done on an elliptic curve

Compared to the RSA, ECC can achieve the same security level using keys with fewer bits, which means a lot since the devices we use often have limited memory. Given its high security and good efficiency, it is now widely used to do the key exchange, make Digital Signature and implement cryptocurrencies. 

[Source: Wikipedia page of "ECC"](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography)\\
[Source: The image](https://crypto.stackexchange.com/questions/48657/how-does-ecc-go-from-decimals-to-integers)
