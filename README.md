# Solrand

Solrand is a decentralized random number generator service based on the Solana blockchain. It provides a fully verifiable RNG for applications such as games, casinos, lotteries, and more.
 
Solrand takes the Solana block hash as input for a verifiable delay function, and then uses the output to generate a random number sequence. The reason for using a VDF is to prevent the leader node from being able to control the random number through changing the block hash.
