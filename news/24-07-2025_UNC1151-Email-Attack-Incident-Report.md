# UNC1151 Roundcube XSS Exploit – Summary

##  Source  
**CERT Polska** – [Post link](https://cert.pl/en/posts/2025/06/unc1151-campaign-roundcube/)  
**Date:** June 5, 2025  

---

##  Attack Summary  
- **Group:** UNC1151 (Belarus-linked APT)  
- **Target:** Polish institutions using Roundcube webmail  
- **Method:** CVE-2024-42009 (XSS) → Email opened → JS auto-runs → Service Worker installed → Credentials stolen  

---

##  Key Terms  
- **XSS:** Cross-site scripting vulnerability  
- **Service Worker:** Background JS that intercepts data  
- **Spearphishing:** Targeted phishing emails  

---

##  Defense Tips  
- Update Roundcube (v1.5.10 / 1.6.11+)  
- Disable HTML email if possible  
- Sanitize mail content  
- Train users  
- Implement layered email security  

---

##  Reflection  
It is difficult to attribute this solely to individual negligence. However, for the survival and continuity of the organization, assigning responsibility becomes inevitable. From a management perspective, overhauling existing systems can be financially burdensome and practically disruptive. Therefore, clear boundaries of accountability must be established in advance—through user training, well-defined system ownership, evaluation of technical limitations, and acknowledgment of habitual behaviors. Anticipating risk and codifying responses before incidents occur is essential for resilient governance.
