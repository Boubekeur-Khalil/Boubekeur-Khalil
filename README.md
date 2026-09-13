<div align="center">

# Khalil Boubekeur

**Security Researcher | Bug Bounty Hunter**

[![YesWeHack](https://img.shields.io/badge/YesWeHack-Active%20Hunter-7B68EE?style=for-the-badge)](https://www.yeswehack.com/)
[![HackerOne](https://img.shields.io/badge/HackerOne-Active-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://www.hackerone.com/)

</div>

---

### About Me

Security researcher from Algeria, active since early 2026. I specialize in **chaining low-severity findings into critical exploit paths** across SSO/OAuth flows, API authorization layers, and server-side file handling.

I focus on private programs and consistently turn overlooked misconfigurations into high-impact chains.

---

### Career Stats

<div align="center">

| | |
|:---|:---|
| **Accepted Reports** | 70+ across multiple programs |
| **Highest CVSS** | 10.0 |
| **Longest Chain** | 6 vulnerabilities (outsider to RCE) |
| **Platforms** | YesWeHack, HackerOne |
| **Focus** | Private programs |

</div>

---

### Vulnerability Classes

```
SSO / OAuth ATO         nOAuth, multi-tenant MSAL, SAML manipulation, identity collision
API Authorization       Systemic ACL bypass, BOLA/IDOR, hidden endpoint discovery
Path Traversal & LFI    Directory traversal via metadata fields, secret/key exfiltration
Authentication Bypass   Reset token leakage, JWT key forgery, unauthenticated flows
RCE                     Unrestricted upload to webroot, chained file-write to execution
Recon & Surface Mapping JS bundle mining, OpenAPI spec analysis, CT logs, favicon pivoting
```

---

### Highlight: 6-Step Chain to RCE

> From a single private YesWeHack engagement. Escalated from **unauthenticated outsider** to **Remote Code Execution** through 6 chained vulnerabilities, producing 9 accepted reports including 3 Criticals.

```
[nOAuth ATO] --> [Reset Token Leak] --> [ACL Bypass] --> [LFI] --> [JWT Forgery] --> [RCE Upload]
  CVSS 9.1         CVSS 8.8            CVSS 8.3       CVSS 10.0                      CVSS 9.9
```

---

### Featured Project

#### [`vuln-chain-labs`](https://github.com/Boubekeur-Khalil/vuln-chain-labs)

[![Docker](https://img.shields.io/badge/Docker-Vulnerable%20Lab-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/Boubekeur-Khalil/vuln-chain-labs)
[![Labs](https://img.shields.io/badge/Challenges-7-critical?style=for-the-badge)](https://github.com/Boubekeur-Khalil/vuln-chain-labs)

7 Docker-based labs reproducing a real exploit chain from an authorized engagement. Each lab includes objectives, progressive hints, and full solution walkthroughs. Ships with an automated end-to-end exploit script.

---

### Tools & Tech

<div align="center">

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Caido](https://img.shields.io/badge/Caido-6C5CE7?style=flat-square)
![Nuclei](https://img.shields.io/badge/Nuclei-6236FF?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

</div>

---

<div align="center">

*Private program operator? I read your JS bundles before I touch a scanner.*

[![Email](https://img.shields.io/badge/Email-khalil.beckeur@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:khalil.beckeur@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-boubekeur--khalil.github.io-16a34a?style=flat-square)](https://boubekeur-khalil.github.io/portfolio/)

</div>
