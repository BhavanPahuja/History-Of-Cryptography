---
title: MD5-The first widely used hash function
start: 1992
order: 4
---

Hash functions are like fingerprints of a file. The first hash function that has been widely used in cryptography is the MD5 designed by Ronald Rivest, who is also one of the three cryptographers that invented RSA. 

Unlike encryption using ciphers like AES or RSA, hashing is a one-direction process. The computer is unable to convert the hashed result back to plaintext. Hash functions are used in cryptography to ensure data integrity and store passwords safely. 


![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Cryptographic_Hash_Function.svg/563px-Cryptographic_Hash_Function.svg.png){:height="400px" width="450px"}

Image: How small changes of input text create totally different output when hashing(The example is using SHA-1)

When someone sends a message to others, they may send the hashing output of the message together with the message itself. The receiver can hash the received message to see if the hashing results match and ensure that the message is not tampered with. 

Hash functions can also be used to store passwords. Even if adversaries get hold of the file that stored the passwords'  hashing results, they cannot retrieve the password.

Although MD5 is still widely used today, it has been proved to have severe vulnerabilities and can be easily cracked.  There are more secure hashing functions to replace it, like the Secure Hashing Algorithms(SHA) family, especially the most recently published one, SHA-3.

[Source: Wikipedia page of "MD5"](https://en.wikipedia.org/wiki/MD5)\\
[Source: Wikipedia page of "Cryptographic hash function"](https://en.wikipedia.org/wiki/Cryptographic_hash_function)\\
[Source: A youtube tutorial about hash function](https://www.youtube.com/watch?v=GI790E1JMgw)
