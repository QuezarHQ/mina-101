# Outline

*   What are zk proofs?

    * Elaborate on - They let you prove that you have certain information or knowledge without actually revealing what that information is
    * Find waldo example


*   Why are they important? What problems do they solve?

    * Privacy & Security
      * Financial data security
    * Blockchain scaling solutions
    * Identity solutions & authentication layers


*   How do they work?

    * The concept of&#x20;
      * prover
      * verifier
      * zero knowledge
    * Underlying cryptography & mathematical probablities


* What are SNARKS & STARKS? What's the difference?
  * SNARKS - **Succinct Non-Interactive Argument of Knowledge**
  * STARKS - **Scalable Transparent Argument of Knowledge**
  * Difference
    * STARKs are designed to be highly scalable. They can handle a large number of computational steps in the proof generation process, making them suitable for more complex computations.
    * Unlike traditional SNARKs with a trusted setup, STARKs are designed to be transparent. They do not rely on a trusted setup phase, which can make them more resilient to certain security risks.
    * While STARKs are scalable and secure, their verification process can be more computationally intensive compared to SNARKs. This means that while generating STARK proofs can be efficient, verifying those proofs may require more computational resources.



* What are zkVMs & zkEVMs? How are they different from each other?
  * zkVMs - a virtual machine that runs on a blockchain or a distributed ledger. It leverages zero-knowledge proofs to execute smart contracts with enhanced privacy and confidentiality.
  * zkEVM - zkEVM is a specific application of zkVM technology in the context of the Ethereum blockchain
  * Differences
    * Scope of application - zkVM can be applied on any blockchain, but zkEVM need to be compatible with Ethereum
    * Use cases - zkVM can be used for a wide range of use cases beyond Ethereum, wherever privacy and zero-knowledge proofs are needed in smart contract execution. zkEVM is primarily intended to provide privacy and efficiency improvements for Ethereum smart contracts
