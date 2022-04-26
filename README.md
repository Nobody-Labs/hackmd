# Verifiable Merkle Trees
Verifiable Merkle Trees are a blockchain efficient implementation of an updateable merkle tree. VMTs are possible because zero knowledge proofs (zkps) are easier to verify than compute, therefore it's possible to perform an expensive computation off-chain and perform a relatively cheaper computation on-chain that proves a result is valid according to the constraints of the zk circuit.

![vmt cubes](https://raw.githubusercontent.com/Nobody-Labs/hackmd/main/vmt.png)