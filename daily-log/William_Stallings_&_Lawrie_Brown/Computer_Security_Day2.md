# Computer Security: Principles and Practice – Day 2

## Book Info
- **Title:** Computer Security: Principles and Practice  
- **Authors:** William Stallings & Lawrie Brown  
- **Publisher:** Pearson  
- **Date Studied:** 2025-10-02  

---

## 1) Core Topic – Security Policies & Models

### Security Policies
- Define what is allowed and not allowed within an information system.  
- Establish the **rules for confidentiality, integrity, and availability**.  
- Example: *Only system administrators may install software on company devices.*  

### Security Models
- **Bell-LaPadula Model (BLP):**  
  - Focus: **Confidentiality**  
  - Rules: *No Read Up* (cannot read higher classification) / *No Write Down* (cannot leak secrets)  

- **Biba Model:**  
  - Focus: **Integrity**  
  - Rules: *No Write Up* (cannot corrupt higher data) / *No Read Down* (cannot read lower-quality data)  

- **Clark-Wilson Model:**  
  - Focus: **Well-formed transactions** and **separation of duties**  
  - Application: Banking systems, fraud prevention  

---

## 2) Key Concepts
- **Security Policy:** Abstract rules (what is permitted or forbidden).  
- **Security Model:** Formal representation of policy (logical or mathematical).  
- **Trusted System:** A system that reliably enforces the security policy.  

---

## 3) Real-World Examples
- **Bell-LaPadula:** Military classified systems (Top Secret → Secret → Confidential).  
- **Biba:** Medical databases ensuring accurate patient data.  
- **Clark-Wilson:** Financial transactions requiring two-person control.  

---

## 4) Study Activity
1. Choose a recent security breach (e.g., healthcare data leak, bank fraud).  
   - Classify: Was it a **Confidentiality**, **Integrity**, or **Availability** issue?  
   - Which model (BLP, Biba, Clark-Wilson) could have reduced the risk?  

2. Write short notes comparing:  
   - **Policy vs Model vs Mechanism**  
   - (Rules vs Representation vs Implementation)  

---
