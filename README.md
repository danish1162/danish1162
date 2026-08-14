# Muhammad Nadeem Danish

**Independent Security Researcher | Cyber Verification Program**

Firmware reverse engineering and vulnerability research focused on CPE routers, mobile hotspots, and IoT gateways. All research performed on personally owned hardware under coordinated disclosure.

---

## Cyber Verification Program

Independent vulnerability research program targeting network infrastructure firmware. Research methodology: full-stack binary analysis (IDA Pro, Ghidra, radare2), protocol reverse engineering (TR-069/CWMP, HTTP/JSON-RPC, AT commands), and proof-of-concept development.

### Focus Areas

- CPE router firmware security (ZTE, Nokia, Linksys, Huawei)
- TR-069/CWMP protocol implementation flaws
- Authentication bypass and credential recovery
- OS command injection in embedded systems
- Carrier lock and NV subsystem security
- WebUI and management interface vulnerabilities

---

## Published CVEs

| CVE ID | Vendor | Device | Vulnerability | Severity |
|---|---|---|---|---|
| CVE-2026-2035703 | ZTE/ZLT | X300 | TR-069 TargetFileName Improper Input Validation (CWE-20) | Critical (10.0) |

*Additional CVEs pending coordinated disclosure — will be listed here upon publication.*

---

## Research Portfolio (Pre-Disclosure)

| # | Vendor | Device | Category | Status |
|---|---|---|---|---|
| 1 | ZTE | U10LS | Authenticated WebUI OS Command Injection (CWE-78) | Pre-disclosure |
| 2 | ZTE | U10LS | WebUI SMS Handler Stack Buffer Overflow (CWE-787) | Pre-disclosure |
| 3 | ZTE | MF286C | Diagnostic Log RCE | Pre-disclosure |
| 4 | ZTE | K12 | NCK Lock Bypass + RSA Forge (CWE-321/602) | Pre-disclosure |
| 5 | ZTE | K12 | PLMN Lock Bypass (CWE-693) | Pre-disclosure |
| 6 | ZTE | G5TS | ZAUTH PRNG Weakness + IMEI Write (CWE-330/287) | Pre-disclosure |
| 7 | Nokia | FastMile 3.1 | LAN to Root via TR-069 ACS | Pre-disclosure |
| 8 | Nokia | FastMile 5G v2 | LAN to Root Chain | Pre-disclosure |
| 9 | Linksys | Velop Pro 7 (MBE70WRT) | Pre-Auth Credential Disclosure | Pre-disclosure |
| 10 | Huawei | H155-381 | Config Decryption (Whitebox AES) | Pre-disclosure |
| 11 | Jontly | M101 (MT6890) | Unauthenticated Root RCE (CWE-78) | Pre-disclosure |

---

## Tools and Methodology

**Binary Analysis:** IDA Pro 9.1, Ghidra 12, radare2, rizin  
**Languages:** Python, C, ARM assembly (aarch64/arm32)  
**Protocols:** TR-069/CWMP, HTTP/JSON-RPC, SOAP, AT commands, ADB  
**Platforms:** OpenWrt, Qualcomm (Balong/HISI), MediaTek, Fibocom  
**OS:** macOS (primary), Kali Linux (firmware extraction), Windows (flash tools)

---

## Contact

**Email:** surfv.free@gmail.com  
**GitHub:** [@danish1162](https://github.com/danish1162)  
**CVE Program:** MITRE CNA-LR (independent researcher)

---

## Disclosure Policy

- 90-day coordinated disclosure on all findings
- Vendor notification before any public release
- All research on personally owned hardware only
- PoC tools designed for authorized testing, not malicious use
