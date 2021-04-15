---
title: The One-Time Pad
start: 1919
order: 2
---

Cousin to the stream cipher and invented by the same minds, the one-time pad is an uncrackable encryption technique (if applied correctly). The "pad" part of the name comes from the sheets of paper on which the key stream was printed.

The key (no pun intended) difference between the OTP and a standard stream cipher is that the digits in the key stream are _truly random_. A proper OTP should also have the following properties:

1. The key length must be at least equal to the plaintext length
2. Only two copies of the pad must ever exist
3. Any OTP should only be used once
4. Both copies of the OTP must be destroyed immediately post-communication

The OTP was very popular among intelligence agents (and is still used today). Spies would often conceal the pads in incospicuous objects such as walnuts, stones and more.

![](https://cryptosmith.files.wordpress.com/2007/06/walnut_12539.jpg){:height="200px" width="300px"}

If you'd like to get into the nitty-gritty of how the OTP works, [this paper](http://users.telenet.be/d.rijmenants/papers/one_time_pad.pdf) is an excellent read.

[Source: Wikipedia](https://en.wikipedia.org/wiki/One-time_pad#History)\\
[Source: Crypto Museum](https://www.cryptomuseum.com/covert/deaddrop/walnut.htm)\\
[Image](https://cryptosmith.files.wordpress.com/2007/06/walnut_12539.jpg)
