---
title: Diffie-Hellman key exchange - the first public key protocol
start: 1976
order: 2
---


Imaging _solving_ a Rubik's Cube of 3*3 cubies per face. Is it hard for you? If not, what about solving one with 128 cubies per face? Do you think that can be done by a human being? Meanwhile, _scrambling_ a Rubik's cube of 128 cubies per face can be an easy job even for a 3-year-old kid, which is precisely the essence of _Diffie-Hallman key exchange_, and subsequently, the _public key cryptosystem_. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/17_layer_cube.png/800px-17_layer_cube.png){:height="230px" width="250px"}

Image: A Rubik's Cube

Before public-key cryptography was developed, all the cryptosystems used symmetrical keys, which means that the sender and receiver of a message use the same key for both encryption and decryption. However, how to distribute the symmetric key while keeping it secret becomes a problem to be solved. 


![](https://news.bitcoin.com/wp-content/uploads/2016/03/DiffHellCova.jpg){:height="200px" width="350px"}

Image: Whitfield Diffie(left) and Martin Hellman(right); They got the Turing Award in 2015 for their contributions


Diffie-Hellman key exchange method provides a solution. As the first practical public key exchange method, it is published by Ralph Merkle, Whitfield Diffie and Martin Hellman in 1976. By making full use of the computer's ability to calculate _modular exponents_ and its lack of efficient ways to solve _discrete logarithm problems_, the Diffie-Hellman key exchange enables two parties to exchange messages securely without knowing any additional information about each other in advance. It thus can be used to exchange symmetric keys for the following communication. 

![](https://www.practicalnetworking.net/wp-content/uploads/2015/11/dh-revised.png){:height="550px" width="650px"}

Image: An example of how Diffie-Hellman key exchange works


It is worth noticing that despite its secrecy against an eavesdropper of Internet traffic, it is vulnerable to _man-in-the-middle attack_. An adversary can impersonate one of the two parties of communications and get hold of all the messages exchanged. _Digital signatures_ attached are necessary when using the Diffie-Hellman protocol for authentication purposes.

[Source: Wikipedia page of _Diffie-Hellman key exchange_](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)\\
[Source: The image of a Rubik's Cube](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/17_layer_cube.png/800px-17_layer_cube.png)\\
[Source: _New Directions in Cryptography_ by Whitfield Diffie and Martin Hellman](https://www-ee.stanford.edu/~hellman/publications/24.pdf)\\
[Source: Photo of Diffie and hellman](https://news.bitcoin.com/diffie-hellman-2015-turing-award/)\\
[Source: A tutorial from _Practical Networking_](https://www.practicalnetworking.net/series/cryptography/diffie-hellman/)
