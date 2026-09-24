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
   - [5.1 Password Cracking with John the Ripper](#51-osint-reconnaissance-maltego)
   - [5.2 NetworkWalks Cracking Tools](#52-network-mapping-zenmap)
   - [5.3 Vulnerability Assessment (Nessus)](#53-vulnerability-assessment-nessus)
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


An authorized security assessment was conducted against the lab environment using Maltego, Zenmap/Nmap, and Nessus to evaluate OSINT exposure, identify active network hosts, and assess system vulnerabilities.

The Maltego OSINT assessment identified one publicly discoverable organizational email address, info@networkwalks.com. As this is a generic mailbox and no credentials or sensitive information were identified, the finding presents a Low risk, with its primary value being reconnaissance and potential exposure to phishing or spam.

Using Zenmap, five active devices were identified within the authorized lab network: Kali Linux, Windows 7, Windows Server 2016, Windows 10, and the VirtualBox NAT Network gateway. Since the scan was limited to host discovery, these results represent network reconnaissance information rather than vulnerabilities.

The Nessus scan produced a significantly larger set of findings on the Windows 7, Windows Server 2016, and Windows 10 systems. The results indicate issues including missing security updates, outdated components, and potentially insecure configurations, with the legacy Windows 7 system requiring particular attention.

Overall, the assessment found that the main security exposure lies within the Windows systems identified by Nessus, rather than the OSINT or network-discovery findings. Remediation should focus on prioritizing high-severity vulnerabilities, applying security updates, reviewing configurations, and isolating or replacing unsupported legacy systems where appropriate.

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
> 
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


1. **Review the public OSINT footprint** — Periodically audit what Maltego / public sources reveal about the domain networkwalks.com.
2. **Reduce infrastructure exposure** — Based on the audit and periodic scanning, decide what infrastructure needs less exposure than required by implementing least privilege principle.

---


<a id="s8"></a>
## `[ SECTION 08 ]` Conclusion

This engagement combined OSINT reconnaissance (Maltego), active network mapping (Zenmap/Nmap), and credentialed vulnerability assessment (Nessus) against the networkwalks.com homelab. OSINT exposure was minimal (a single contact email). Network mapping identified 5 hosts — including a Windows Server 2016 DC, a Windows 10 workstation, and a legacy Windows 7 host — with RDP, SMB, LDAP, Kerberos, and a database exposed on a flat, unsegmented network. Nessus confirmed these exposures as real, exploitable vulnerabilities: a kernel-level TCP/IP flaw on Windows 7, DNS Server RCE and SMBv1 disclosure on the DC, missing patches on Windows 10, and IIS path disclosure on the gateway.

Overall, the security posture is **weak to moderate**: the Domain Controller and legacy endpoints are directly reachable and unpatched, placing the core of the domain at meaningful risk. The key takeaway is that each phase validated the next — OSINT mapped the external footprint, network scanning revealed the internal attack surface, and vulnerability scanning proved that surface maps to real, exploitable risk. Network segmentation, patching, and least-privilege exposure are the priority fixes.

All activity in this report was performed strictly within the scope authorized by networkwalks.com. No exploitation was conducted; confirming exploitability would require a separately authorized penetration test.

---

<a id="s9"></a>
## `[ SECTION 09 ]` Evidence & Appendix

### 📷 Maltego

| Screenshot |
|---|
| ![Maltego](images/maltego-1.png) |
| ![Maltego](images/maltego-2.png) |
| ![Maltego](images/maltego-3.png) |
| ![Maltego](images/maltego-4.png) |

### 📷 Zenmap

| Screenshot |
|---|
| ![Discovery](images/zenmap-1.png) |
| ![Discovery](images/zenmap-2.png) |

### 📷 Nessus

| Screenshot |
|---|
| ![Nessus](images/nessus-1.png) |
| ![Nessus](images/nessus-2.png) |
| ![Nessus](images/nessusrisk1.png) |
| ![Nessus](images/nessusrisk2.png) |
| ![Nessus](images/nessusrisk3.png) |
| ![Nessus](images/nessusrisk4.png) |
| ![Nessus](images/nessusrisk5.png) |

---

<a id="s10"></a>
## `[ SECTION 10 ]` Author & Project Information

**👤 Author**
`Safwan Abdurahiman Kavil` — `CompTIA Security+`
LinkedIn: `www.linkedin.com/in/safwan-abdurahiman-kavil-sak03`

**📌 Project Information**
Program: `W2-PM3-FINAL` | Week / Phase: `[2]`

---

