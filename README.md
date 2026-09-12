<div align="center">

# Khalil Boubekeur

**Security Researcher | Bug Bounty Hunter | Full-Stack Developer**

[![YesWeHack](https://img.shields.io/badge/YesWeHack-Private%20Programs-7B68EE?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQyIDAtOC0zLjU4LTgtOHMzLjU4LTggOC04IDggMy41OCA4IDgtMy41OCA4LTggOHoiLz48L3N2Zz4=)](https://www.yeswehack.com/)
[![HackerOne](https://img.shields.io/badge/HackerOne-Active-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://www.hackerone.com/)

*I hunt bugs on private programs and build the tools I wish I had.*

</div>

---

### About Me

Security researcher from Algeria. I specialize in **chaining low-severity findings into critical exploit paths** - SSO misconfigurations, API authorization gaps, and server-side file handling flaws.

I also build things: Android apps (Kotlin/Dart), web platforms (React, Django, Angular), and security tooling in Python.

---

### Highlight: 6-Step Chain to RCE

> Discovered on a private YesWeHack program. Escalated from **unauthenticated outsider** to **Remote Code Execution** through a chain of 6 vulnerabilities, producing **9 accepted reports** from a single target.

```
  Outsider                                                            RCE
     |                                                                 |
     v                                                                 v
[nOAuth ATO] --> [Reset Token Leak] --> [ACL Bypass] --> [LFI] --> [JWT Forgery] --> [PHP Upload]
  CVSS 9.1         CVSS 8.8            CVSS 8.3       CVSS 10.0                      CVSS 9.9
```

---

### Bug Bounty Stats

<div align="center">

| | |
|:---|:---|
| **Findings** | 9 accepted (3 Critical, 2 High, 4 Medium) |
| **Highest CVSS** | 10.0 - Path traversal to arbitrary file read |
| **Longest chain** | 6 steps (outsider to RCE) |
| **Reward** | First engagement, first payout |
| **Platform** | YesWeHack (private programs) |

</div>

---

### Vulnerability Classes

```
SSO / OAuth ATO         nOAuth, multi-tenant MSAL, mutable Graph attributes, SAML manipulation
API Authorization       Systemic ACL bypass (POST blocked, PUT/PATCH/DELETE open), BOLA, IDOR
File Handling           Path traversal via writable metadata, unrestricted upload to webroot
Authentication          Reset token leakage, unauthenticated reset endpoints, JWT key forgery
Recon                   JS bundle mining, OpenAPI spec analysis, CT logs, favicon hash pivoting
```

---

### Featured Project

### [`vuln-chain-labs`](https://github.com/Boubekeur-Khalil/vuln-chain-labs)

[![Lab](https://img.shields.io/badge/Docker-Vulnerable%20Lab-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/Boubekeur-Khalil/vuln-chain-labs)
[![Labs](https://img.shields.io/badge/Challenges-7-critical?style=for-the-badge)](https://github.com/Boubekeur-Khalil/vuln-chain-labs)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://github.com/Boubekeur-Khalil/vuln-chain-labs/blob/master/LICENSE)

**7 Docker-based labs** reproducing the full exploit chain from an authorized engagement. Each lab includes objectives, progressive hints, and complete solution walkthroughs with curl commands. Ships with an automated end-to-end exploit script.

---

### Tech & Tools

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Caido](https://img.shields.io/badge/Caido-6C5CE7?style=flat-square)
![Nuclei](https://img.shields.io/badge/Nuclei-6236FF?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)

</div>

---

### Currently

- Hunting on private bug bounty programs
- Building security tooling and vulnerable labs
- Expanding into cloud security and mobile app testing

---

<div align="center">

*If you run a private program and want someone who reads your JS bundles before touching a scanner - let's talk.*

[![Email](https://img.shields.io/badge/Email-khalil.beckeur@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:khalil.beckeur@gmail.com)

</div>
