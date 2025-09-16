# Security Engineering – Day 2

## Book Info
- **Title:** Security Engineering  
- **Author:** Ross Anderson  
- **Publisher:** Wiley  
- **Date Studied:** 2025-09-16  

---

## 1. Core Concepts
- **Symmetric Key Encryption**  
  - One key for both encryption and decryption.  
  - Fast and efficient but suffers from key distribution problems.  
  - *Example:* AES (current standard), DES (outdated, insecure).  

- **Public Key Encryption**  
  - Uses separate public and private keys.  
  - Solves key distribution but is computationally slower.  
  - *Example:* RSA (traditional), ECC (modern, efficient).  

- **Hash Functions**  
  - Transform input into fixed-length output.  
  - Irreversible; used for integrity checks.  
  - *Example:* SHA-256 (blockchain), MD5 & SHA-1 (broken due to collisions).  

- **Digital Signatures**  
  - Created with private key, verified with public key.  
  - Provide authentication (“who sent this?”) and integrity (“was it altered?”).  

---

## 2. Lessons
- Cryptography is only the foundation, not the entirety of security.  
- Most security failures come not from broken algorithms but from:  
  - Poor key management  
  - Flawed protocol design  
  - Human error and negligence  

---

## 3. Historical Cases
- **Enigma (WWII German cipher machine):**  
  Strong mathematically, but broken due to operator mistakes (key reuse, predictable patterns).  

- **MD5 & SHA-1:**  
  Retired after practical collision attacks made them unsafe for security use.  

---

## My Reflection

Cryptography forms the foundation of modern security systems, yet it cannot by itself guarantee complete protection. Algorithms such as AES, RSA, and ECC provide robust mathematical safeguards, but they cannot entirely eliminate real-world threats.  

First, as technology continues to advance, new forms of attack inevitably emerge. A notable historical case is the German **Enigma** cipher machine during World War II. Despite representing the cutting-edge technology of its time, it was eventually broken due to Allied decryption efforts and operational errors. This illustrates that no cipher can remain absolute in the face of evolving techniques and contextual vulnerabilities.  

Second, humans are inherently irrational. This is highlighted in **Prospect Theory (1979)**, developed by **Daniel Kahneman** and **Amos Tversky**. Their research demonstrates that individuals respond more strongly to potential losses than to equivalent gains (*loss aversion*), making it unrealistic to expect perfectly rational adherence to security practices. Instead of attempting to fully correct human psychology, it is more effective to design structural and institutional frameworks that naturally guide individuals toward safer behaviors.  

In conclusion, security can never be 100% flawless. Only by integrating technological progress with social, cultural, and institutional contexts can security systems achieve both legitimacy and effectiveness.  

## Reference
- Daniel Kahneman & Amos Tversky (1979), Prospect Theory: An Analysis of Decision under Risk, Econometrica.
