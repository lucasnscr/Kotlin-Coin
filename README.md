# Kotlin-Coin

## Theory ##

Blockchain is made of a list of blocks where each block has its own hash, previous or parent block hash and an auxiliary data like timestamp and, for example, a list of transactions included in that block. Essentially one block captures system’s state at particular moment.

![Blockchain](https://github.com/lucasnscr/Kotlin-Coin/blob/main/1_Ln0zuMCaf71iwmO3PcEqmw.png?raw=true)

## Hash utils ##
Blockhains use special types of hashes which are called cryptographic hashes. Bitcoin uses SHA-256 and we’re going to use the same. The actual implementation is done as Extension Function to the existing String class.

## Blocks ##
It’s easy to model blocks using Data Classes. They generate all java boilerplate and enforce immutability during compile time. mentioned before hash includes previousHash, data, which is empty in our case and the timestamp. Bitcoin has a very similar structure with some other extra fields, which we can ignore for now.

## Blockhain ##
So far we only created blocks, let’s add a container to store them — Blockchain.

## Mining ##
Right now there’s no limit on how many and how fast we can add blocks to Blockchain. In a centralized system the central authority controls that process, but since we’re dealing with a distributed system we can’t afford that.
As it turned out to be the problem isn’t new and your Inbox is dealing with it every day in the form of spam: a lot of spammers want to write (send) to you.

## Conclusion ##
Now, finish all the process we can understand a little about blockchaing and implement one cryptocurrency
