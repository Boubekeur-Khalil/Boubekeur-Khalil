# Hey, I'm Khalil

Security researcher & full-stack developer from Algeria.

I hunt bugs on private programs and build the tools I wish I had.

## What I do

**Bug Bounty** — I specialize in chaining low-severity findings into critical exploit paths. My methodology focuses on SSO misconfigurations, API authorization gaps, and server-side file handling flaws.

**Engagement highlight:** Discovered a 6-step chain escalating from unauthenticated outsider to Remote Code Execution on a private program — nOAuth ATO, leaked reset tokens, systemic ACL bypass, path traversal LFI, JWT key theft, and unrestricted file upload to webroot. Produced 9 accepted reports (3 Critical, 2 High, 4 Medium) from a single target.

**Development** — Android (Kotlin/Dart), React, Django, Python tooling. I like building things that solve real problems, not boilerplate.

## Bug Bounty Stats

```
Findings submitted    9 accepted (1 engagement)
Severity breakdown    3 Critical  |  2 High  |  4 Medium
Highest CVSS          10.0 (path traversal → arbitrary file read)
Longest chain         6 steps (outsider → RCE)
Platform              YesWeHack (private programs)
```

## Vulnerability Classes I Hunt

| Class | Technique |
|-------|-----------|
| **SSO/OAuth ATO** | nOAuth (multi-tenant MSAL + mutable Graph mail attribute), SAML assertion manipulation |
| **API Authorization** | Systemic write ACL bypass (POST blocked, PUT/PATCH/DELETE open), BOLA/IDOR on collection endpoints |
| **File Handling** | Path traversal via writable metadata fields, unrestricted upload to webroot |
| **Authentication** | Password reset token leakage, unauthenticated reset endpoints, JWT key theft + forgery |
| **Recon** | JS bundle mining, OpenAPI spec analysis, CT log expansion, favicon hash pivoting |

## Featured Project

### [vuln-chain-labs](https://github.com/Boubekeur-Khalil/vuln-chain-labs)

A deliberately vulnerable Docker lab that reproduces a real exploit chain I discovered during an authorized engagement. 7 challenges that walk you through every step from zero access to RCE.

```
[nOAuth ATO] → [Reset Token Leak] → [ACL Bypass] → [Path Traversal LFI]
    → [JWT Forgery] → [PHP Upload to Webroot] → [Remote Code Execution]
```

Each lab has objectives, hints, and full solution walkthroughs with curl commands. Includes an automated end-to-end exploit script.

## Tech & Tools

**Languages:** Python, PHP, Bash, TypeScript, Kotlin, Dart, C

**Security:** Burp Suite, curl, Caido, Nuclei, Subfinder, httpx, Amass, ffuf, interactsh

**Dev:** React, Django, Angular, Symfony, Docker, Git

**Platforms:** YesWeHack, HackerOne

## Currently

- Hunting on private bug bounty programs
- Building security tooling and vulnerable labs
- Expanding into cloud security and mobile app testing

## Contact

If you run a private program and want someone who reads your JS bundles before touching a scanner — let's talk.
