## Written Responses

1. Describe the general process of how blocks are added to a blockchain.

A block is added to a blockchain when a miner provides a valid proof. In cases such as "proof of work" the miner can provide a valid proof by doing some computational work. This work consists of solving some puzzle -- like performing a hash over and over again using the proof of the last block in the chain, until it satisfies some rule (such as leading with 6 zeroes). Because the solution can easily be checked by inputting the proof into the same hashing algorithm, it can be verified quickly by other parties. Once it is verified, we can trust that this is a legitimate transaction. We know this because other parties are verifying it when the true last proof which depends on all of the blocks before it. Therefore, one proof can encapsulate an entire history of hours of work. If it was wrong it would be that some block somewhere in the chain had been altered and we would know not to trust it.  

2. How can blockchain users mine coins?

This is answered above. When the miner provides a correct solution they are awarded a coin.

3. Explain how simulations like Conway's Game of Life can be used in real-world applications.

Basically any evolving program that begins with a genesis state can be considered an application of cellular automation. One could say Blockchain is a type of cellular automation if each block was considered a cell. Another application is public-key cryptography, where a one-way function is given a rule to calculate future states yet is very difficult to calculate previous states. Another example is music. Chord progression could evolve using some rule given an initial chord.