<div align="center">

# Hi, I'm Nathan 👋

**Systems, Security & Full-Stack Engineer**  
*Building high-performance backends, resilient self-hosted infrastructure, and developer tooling.*

[![Website](https://img.shields.io/badge/Website-kn8design.com-2563eb?style=flat-square&logo=googlechrome&logoColor=white)](https://kn8design.com)
[![GitHub](https://img.shields.io/badge/GitHub-nwpeckham88-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nwpeckham88)
[![Homelab Docs](https://img.shields.io/badge/Homelab-Docs-10b981?style=flat-square&logo=git&logoColor=white)](https://git.kn8design.com/nathan/homelab-docs)

---

</div>

### 🛠️ Core Technical Stack

```text
Languages:       Rust  •  Go  •  TypeScript  •  Python  •  C++  •  Svelte / SvelteKit
Systems & Infra: Linux (Debian)  •  Docker & Compose  •  Ansible  •  Caddy  •  WireGuard / NetBird
Data & Storage:  PostgreSQL  •  SQLite / SQLx  •  Rclone  •  Redis
Security & Ops:  SIEM (Vigilant)  •  Recon & IOC Auditing  •  Zero-Trust Edge Gateways (Authelia, CrowdSec)
```

---

### 🚀 Featured Engineering Projects

<br>

#### 🦀 [supafast-jellyfin](https://github.com/nwpeckham88/supafast-jellyfin)
> **High-Performance Media Normalizer, Deduplicator & Rollback Engine**  
> *Stack: Rust (Axum, Tokio) • SvelteKit • PostgreSQL • Filesystem Path Guards*
* **Architecture:** Implements a strict two-phase execution pipeline (**Scan ➔ Preview ➔ Execute**) with filesystem path locking to safely normalize messy scene/release filenames without modifying source roots.
* **Reliability:** Built-in persistent transaction audit logging with one-click rollback support, idempotent execution keys, and sub-millisecond duplicate detection.

<br>

#### ⚡ [updu](https://github.com/nwpeckham88/updu)
> **Lightweight, Single-Binary Self-Hosted Uptime Monitoring**  
> *Stack: Go • Svelte • Embedded Assets*
* **Architecture:** Minimalist, self-contained health monitor packaged into a single deployable binary.
* **Performance:** Capable of running effortlessly across edge SBCs (Raspberry Pi Zero) and cloud VPS nodes with embedded web UI and instant alert dispatching.

<br>

#### 🌐 [cisco-ios-tplink](https://github.com/nwpeckham88/cisco-ios-tplink)
> **Interactive Cisco IOS CLI & Protocol SDK for Managed Switches**  
> *Stack: Go • Low-Level Networking • Protocol Reverse Engineering*
* **Architecture:** Re-engineers the proprietary configuration protocol of TP-Link TL-SG108E switches into an interactive Cisco IOS-like shell environment.
* **Utility:** Provides network engineers with programmatic VLAN tagging, port duplexing, and link state diagnostics over standard CLI workflows.

<br>

#### 🐳 [quick-compose](https://github.com/nwpeckham88/quick-compose)
> **Visual Docker Compose Assembler & Configuration Validator**  
> *Stack: TypeScript • React / Modern Web • Docker Compose Spec*
* **Architecture:** Interactive web-based workspace designed to draft, validate, and assemble modular multi-container Docker Compose stacks.
* **Developer Experience:** Live YAML preview, syntax error highlighting, and exportable service definitions.

<br>

#### 🛡️ [quixote](https://github.com/nwpeckham88/quixote)
> **Security Assessment, Reconnaissance & Pentesting Workbench**  
> *Stack: Go • Cybersecurity Operations*
* **Architecture:** Modular security assessment framework for learning, testing, and recording network penetration testing workflows.
* **Features:** Structured evidence recording, IOC-driven discovery, and repeatable reconnaissance logs.

<br>

#### 🎲 [bandb](https://github.com/nwpeckham88/bandb)
> **AI-Narrated Incident Response Tabletop Simulation**  
> *Stack: JavaScript • Web Components • LLM Integration*
* **Architecture:** Interactive digital web implementation of the *Backdoors & Breaches* cyber incident response tabletop game.
* **AI Integration:** Dynamically generated tactical scenarios, automated dice mechanics, and AI incident master narration.

---

### 🏡 Distributed Homelab & Edge Architecture
Beyond software applications, I design and maintain a multi-node distributed infrastructure connecting edge VPS gateways (Debian 13, Caddy, Authelia SSO, Headscale) with internal compute nodes running containerized workloads, localized AI models (RK3588 NPU), and redundant storage.

* 📖 **Public Homelab Architecture & Runbooks:** [git.kn8design.com/nathan/homelab-docs](https://git.kn8design.com/nathan/homelab-docs)

---

<div align="center">
<sub>Designed and maintained by Nathan Peckham • Powered by open source</sub>
</div>