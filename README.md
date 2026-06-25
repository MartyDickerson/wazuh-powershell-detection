# 🛡️ Wazuh PowerShell Abuse Detection Lab

**Author:** Marty Dickerson | [@cyberintelhq](https://github.com/MartyDickerson)  
**MITRE ATT&CK:** T1059.001, T1027, T1105, T1562, T1564  
**Severity:** High (Level 10–14)  
**Environment:** SOC Home Lab — Wazuh 4.x + Windows 10 Agent

---

## 📋 Overview

Custom Wazuh detection rules for PowerShell abuse — one of the most common attacker techniques in the wild.

| Rule ID | Detection | MITRE | Severity |
|---------|-----------|-------|----------|
| 100010 | Encoded Command (`-enc`) | T1059.001, T1027 | 12 |
| 100011 | Download Cradle (`IEX`, `WebClient`) | T1059.001, T1105 | 14 |
| 100012 | Execution Policy Bypass | T1059.001, T1562 | 10 |
| 100013 | Hidden Window | T1059.001, T1564 | 10 |

---

## 🏗️ Lab Environment

