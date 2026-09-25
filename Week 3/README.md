# 🟩 B083-NETWORKWALKS

## 🟪 PASSWORD CRACKING REPORT

---

### 🟢 PHASE 01 — PASSWORD CRACKING WITH JOHN THE RIPPER
**Tool:** `JOHN THE RIPPER`
**Objective:** Crack an authorized and protected PDF file using JTR and JOHNNY.

---

### 🔵 PHASE 02 — PASSWORD CRACKING WITH NETWORKWALKS
**Tool:** `NETWORKWALKS IN-HOUSE TOOLS`
**Objective:** Crack an authorized and protected PDF file using NETWORKWALKS tools.

---

### 🟠 PHASE 03 — AI BASED PASSWORD CRACKING
**Tool:** `CLAUDE + HEXSTRIKE MCP + JOHN THE RIPPER`
**Objective:** Use the AI-based setup to crack the password and capture the flag of a PDF file.

---

## 🟠 Bonus Phase — MEDIROZA HOSPITAL PENTEST
**Tool:** `VARIOUS PENTESTING TOOLS`
**Objective:** Fully conduct a web application penetration test on an authorized hospital website.
**Path to Project:**

---

## 📋 ENGAGEMENT DETAILS

| Field | Value |
|---|---|
| 🟢 **Status** | `AUTHORIZED` |
| 🔵 **Target** | `networkwalks' PDF files` |
| 🟣 **Date** | `23 SEPTEMBER 2026` |

---

> ⚠️ *This report documents an authorized security assessment conducted strictly within the defined scope and rules of engagement.*
`IMPORTANT — LEGAL AND ETHICAL USE ONLY`



---

## 📋 W2-PM3-FINAL | CYBERSECURITY | NETWORKWALKS

### Engagement Information

| **Item** | **Information** |
|---|---|
| **Analyst / Pentester** | Safwan Abdurahiman Kavil |
| **Role / Title** | Cybersecurity Intern |
| **Engagement Name** | B083-Networkwalks |
| **Client / Target Scope** | `networkwalks' PDF files`|
| **Authorization on File** | Yes — Approval secured from `networkwalks.com` |
| **Report Date** | 23 September 2026 |

### Assessment Scope

| **Category** | **Details** |
|---|---|
| **Password Cracking Base Tool** | John The Ripper |
| **Password Cracking GUI** | Johnny |
| **Password Cracking Agent** | Hexstrike MCP |
| **AI Tool** | Claude |
| **Phase 1** | PASSWORD CRACKING WITH JOHN THE RIPPER |
| **Phase 2** | PASSWORD CRACKING WITH NETWORKWALKS |
| **Phase 3** | AI BASED PASSWORD CRACKING|
---

## 🗂 Report Index

1. [Authorization & Liability Disclaimer](#s1)
2. [Executive Summary](#s2)
3. [Scope & Objectives](#s3)
4. [Methodology & Tools Used](#s4)
5. [Activities Performed](#s5)
   - [5.1 Password Cracking with John the Ripper](#51-password-cracking-with-john-the-ripper)
   - [5.2 NetworkWalks Cracking Tools](#52-networkwalks-cracking-tools)
   - [5.3 AI Based Password Cracking](#53-ai-based-password-cracking)
6. [Findings & Risk Analysis](#s6)
7. [Recommendations](#s7)
8. [Conclusion](#s8)
9. [Evidence & Appendix](#s9)
10. [Author & Project Information](#s10)

---

<a id="s1"></a>
## `[ SECTION 01 ]` Authorization & Liability Disclaimer

This assessment was performed only against systems and assets for which written authorization was obtained — specifically **networkwalks.com** , **my own Home Lab** — and/or systems and devices that I own myself.

All activities described in this report are conducted for authorized security assessment, education and research purposes only. Nothing in this document should be used to access, scan or test any system without explicit written permission from its owner. Every action taken is the responsibility of the person performing it. Misuse of these techniques may result in criminal charges, civil liability, loss of employment and a permanent record. In most jurisdictions, unauthorized access to a computer system is a crime even when no damage occurs.


---

<a id="s2"></a>
## `[ SECTION 02 ]` Executive Summary

An authorized password-cracking assessment was conducted against three protected networkwalks PDF files using three distinct methods: John the Ripper (JTR), NetworkWalks' in-house hash/password cracking tools, and an AI-driven setup combining Claude, Hexstrike MCP, and JTR.

All three PDF files were cracked successfully, and in every case the password was recovered **instantly** — indicating each password was weak, short, and/or drawn from a common dictionary/wordlist. This held true regardless of method: the manual JTR approach, the in-house tooling, and the autonomous AI-agent approach all achieved the same trivial outcome, with the AI-based method additionally demonstrating that password recovery can now be fully automated end-to-end with no manual cracking expertise required.

Overall, the assessment found that the core risk lies not in any single tool's capability, but in **weak password practices** applied to the protected files themselves. The consistent, near-instant success across all three methods — including a fully autonomous AI agent — indicates that current password strength on these files provides negligible real-world protection. Remediation should focus on enforcing strong password policy for protected documents, rather than on the cracking tools or methods used to test them.



---

<a id="s3"></a>
## `[ SECTION 03 ]` Scope & Objectives

**Objectives**
- ▸ Crack an authorized and protected PDF file using JTR and JOHNNY.
- ▸ Crack an authorized and protected PDF file using NETWORKWALKS tools.
- ▸ Use the AI-based setup to crack the password and capture the flag of a PDF file.

**In Scope**

networkwalks' PDF Files


**Out of Scope**
networkwalks.com
Web Applications
Web Servers
Other Networks (WAN, Internet)

**Constraints / Rules of Engagement**

Only allowed to crack PDF files under explicit authorization from networkwalks.com.
Cracking will be isolated within a possible VM machine network.

---

<a id="s4"></a>
## `[ SECTION 04 ]` Methodology & Tools Used

The table below lists each tool used during this engagement and its purpose.

| Tool | Purpose |
|---|---|
| **John The Ripper** | John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong passwords are. |
| **NetworkWalks Cracking Tools** | A Hash Calculator to take the hash out of a locked PDF file. Then, a Password Cracker to find the real password from that hash. |
| **Hexstrike MCP** | Advanced AI-powered penetration testing MCP framework consisting of security tools and autonomous AI agents |
| **Claude AI** | AI Agent overlay connected to Hexstrike server for autonomous operations and analysis |



---

<a id="s5"></a>
## `[ SECTION 05 ]` Activities Performed

### 5.1 Password Cracking with John the Ripper

- ▸ Target: My Locked PDF1.pdf
- ▸ Password cracked?: Yes
- ▸ Flag Acquired: nw{cybersecurity_flag_captured_2608}
- ▸ Notable details: A simple flag was captured

### 5.2 NetworkWalks Cracking Tools

- ▸ Target: My Locked PDF2.pdf
- ▸ Password cracked?: Yes
- ▸ Flag Acquired: nw{networkwalks_persistence_jtr_270521}
- ▸ Notable details: A simple flag was captured once again

### 5.3 AI Based Password Cracking

- ▸ Target: My Locked PDF3.pdf
- ▸ Password cracked?: Yes
- ▸ Flag Acquired: nw{networkwalks_flag_260821_1}
- ▸ Notable details: A simple flag was captured again
---

<a id="s6"></a>
## `[ SECTION 06 ]` Findings & Risk Analysis

Based on the three password cracking activities, the following potential risks were identified.

## 🔒 Password Cracking with John the Ripper

**Scope:** My Locked PDF1.pdf

| # | Finding | Evidence / Observation | Potential Impact | Risk |
|---|---|---|---|---|
| 1 | **Password Cracked Easily** | Was able to crack the password instantly using John and the password was basic. | Potential for risk of unauthorized access. | 🟠 **High** |

**Risk level key:** 🔴 Critical &nbsp;&nbsp; 🟠 High &nbsp;&nbsp; 🟡 Medium &nbsp;&nbsp; 🟢 Low

## 🔒 NetworkWalks Cracking Tools

**Scope:** My Locked PDF2.pdf

| # | Finding | Evidence / Observation | Potential Impact | Risk |
|---|---|---|---|---|
| 1 | **Password Cracked Very Easily** | Was able to crack the password instantly using John and the password was very basic. | Potential for risk of easy unauthorized access. | 🟠 **High** |

---
**Risk level key:** 🔴 Critical &nbsp;&nbsp; 🟠 High &nbsp;&nbsp; 🟡 Medium &nbsp;&nbsp; 🟢 Low

## 🔒 AI Based Password Cracking

**Scope:** My Locked PDF3.pdf

| # | Finding | Evidence / Observation | Potential Impact | Risk |
|---|---|---|---|---|
| 1 | **Password Cracked Very Easily with AI** | Was able to crack the password instantly using John and the password was very basic. | Potential for risk of easy unauthorized access using dictionary attacks. | 🟠 **High** |

---
**Risk level key:** 🔴 Critical &nbsp;&nbsp; 🟠 High &nbsp;&nbsp; 🟡 Medium &nbsp;&nbsp; 🟢 Low

***These findings are just basic observations after password cracking. No exploitation was performed as part of this engagement unless explicitly stated above. Further authorized pentesting would be required to confirm actual exploitability.***

---

<a id="s7"></a>
## `[ SECTION 07 ]` Recommendations

| # | Finding Addressed | Recommendation |
|---|---|---|
| 1 | Password cracked instantly via John the Ripper (PDF1) | Enforce a minimum password policy (12+ characters, mixed case, numbers, symbols) for all protected PDF files; avoid dictionary words or predictable patterns. |
| 2 | Password cracked very easily via NetworkWalks tools (PDF2) | Treat in-house cracking tool availability as a signal — periodically test internal document passwords against the same tooling to catch weak passwords before an attacker does. |
| 3 | Password cracked instantly via AI-based (Claude + Hexstrike MCP + JTR) automation (PDF3) | Recognize that AI-assisted cracking lowers the skill barrier significantly; weak passwords are no longer a defense even against non-expert attackers. Prioritize passphrase-based or password-manager-generated credentials over human-memorable passwords. |
| 4 | Overall pattern across all three tests | Where document sensitivity warrants it, use document encryption backed by strong, randomly generated passwords (or key-based protection) rather than relying on PDF password protection alone, as PDF password schemes are well-supported by cracking tools. |


---


<a id="s8"></a>
## `[ SECTION 08 ]` Conclusion

This engagement tested password protection on three networkwalks PDF files using three progressively different approaches: manual cracking with John the Ripper, NetworkWalks' in-house hash/password cracking tools, and a fully autonomous AI-driven setup (Claude + Hexstrike MCP + JTR). All three files were cracked, and in every case the password was recovered near-instantly, confirming that weak, guessable passwords were in use across all tested documents.

The key takeaway is that the **cracking method mattered less than the password strength itself** — even the most basic tool succeeded as quickly as the AI-driven automated agent, showing that current password practices offer little to no real protection against any of the tested approaches. The AI-based phase in particular highlights an evolving risk: autonomous agents can now perform end-to-end password recovery with minimal human input, meaning weak passwords are exploitable even by attackers without deep technical expertise.

All activity in this report was performed strictly within the scope authorized by networkwalks.com, against files owned/provided for this authorized assessment. No exploitation was conducted beyond the password-cracking activities explicitly documented above.


---

<a id="s9"></a>
## `[ SECTION 09 ]` Evidence & Appendix

### 📷 JTR Cracking

| Screenshot |
|---|
| ![JTR](images/JTR-1.png) |
| ![JTR](images/JTR-2.png) |
| ![JTR](images/JTR-3.png) |
| ![JTR](images/JTR-4.png) |

### 📷 NetworkWalks Cracking

| Screenshot |
|---|
| ![NW](images/NW-1.png) |
| ![NW](images/NW-2.png) |
| ![NW](images/NW-3.png) |
| ![NW](images/NW-4.png) |

### 📷 AI Cracking

| Screenshot |
|---|
| ![AI](images/MCP-1.png) |
| ![AI](images/MCP-2.png) |
| ![AI](images/MCP-3.png) |
| ![AI](images/MCP-4.png) |
| ![AI](images/MCP-5.png) |


---

<a id="s10"></a>
## `[ SECTION 10 ]` Author & Project Information

**👤 Author**
`Safwan Abdurahiman Kavil` — `CompTIA Security+`
LinkedIn: `www.linkedin.com/in/safwan-abdurahiman-kavil-sak03`

**📌 Project Information**
Program: `W3-FINAL` | Week / Phase: `[3]`

---

