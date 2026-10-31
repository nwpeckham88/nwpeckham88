<div align="center">

# Hi, I'm Nathan 👋

### **Cybersecurity Student & Aspiring Security Engineer**
*Focusing on Network Security, Threat Detection & SIEM, Incident Response, and Defensive Infrastructure.*

[![Website](https://img.shields.io/badge/Website-kn8design.com-2563eb?style=flat-square&logo=googlechrome&logoColor=white)](https://kn8design.com)
[![GitHub](https://img.shields.io/badge/GitHub-nwpeckham88-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nwpeckham88)


---

</div>

### 🎯 Core Cybersecurity Competencies

```text
Security Operations:  SIEM & Log Analysis  •  Threat Detection & IOC Hunting  •  Incident Response (IR)
Network Security:     Zero-Trust Architecture  •  VLAN Segmentation  •  Single Packet Authorization (fwknop)
Defensive Hardening:  Intrusion Prevention (CrowdSec/Fail2ban)  •  Authelia 2FA SSO  •  WireGuard / Headscale
Security Tooling:     Go  •  Rust  •  Python  •  Bash/Shell  •  Protocol Reverse Engineering
Testing Environments: Self-Hosted Cowrie Honeypot  •  Kali Linux  •  ASUSWRT Hardening
```

---

### 🛡️ Featured Security Projects

<br>

#### 🔍 [quixote](https://github.com/nwpeckham88/quixote)
> **Security Assessment, Reconnaissance & Pentesting Workbench**  
> *Stack: Go • Offensive Security • Reconnaissance Automation*
* **Purpose:** A modular CLI workbench built for automating security reconnaissance, capturing host intelligence, and structuring penetration testing evidence.
* **Key Capabilities:** Streamlined target enumeration, repeatable reconnaissance logs, and structured IOC recording for post-assessment reporting.

<br>

#### 🎲 [bandb](https://github.com/nwpeckham88/bandb)
> **Interactive Incident Response Tabletop Simulation (*Backdoors & Breaches*)**  
> *Stack: JavaScript • LLM/AI Incident Master • Defensive Tactics*
* **Purpose:** A digital implementation of Black Hills Information Security's *Backdoors & Breaches* incident response game.
* **Training Value:** Simulates security breach escalation scenarios, MITRE ATT&CK defensive responses, procedural dice mechanics, and AI-driven tactical scenario narration.

<br>

#### 🚨 [security-resources](https://github.com/nwpeckham88/security-resources)
> **Perimeter Security Auditing & IOC-Driven Detection Suite**  
> *Stack: Shell • Network Hardening • ASUSWRT-Merlin Security*
* **Purpose:** Hardening scripts and threat detection checks built specifically for edge gateway and router environments.
* **Key Capabilities:** Scans for compromised host IOCs, monitors unauthorized DNS redirects, inspects dropped firewall states, and enforces perimeter baseline security.

<br>

#### 🌐 [cisco-ios-tplink](https://github.com/nwpeckham88/cisco-ios-tplink)
> **Network Switch Protocol Reverse Engineering & VLAN Management CLI**  
> *Stack: Go • Layer 2 Protocols • Network Infrastructure*
* **Purpose:** Reverse-engineered the proprietary configuration protocol of TP-Link TL-SG108E switches to provide a robust, Cisco IOS-like interactive CLI.
* **Security Application:** Enables scripted VLAN segmentation, port isolation, link status audits, and programmatic network isolation across homelab switch hardware.

<br>

#### 🦀 [supafast-jellyfin](https://github.com/nwpeckham88/supafast-jellyfin)
> **Memory-Safe Defensive Systems Programming & Audit Rollback Engine**  
> *Stack: Rust (Axum, Tokio) • Strict Path Lock Guards • Immutable Audit Logs*
* **Security Focus:** Demonstrates secure-by-default software engineering in pure Rust.
* **Defense-in-Depth:** Implements strict path-traversal confinement (preventing operations outside authorized roots), in-memory concurrency locks, and persistent transactional audit logging with deterministic one-click rollback.

<br>

#### ⚡ [updu](https://github.com/nwpeckham88/updu)
> **Lightweight Infrastructure & Service Availability Monitor**  
> *Stack: Go • Single-Binary • Self-Hosted Telemetry*
* **Security Focus:** Reliable uptime and telemetry verification across edge gateways and cloud nodes without external SaaS dependencies or third-party credential exposure.

---

### 🏰 Practical Cyber Range & Homelab Architecture
I maintain a hands-on distributed homelab infrastructure (`kn8design.com`) used as a practical testbed for network security and defensive operations:

* **Sacrificial Honeypot Node:** Isolated Cowrie SSH/Telnet honeypot node with strict outbound egress filtering to log and analyze real-world brute-force attack telemetry.
* **Single Packet Authorization (fwknop):** Drop-all perimeter firewall on edge nodes unlocked exclusively via encrypted SPA knocks on UDP 62201.
* **Zero-Trust Access & Identity:** Authelia 2FA SSO integration with LLDAP, CrowdSec automated intrusion prevention, and isolated Tailscale/WireGuard mesh.
* 📖 **Detailed Architecture & Security Runbooks:** [git.kn8design.com/nathan/homelab-docs](https://git.kn8design.com/nathan/homelab-docs)

---

<div align="center">
<sub>Nathan Peckham • Cybersecurity Student & Security Engineer</sub>
</div>
