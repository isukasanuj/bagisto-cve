# Security advisories

Public advisories for vulnerabilities found and reported by [Isuka Sanuj](https://github.com/isukasanuj) — CyberCrew (株式会社CyberCrew).

## Bagisto (Webkul Software)

All three were reported to Webkul on 2026-08-12 and discussed over several exchanges. None is fixed as of 2.4.10, the current release at time of publication, verified by source diff of `v2.4.9..v2.4.10`.

| CVE | Issue | CVSS 3.1 |
|---|---|---|
| [CVE-2026-79409](CVE-2026-79409.md) | Cross-product downloadable entitlement grant via unvalidated `links[]` | 6.5 |
| [CVE-2026-79410](CVE-2026-79410.md) | Customer-controlled order total via negative quantity on the add-to-cart path | 6.5 |
| [CVE-2026-79411](CVE-2026-79411.md) | Vertical privilege escalation via unconstrained `role_id` | 8.8 |

CVE IDs assigned by the MITRE CNA-LR.

---

Released for defensive purposes. Testing against systems you do not own or have written authorization to assess is illegal.
