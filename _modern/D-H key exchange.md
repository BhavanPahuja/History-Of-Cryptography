---
title: Diffie-Hellman key exchange - the first public key protocol
start: 1976
order: 2
---


Imaging solving a Rubic's cube of 3 X 3 cubies per face. Is it hard for you? If not, what about solving one with 128 cubies per face? Do you think that can be done by any human being? Meanwhile, scrambling a Rubik's cube of 128 cubies per face can be an easy job even for a 3-year-old kid, which is precisely the essence of Diffie-Hallman key exchange, and subsequently, the public key cryptosystem. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/17_layer_cube.png/800px-17_layer_cube.png){:height="230px" width="250px"}

Image: A Rubic's cube

Before public-key cryptography was developed, all the cryptosystems used symmetrical keys, which means that the sender and receiver of a message use the same key for both encryption and decryption. However, how to distribute the asymmetric key while keeping it secret becomes a problem to be solved. 


![](https://i.guim.co.uk/img/media/a09cc0d2b842c5eade7383d156e4c5e43cdaf6df/0_40_2184_1310/master/2184.jpg?width=1200&height=900&quality=85&auto=format&fit=crop&s=10c5122e750e8fb9053b31f13f46fd19){:height="200px" width="350px"}

Image: Whitfield Diffie(left) and Martin Hellman(right); They got the Turing Award in 2015 for their contributions 39 years ago

Diffie-Hellman key exchange method provides a solution. As the first practical public key exchange method, it is published by Ralph Merkle, Whitfield Diffie and Martin Hellman in 1976. By making full use of the computer's ability to calculate modular exponents and its lack of efficient ways to solve discrete logarithm problems, the D-H key exchange enables two parties to exchange messages securely without knowing any additional information about each other in advance. It thus can be used to exchange symmetric keys for the following communication. 

![](https://4.bp.blogspot.com/-kgA2N3UK8O0/WyVhWZBf5GI/AAAAAAAAJeA/gSASn5x6WAkuq-1Az3L9U75RkdLOW9XLQCLcBGAs/s1600/diffie%2Bhellman%2Bkey%2Bexchange%2Balgorithm%2Btechblogmu.png){:height="200px" width="350px"}

Image: The mechanism of Diffie-Hellman Key Exchange

It is worth noticing that despite its secrecy against an eavesdropper of Internet traffic, it is vulnerable to man-in-the-middle attack. An adversary can impersonate one of the two parties of communications with their own fake keys. Digital signatures attached are necessary when using the D-H protocol for authentication purposes.

[Source: Wikipedia](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)\\
[Source: The picture of a Rubic's cube](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/17_layer_cube.png/800px-17_layer_cube.png)\\
[Source: New Directions in Cryptography by Whitfield Diffie and Martin Hellman](https://www-ee.stanford.edu/~hellman/publications/24.pdf)\\
[Source: A news report from The Guardian](https://www.theguardian.com/science/2016/mar/01/turing-award-whitfield-diffie-martin-hellman-online-commerce)\\
[Source: TechBlogMU](https://techblogmu.blogspot.com/2018/06/diffie-hellman-key-exchange-algorithm.html)
