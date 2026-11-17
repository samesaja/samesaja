# Frans Dhito Aditya Wibowo (`samdhito` / `samesaja`)

**Principal Full-Stack, Cloud Infrastructure & AI Systems Architect**  
🌐 [samdhito.web.id](https://samdhito.web.id) · 💼 [LinkedIn](https://www.linkedin.com/in/frans-dhito-aditya-wibowo-1570b1241) · 📦 [npm (`@samdhitosaja`)](https://www.npmjs.com/~samdhitosaja) · ✉️ [frans@samdhito.web.id](mailto:frans@samdhito.web.id)

---

### ⚡ Executive Summary
Principal Software, Cloud Infrastructure, and AI Systems Architect with **6+ years of production experience** designing, building, and operating mission-critical distributed systems, bare-metal GPU/cloud clusters, real-time WebRTC/VoIP telephony, and autonomous AI workflows across **Europe (Amsterdam / CET)** and **Asia-Pacific (Auckland / NZDT)**.

---

### 🏗️ Flagship Production Systems & Deep-Tech Engineering

- **☁️ Bare-Metal OpenStack, Kubernetes & Multi-Tenant PaaS (`RZ Command Center`):**
  - Architected and operated a **6-node production OpenStack & Kubernetes cluster** (**528 CPU threads**, **2.26 TB DDR4 ECC RAM**, **63 TB Ceph NVMe**, **219 TB HDD**) automated via `kolla-ansible`, Terraform, GitLab CI, ArgoCD, and Prometheus/Grafana.
  - Built **RZ Command Center**, a multi-tenant BaaS/PaaS platform featuring isolated PostgreSQL tenant databases, automated REST/OpenAPI & MCP data planes, zero-downtime Docker container runners, and dynamic subdomain gateways.

- **🖥️ Multi-GPU AI Inference & Real-Time 3D Pixel Streaming Clusters (`14x NVIDIA RTX A6000`):**
  - Engineered a **10x NVIDIA RTX A6000 (480 GB ECC VRAM)** Unreal Engine Pixel Streaming and 3D Digital Twin infrastructure (including large-scale interactive 3D Virtual City deployment in **Yanbu, Saudi Arabia** with custom signaling, TURN servers, and GPU queue orchestration).
  - Operate a sovereign **4x NVIDIA RTX A6000 (192 GB ECC VRAM)** AI inference cluster serving multi-tenant LLM workloads (`Qwen`, `Llama`, `DeepSeek` via LiteLLM) and real-time `Faster-Whisper large-v3` speech pipelines.

- **📱 On-Device Edge NPU AI (`MODEL-QNN` — Qualcomm Hexagon HTP v79 NPU):**
  - Compiled and deployed custom `W4A16 (INT4)` quantized context binaries running natively on **Qualcomm Hexagon HTP v79 NPU (45 TOPS)** via a custom `libQnnHtp.so` C++/JNI bridge, achieving **40–45ms offline Whisper STT latency** and **75–150ms offline Llama 3.2 1B inference** on mobile hardware.

- **📞 Enterprise Cross-Platform VoIP PBX & AI Call Intelligence:**
  - Solely engineered a complete corporate telephony ecosystem replacing 3CX end to end across **Native iOS (`CallKit`, `PushKit`, `RTCAudioSession`)**, **Android (`TelecomManager`, `ConnectionService`, Bluetooth HFP)**, **React/Expo Web PWA**, **FreeSWITCH WebRTC (`mod_verto`, `mod_xml_curl`)**, **CoTURN**, and an automated **Faster-Whisper + Claude AI CRM Intelligence** pipeline.

- **🚚 European Logistics, Warehouse & Accounting Automation (Amsterdam, NL):**
  - Architected zero-touch backend and workflow pipelines (`Python FastAPI`, `TypeScript`, `Next.js/React`, `PostgreSQL`, `n8n`) integrating **Mintsoft (WMS)**, multi-region **FedEx APIs**, **MyFreight**, and **Fortnox** accounting, eliminating **90% of manual operational tasks**.

- **🛡️ Autonomous AI SecOps & Red-Team Command Center (`RZ Sensing`):**
  - Built a multi-agent security operations platform orchestrating 21+ security scanners (`nuclei`, `subfinder`, `httpx`, `naabu`, `trivy`, `semgrep`, `gitleaks`, `zap`) with automated STRIDE threat modeling, multi-tenant RBAC, and strict target scope guardrails.

---

### 📦 Published Open-Source Packages (MCP & Workflow Automation)

| Package | Registry | Description |
| :--- | :--- | :--- |
| **[`@samdhitosaja/mcp-eu-company-registry`](https://github.com/samesaja/mcp-eu-company-registry)** | [npm](https://www.npmjs.com/package/@samdhitosaja/mcp-eu-company-registry) · [LobeHub MCP](https://lobehub.com/mcp/samesaja-mcp-eu-company-registry) | Model Context Protocol (MCP) server connecting AI agents directly to **16 official European company registries & B2B directories** (NL, CH, DE, AT, NO, SE, FI, DK, PL, IT, UK, FR, BE, ES, IE, EU VIES). |
| **[`n8n-nodes-eu-b2b-registry`](https://github.com/samesaja/n8n-nodes-eu-b2b-registry)** | [npm](https://www.npmjs.com/package/n8n-nodes-eu-b2b-registry) | Official n8n community node for automated European B2B company registry lookup, VAT/KVK/UID verification, and lead enrichment. |

---

### 🏆 Honors & Competitive Achievements
- **National Grand Finalist — Olimpiade Jaringan MikroTik (OJM) 2019** (*Citraweb & APJII — Top 22 National Finalists across Indonesia in Bali; sole finalist representing the Special Region of Yogyakarta, Participant `#1102854`*).

---

### 🛠️ Technical Arsenal
- **Languages:** TypeScript, Python, Go, Java/Kotlin, Swift, C/C++ (JNI), Lua, SQL, Bash
- **Frontend & Mobile:** React, Next.js, React Native, Expo, Tailwind CSS, Native iOS (`CallKit`/`PushKit`), Native Android (`TelecomManager`)
- **Backend & Data:** FastAPI, Node.js, PostgreSQL, Redis, Supabase, PostgREST, GraphQL, gRPC, WebSockets
- **Cloud, Bare-Metal & DevSecOps:** OpenStack (`kolla-ansible`), Kubernetes, Docker, Proxmox, Linux, Terraform, Ansible, GitLab CI, GitHub Actions, ArgoCD, Prometheus, Grafana, Cloudflare, MikroTik RouterOS, WireGuard / NetBird
- **AI, Voice & Telephony:** Multi-GPU LLM Serving (`vLLM`, `LiteLLM`, `Faster-Whisper`), Qualcomm QNN / Hexagon NPU (`INT4/W4A16`), LangGraph / Multi-Agent Systems, FreeSWITCH / FusionPBX, WebRTC, SIP, CoTURN
