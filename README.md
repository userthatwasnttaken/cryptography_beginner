# About this Repo

## Learning with Errors

The computational hardness of the LWE problem is a crucial property for its use in cryptography. It is believed to be quantum-resistant, meaning that even powerful quantum computers would not be able to solve it efficiently.

This makes LWE a leading candidate for building cryptographic systems, and in fact is used in the WOTS+ system of encryption that is used in KYBER standard more broadly, which has been recently approved to be used as a Post-Quantum Cryptographic method.

Learning with errors poses a way that we can create a secret key, and with this, use this information to publish a key that contains the location to a point close to, say, Alice’s real point. If we consider the lattice shown above in Figure 5, it is very clear that each point in the lattice is accessible by Alice by using her basis vectors [7].

### But what about a point that is near her lattice?

First of all, we note: the real points on her lattice are established from the basis vectors that she used to create the lattice. There is no way of knowing what basis vectors were use to create those points as there are many that could have created it, but, Bob has access to (many) equations that are listed as being solvable under the conditions of this basis vectors. He can use this information, as well as the point, that Alice pub- lishes, to find the ”closest point” [7, 10].

### References

7] Jean-Philippe Aumasson, Serious Cryptography, 2nd Edition, ”A Practical Introduction to Modern Encryption” August 2024, ISBN-13: 9781718503847 

[8] Algorithms for the Closest and Shortest Vector Problems, Mathematics of University of Auckland, https://www.math.auckland.ac.nz/ sgal018/crypto-book/ch18.pdf

[9] Advanced Topics in Cryptography: Lattices, Vinod Vaikuntanathan, Computational Problems, Online, Available: https://people.csail.mit.edu/vinodv/6876-Fall2015/L3.pdf

[10] University of San Diego, CSE 206A: Lattice Algorithms and Applications, Daniele Micciancio, https://cseweb.ucsd.edu/classes/wi12/cse206A-a/lec3.pd
