# Security Engineering – Day 3

## Book Info
- **Title:** Security Engineering  
- **Author:** Ross Anderson  
- **Publisher:** Wiley  
- **Date Studied:** 2025-09-17  

---

## 1. Review of Cryptography (Day 2 Recap)
- **Symmetric Key Encryption (AES, DES)**  
  - Uses the same key for encryption and decryption.  
  - Very fast, but vulnerable to key distribution problems.  

- **Public Key Encryption (RSA, ECC)**  
  - Uses a key pair: public key (openly shared) and private key (kept secret).  
  - Solves key distribution issues, but slower than symmetric encryption.  

- **Hash Functions (SHA-256, etc.)**  
  - Convert any input into a fixed-length output (like a fingerprint).  
  - Used for integrity verification — changes in data produce completely different hashes.  

- **Digital Signatures**  
  - Private key is used to sign, public key is used to verify.  
  - Proves authenticity (“who sent it”) and integrity (“not tampered”).  

---

## 2. Access Control Models
Security is not only about locking data (cryptography) but also deciding **who is allowed to access what**.  

1. **ACL (Access Control List)**  
   - Permission is listed per user.  
   - Example: User A = read only, User B = read/write, User C = denied.  

2. **RBAC (Role-Based Access Control)**  
   - Permissions are assigned by role rather than individuals.  
   - Example: “HR role” can read employee data but not change salary info.  

3. **DAC (Discretionary Access Control)**  
   - The data owner decides who can access the resource.  
   - Example: If I create a file, I can allow or deny access at my discretion.  

4. **MAC (Mandatory Access Control)**  
   - Access is decided by system-enforced rules that cannot be changed by users.  
   - Example: Military classification (Top Secret, Secret, Confidential).  

---

## 3. Real-World Applications
- **Banking Systems**  
  - Cryptography secures communication (AES, RSA, TLS).  
  - Access Control ensures customers only view their own accounts.  

- **Corporate IT Systems**  
  - Cryptography protects data transfer.  
  - Access Control ensures each department (HR, Dev, Marketing) has different levels of access.  

---

## 4. Key Takeaways
- **Cryptography** = the lock on the door (protecting data).  
- **Access Control** = deciding who holds the keys and which rooms they can enter.  
- Both are required for a secure system.  

---

## My Reflection
Cryptography is structured in diverse forms to maintain security, and it is crucial to select the appropriate method depending on the specific domain and use case.

Beyond this, I have learned that cryptography is not an independent or flawless solution. Even the strongest algorithms such as AES, RSA, or ECC can fail if applied in the wrong context or if key management is neglected.

Therefore, the combination of proper algorithm selection, secure operational practices, and clear access control policies is essential to ensure practical security. Access control models (ACL, RBAC, DAC, MAC) are particularly important, as they determine “who is permitted to unlock the system”, extending beyond the cryptographic layer itself.

In conclusion, security is not merely a matter of technical implementation but rather a comprehensive system intertwined with organizational structures, human behavior, and institutional rules. Moving forward, I realize the importance of developing the ability to judge “which approach is most appropriate for which situation”, rather than focusing solely on the technical strength of cryptography.
