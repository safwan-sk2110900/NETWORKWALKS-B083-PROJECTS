---
                    ██████████████████████████████████████████████████████████████████████████████████████████████████████
                                                    RECONNAISSANCE & NETWORK MAPPING REPORT
                                            OSINT (MALTEGO)  ///  NETWORK MAPPING (ZENMAP) // Nessus
                    ██████████████████████████████████████████████████████████████████████████████████████████████████████
---
`IMPORTANT — LEGAL AND ETHICAL USE ONLY`

> **TEMPLATE NOTICE:** findings, evidence and narrative content have been removed. Replace every bracketed `[ placeholder ]` before this report is distributed.

---

## 📋 W2-PM3-FINAL | CYBERSECURITY | NETWORKWALKS

|---|---|
| **Analyst/Pentester**  | `Safwan Abdurahiman Kavil`  |

| **Role / Title** | `Cybersecurity Intern` |

| **Engagement Name** | `B083-Networkwalks` |

| **Client / Target Scope** | `networkwalks.com` — `Home Lab` |

| **Authorization on file?** | Yes — approval secured from networkwalks.com |

| **Report Date** | `[ 16 September 2026 ]` |

| **Tools / Modules** | Maltego (OSINT Reconnaissance) + Zenmap / Nmap (Network Mapping) + Nessus |

| **Phases Covered** | Phase 1 – OSINT Reconnaissance \| Phase 2 – Network Discovery & Mapping \| `Phase 3 - Nessus/Maltego Mapping` |
|---|---|

---

## 🗂 Report Index

1. Authorization & Liability Disclaimer
2. Executive Summary
3. Scope & Objectives
4. Methodology & Tools Used
5. Activities Performed
   - 5.1 OSINT Reconnaissance (Maltego)
   - 5.2 Network Mapping (Zenmap)
6. Findings & Risk Analysis
7. Recommendations
8. Conclusion
9. Evidence & Appendix
10. Author & Project Information

---

## `[ SECTION 01 ]` Authorization & Liability Disclaimer

This assessment was performed only against systems and assets for which written authorization was obtained — specifically **networkwalks.com** , **my own Home Lab** — and/or systems and devices that I own myself.

All activities described in this report are conducted for authorized security assessment, education and research purposes only. Nothing in this document should be used to access, scan or test any system without explicit written permission from its owner. Every action taken is the responsibility of the person performing it. Misuse of these techniques may result in criminal charges, civil liability, loss of employment and a permanent record. In most jurisdictions, unauthorized access to a computer system is a crime even when no damage occurs.


---

## `[ SECTION 02 ]` Executive Summary

> _[ Provide a 3–4 sentence, non-technical summary: what was assessed, the two methods used (OSINT via Maltego, network mapping via Zenmap), and the overall risk posture identified ]_

> _[ State the number and severity breakdown of findings, e.g. "2 Medium, 3 Low" ]_

---

## `[ SECTION 03 ]` Scope & Objectives

**Objectives**
- ▸ Map the external OSINT footprint of the target using Maltego (domains, infrastructure, personas, related entities)
- ▸ Discover and map live hosts, services and topology on the in-scope network using Zenmap
- ▸ `[ Add any additional engagement objective ]`

**In Scope**
> _[ List domains, IP ranges, subnets or entities explicitly authorized for this engagement ]_

**Out of Scope**
> _[ List anything explicitly excluded from this engagement ]_

**Constraints / Rules of Engagement**
> _[ Testing windows, rate limits, exploitation boundaries, notification requirements, etc. ]_

---

## `[ SECTION 04 ]` Methodology & Tools Used

The table below lists each tool used during this engagement and its purpose.

| Tool | Purpose |
|---|---|
| **Maltego** | Graph-based OSINT reconnaissance — mapping domains, subdomains, infrastructure, email addresses, personas and related entities tied to the target. |
| **Zenmap (Nmap GUI)** | Active network discovery and mapping — identifying live hosts, IP/MAC addresses, open ports, services and network topology. |
| `[ Supporting OS ]` | `[ e.g. Kali Linux / Windows — operating environment used to run the above tools ]` |
| `[ Additional tool ]` | `[ Purpose of any additional tool used in this engagement ]` |

---

## `[ SECTION 05 ]` Activities Performed

### 5.1 OSINT Reconnaissance (Maltego)

> _[ Describe the Maltego machines/transforms run, the seed entity used, and the general approach taken ]_

- ▸ Domains / subdomains identified: `[ list ]`
- ▸ Infrastructure (IPs, ASN, hosting) mapped: `[ list ]`
- ▸ Email addresses / personas / related entities discovered: `[ list ]`
- ▸ Notable relationships or pivot points surfaced by the graph: `[ list ]`

### 5.2 Network Mapping (Zenmap)

> _[ Describe the scan type(s) run (e.g. ping scan, intense scan), the subnet targeted, and the process followed ]_

- ▸ Subnet / range scanned: `[ e.g. 10.0.0.0/24 ]`
- ▸ Live hosts identified: `[ list of IPs ]`
- ▸ Notable open ports / services: `[ list ]`
- ▸ Topology exported (Yes/No, format): `[ answer ]`

*Note: replace all bracketed values above with the actual subnet, hosts, ports and entities discovered during this engagement before this report is finalized.*

---

## `[ SECTION 06 ]` Findings & Risk Analysis

Based on the OSINT reconnaissance and network mapping activities, the following potential risks were identified.

| # | Finding | Evidence / Observation | Potential Impact | Risk |
|---|---|---|---|---|
| 1 | `[ Finding title ]` | `[ What was observed ]` | `[ Why it matters ]` | `[ Crit/High/Med/Low ]` |
| 2 | `[ Finding title ]` | `[ What was observed ]` | `[ Why it matters ]` | `[ Crit/High/Med/Low ]` |
| 3 | `[ Finding title ]` | `[ What was observed ]` | `[ Why it matters ]` | `[ Crit/High/Med/Low ]` |
| 4 | `[ Finding title ]` | `[ What was observed ]` | `[ Why it matters ]` | `[ Crit/High/Med/Low ]` |

**Risk level key:** ● Critical &nbsp;&nbsp;● High &nbsp;&nbsp;● Medium &nbsp;&nbsp;● Low

*These findings are observations from reconnaissance and mapping activities, not confirmed exploitable vulnerabilities. No exploitation or vulnerability validation was performed as part of this engagement unless explicitly stated above. Further authorized testing would be required to confirm actual exploitability.*

---

## `[ SECTION 07 ]` Recommendations

1. **Review the public OSINT footprint** — `[ Recommendation detail — e.g. periodically audit what Maltego / public sources reveal about the organization ]`
2. **Reduce infrastructure exposure** — `[ Recommendation detail ]`
3. **Harden discovered services** — `[ Recommendation detail — based on ports/services found via Zenmap ]`
4. **Monitor for unauthorized hosts** — `[ Recommendation detail ]`
5. **Maintain network documentation** — `[ Recommendation detail ]`
6. **Perform recurring authorized testing** — `[ Recommendation detail ]`

---

## `[ SECTION 08 ]` Conclusion

> _[ Summarize what was performed, the overall security posture observed, and the key takeaway from combining OSINT reconnaissance with active network mapping ]_

> _[ Reaffirm that all activity was performed within the authorized scope granted by networkwalks.com ]_

---

## `[ SECTION 09 ]` Evidence & Appendix

| Screenshot |
|---|
| 📷 `[ Insert screenshot — Maltego — domain/infrastructure graph ]` |
| 📷 `[ Insert screenshot — Maltego — entity/persona graph ]` |
| 📷 `[ Insert screenshot — Zenmap — host discovery scan ]` |
| 📷 `[ Insert screenshot — Zenmap — network topology export ]` |
| 📷 `[ Insert screenshot — Additional evidence ]` |

---

## `[ SECTION 10 ]` Author & Project Information

**👤 Author**
`[ Your Full Name ]` — `[ Your Title / Certification ]`
LinkedIn: `[ your LinkedIn URL ]`

**📌 Project Information**
Program: `[ Program / Engagement Name ]` | Week / Phase: `[ # ]` | Repository: `[ link, if applicable ]`

---

`— END OF TEMPLATE —`
