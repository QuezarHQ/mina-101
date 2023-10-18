# What are Zero Knowledge Proofs?

*   ELI5 version

    * Imagine you have a secret password, and you want to prove to someone that you know it without actually revealing what the password is. That's where zero-knowledge proofs come in.
    * In a zero-knowledge proof, you demonstrate your knowledge of the password without actually telling the other person the password. You do this by performing a series of actions or calculations that show you have the correct password, but you don't reveal the password itself.
    * So, zero-knowledge proofs allow you to prove something without giving away the actual information, which is important for privacy and security in various digital applications, like verifying your identity without exposing sensitive data.


*   Technical version

    * Zero-knowledge proofs are cryptographic techniques used to prove the truth of a statement without revealing any details about the statement itself.&#x20;
    *   Imagine you want to prove to someone that you have a particular piece of information, like a password or a secret key. With a zero-knowledge proof, you can demonstrate that you possess this information without actually disclosing the information itself.

        You achieve this by engaging in a kind of cryptographic back-and-forth with the verifier. You perform a series of operations or computations that involve the secret information, and each step convinces the verifier that you know the secret. However, at no point during this process do you reveal the secret directly.
    * This is useful in various applications, such as authentication or verification processes. For example, in a password-based system, you could prove your identity to a server without transmitting your actual password over the internet. This adds an extra layer of security by reducing the risk of your password being intercepted or exposed.


* Reference videos
  * Simple explainer of ZKPs & ZK-SNARKs by Mina - [https://www.youtube.com/watch?v=GvwYJDzzI-g](https://www.youtube.com/watch?v=GvwYJDzzI-g)
  * Slighly more technical explainer with real world examples - [https://www.youtube.com/watch?v=OcmvMs4AMbM](https://www.youtube.com/watch?v=OcmvMs4AMbM)
  * ZK explained in 5 levels of difficulties - [https://www.youtube.com/watch?v=fOGdb1CTu5c](https://www.youtube.com/watch?v=fOGdb1CTu5c)
