---
title: Kasiski's test 
start: 1863
order: 5
---

![](http://4.bp.blogspot.com/-dSovKAAOnf4/USmy1SnDfTI/AAAAAAAAARw/AWNIWKrjTcI/s200/babbage.png){:height="200px" width="160px"}

Kasiski's test is a method of statistical analysis that utilized the cracked polyalphabetic substitution ciphers. Although published by Friedrich Kasiski in 1863, the technique had already been developed by Charles Babbage as early as 1846. Sadly the system was attributed to Friedrich because Charles Babbage had a bad habit of not finishing the paperwork aspect of his work.

One of the fundamental weakness of the polyalphabetic substitution cipher is that if the key length is known, the ciphertext can be split apart into *individual shift ciphers*. The Kasiski’s method exploits this weakness and focuses on determining the *key size* of the polyalphabetic substitution cipher. In order to find the key length, we seach for *repeated strings* of characters in the ciphertext. Then, we look at the overall distances between the occurrences, which allows us to figure out which ones are *multiples* of the key length. After that, we can decipher the text.


[Source: Cryptography - Engineering and Technology History](http://ethw.org/Cryptography)\\
[Source: A bils's security site](https://asecuritysite.com/encryption/kasiski)
\\
[Image](http://4.bp.blogspot.com/-dSovKAAOnf4/USmy1SnDfTI/AAAAAAAAARw/AWNIWKrjTcI/s200/babbage.png)


