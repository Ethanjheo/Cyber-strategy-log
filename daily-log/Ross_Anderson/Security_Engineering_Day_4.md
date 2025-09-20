# Security Engineering – Day 4

## Book Info
- **Title:** Security Engineering  
- **Author:** Ross Anderson  
- **Publisher:** Wiley  
- **Date Studied:** 2025-09-20  

---

## 1. Core Concepts (Distributed Systems)

### Concurrency  
- When multiple nodes update data at the same time, consistency must be ensured.  
- Example: Preventing “double spending” in financial transactions.  
- Solution: Locks, transaction ordering, consensus algorithms.  

### Fault Tolerance  
- Distributed systems assume that some nodes may fail.  
- **Crash failure:** A server stops working.  
- **Byzantine failure:** A server gives incorrect or malicious responses.  
- Solution: Replication, quorum, Byzantine fault-tolerant protocols.  

### Naming  
- How systems identify resources (e.g., DNS, IP addresses).  
- Risks: Spoofing, naming conflicts, misdirection.  
- Solution: Secure naming with DNSSEC, PKI.  

---

## 2. Real-World Applications
- **Banking:** Preventing double spending and ensuring transaction order.  
- **Cloud services:** Replication and failover to ensure availability.  
- **Blockchain:** Consensus in untrusted environments (e.g., PBFT, PoS).  
- **DNS:** Protecting domain resolution with DNSSEC.  

---

## 3. Key Takeaways
- **Cryptography** secures communication, but it is not enough.  
- Distributed security requires handling concurrency, failures, and naming.  
- Security must ensure that all participants share the same “view of reality.”  

---

## My Reflection
One of the core truths in security is that achieving zero risk is impossible. Therefore, the key lies in learning how to distribute and manage risk effectively.

History shows that even the strongest security systems have collapsed due to technological advancements and human error. This is why the true goal of security is not absolute perfection, but rather reducing risk to the minimum and keeping it within a manageable range.
