<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="Nanako. DevSecOps, C++" width="100%">
  </picture>
</p>

<p align="center">English &middot; <a href="README.zh-CN.md">中文</a> &middot; <a href="README.la.md">Lingua Latīna</a></p>

---

## Engineering Values

- I tend to rank the dignity, elegance and correctness of architecture above all delivery speed and requirements.
- I tend to design API-first, and I give priority to the engineering quality of APIs and SDKs.
- I have always taken the Dev-First position; Sales-First, Consumer-First and Time-to-Market do not interest me.
- I do not oppose over-design, and I particularly detest the excuses of YAGNI and KISS.
- Fail-Fast. I detest defensive branches and fallback code of every kind.
- I do not accept the philosophy of pursuing lightness and small-is-beautiful for their own sake. I lean towards API-driven, flexibly pluggable software, and for elegant architectural composition to be truly workable, the precondition is a strong, unified underlying abstraction.
- I build only software that meets my own aesthetic; open-source reputation, helping others and commercialisation do not interest me.
- Word choice is a design decision. An imprecise name is an imprecise design.
- Whether to open-source is the developer's choice. Open source and closed source are two routes of equal worth, and choosing either needs no explanation. I oppose moral coercion in the name of open source.
- I detest unauthorised, unlawful reverse engineering, and I also oppose dressing it up as the spirit of open source or of sharing.
- I have my own server room and cluster. I care to the extreme about my data sovereignty and software sovereignty, so whatever can run locally does not go to the cloud.

## Technology

| Area | Technology |
| --- | --- |
| Languages | C, C++ (C++11 to C++23), Go, TypeScript, Python, Rust, x86 ASM |
| Clients and Graphics | Qt6 and Custom Vendored Qt6, Unreal Engine 5, CEF Off-Screen Rendering, DirectX 12, Vulkan, DirectComposition, Live2D Cubism |
| Protocols and Transport | Custom Binary Protocol Design, TLS 1.3, QUIC, HTTP/3, WebRTC, AnyTLS, REALITY, obfs4, Hysteria2, Snowflake |
| Cryptography | GM (SM2, SM3, SM4), PQC (ML-KEM, ML-DSA, SLH-DSA), OPAQUE, MLS, HPKE, Noise, TPM 2.0 Attestation, WebAuthn, ProVerif |
| Systems Programming and Sandboxing | Linux Namespaces, seccomp, cgroups, AppContainer, WebAssembly (Wasmtime), Anti-Debugging and Software Hardening, VMP Variants and Mutation Protection |
| Model Training | PyTorch, TRL, PEFT, LoRA, DPO, Directional Ablation (Heretic, MPOA, ARA) |
| Model Inference | vLLM, TensorRT-LLM, Infinity, Model Quantisation, RoPE Tuning |
| Retrieval and Knowledge Bases | RAGFlow, Elasticsearch, Hybrid Retrieval, Reranking, Golden Set |
| Agents | MCP, Letta, Claude Code, Codex |
| Networking | Software Routers, Load Balancing and Failover, Link Aggregation, VLAN, VXLAN, Firewalls (nftables), Transparent Proxying and Traffic Splitting, Traffic Shaping and Congestion Control, Recursive and Authoritative DNS, DNSSEC, Tor Hidden Services |
| Systems and Operations | Linux, Docker, systemd, Ansible, Nginx, FRP, Proxmox Backup Server |
| Databases | PostgreSQL, MySQL, SQLite, CouchDB, Elasticsearch, Valkey |
| Scientific Computing | JupyterLab, Dask, REBOUND, MERCURY, VPLanet, ExoPlaSim, climlab |

## Projects

### Platforms and infrastructure

| Project | Description | Language | Licence |
| --- | --- | --- | --- |
| [**Astra**](https://gitlab.rothmary.com/Astra/Public) | A privately sovereign, unified DevOps plane that brings software engineering management and server operations onto one platform. Qt, Unreal Engine and web clients share one core of protocol, permissions and audit. | C/C++ | Proprietary (EULA) |
| [**Aevum**](https://gitlab.rothmary.com/Aevum) | A verifiable public record network. A minimal, auditable kernel fetches application protocols, data schemas and cryptographic suites from content-addressed on-chain records and runs them in a sandbox. Built on a permissioned BFT ledger. | Go, Rust, Solidity | MIT |

### Agents

| Project | Description | Language | Licence |
| --- | --- | --- | --- |
| [**Armillary**](https://gitlab.rothmary.com/Armillary) | An on-premises agent runtime with CLI, SDK and MCP entry points, built-in tools and sub-agents. Also deployable as SaaS. | TypeScript | Proprietary (EULA) |
| [**Gestalt Mind**](https://gitlab.rothmary.com/Gestalt) | Office automation for agents: accounts, positions, working groups, scoped permissions, shared files and common knowledge, with mail and notices. Each agent keeps its native sessions. | Rust | Source-available (RSL) |

### Content and notes

| Project | Description | Language | Licence |
| --- | --- | --- | --- |
| [**Pandectae**](https://gitlab.rothmary.com/Pandectae) | A general-purpose CMS: WordPress reimplemented in Go, compatible in concepts and data. Any WordPress site can be imported without loss. | Go | Apache 2.0 |
| [**Eburnea**](https://gitlab.rothmary.com/Eburnea) | A personal blog being rebuilt on Pandectae. | Go | Proprietary |
| [**Tabularium**](https://github.com/Violaria/Tabularium) | A self-hosted, end-to-end encrypted note synchronisation server with an Obsidian plug-in, web notes, sharing, Send to Kindle and an AI administrator. | TypeScript | MIT |
| [**Litterae Anonymae**](https://gitlab.rothmary.com/Litterae) | A self-maintained anonymous question box: visitors ask without registering and the site owner answers in public. | Ruby, TypeScript | MIT |

All repositories are hosted on a self-managed GitLab instance. Open-source projects may publish their source there; proprietary projects publish releases and documentation only. Tabularium's source is also public on GitHub.

If you want to follow my work on GitHub or open an issue, I regret to say that I seldom check messages on GitHub, and most of my projects live on my private GitLab.
