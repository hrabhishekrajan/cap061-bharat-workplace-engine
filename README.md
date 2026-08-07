# cap061-bharat-workplace-engine
SOVEREIGN ENTERPRISE MESH: THE BHARAT WORKPLACE ENGINE
> **An Open-Source, Zero-Telemetry Architecture for Operational Communication & Automated KPI Logging**
> 
> **IIT Delhi – CEP | Design Thinking & Innovation (DTI Batch 10)**  
> **Capstone Project ID:** CAP-061  
> **Author:** Abhishek Rajan (Student ID: 110019608)  
> **Mentors:** Prof. Vijayaraghavan M. Chariar, Primary Sherpa Girish Anand, Backup Sherpa Nalini Murugesan  
> **License:** `IITD-CEP-DTI10-SOVEREIGN-1.0`
---
Overview
Modern enterprise software treats internal communication as an administrative broadcast problem, resulting in unrecorded operational work. The Bharat Workplace Engine bridges operational execution and community trust using a sovereign, pure Free and Open Source Software (FOSS) technical stack.
---
Operational Architecture
[ Internal Enterprise Zone ]                  [ External Expert Mesh ]
(Operations / HR / Legal)                    (Labor Lawyers / POSH)
│                                           │
▼                                           ▼
┌──────────────────────────┐                    ┌──────────────────────────┐
│   Matrix Synapse /       │◄── Federated ─────►│  Federated Matrix        │
│   Rocket.Chat Server     │    Encrypted       │  Bridge                  │
└────────────┬─────────────┘    Gateway         └──────────────────────────┘
│
▼
┌──────────────────────────┐
│  n8n Middleware          │ (Podman Container Orchestration)
└────────────┬─────────────┘
│
▼
┌──────────────────────────┐
│  Ollama Local LLM        │ (Offline Processing: Llama 3 / Mistral)
│  (Chat-to-KPI Engine)    │
└──────────────────────────┘


---

## Core System Modules

1. **Desi Baithak (Peer-Trust Guilds)**  
   Non-hierarchical, autonomous micro-guilds (5–15 peers) built for mentorship, operational problem-solving, and workplace psychological safety.

2. **Chat-to-KPI Engine**  
   Autonomous local AI agent running via Ollama and n8n that parses raw operational chat streams, extracting time-and-motion data to generate structured performance logs. Reduces weekly report preparation time from 120 minutes to under 10 minutes (91% reduction).

3. **Three-Tier Contextual Moderation**  
   * **Tier 1:** Automated expletive masking and channel tone grading.
   * **Tier 2 (Accidental Post Shield):** Local UI overlays that block informal slang directed at executive channels and prevent unauthorized screenshots.
   * **Tier 3:** Cryptographic file hash verification to prevent unauthorized data leaks.

---

## Technology Stack

| Layer | Component | Deployment Model |
| :--- | :--- | :--- |
| **Messaging Core** | Matrix Synapse / Rocket.Chat | Self-Hosted / On-Premise |
| **Orchestration** | n8n Workflows | Local Podman Containers |
| **Local Intelligence** | Ollama (Llama 3 / Mistral) | Sovereign Air-Gapped Hardware |
| **Compliance** | DPDP Act 2023 & POSH Framework | Zero External Telemetry |

---

## Regulatory & Legal Framework

* **Constitutional Balance:** Harmonizes **Article 19(1)(a)** (freedom of speech) with **Article 19(2)** (reasonable restrictions for decorum and safety).
* **Data Sovereignty:** 100% on-premise data residency compliant with India's Digital Personal Data Protection (DPDP) Act 2023.

---

## Project Artifacts & Links

* **Live Frontend Prototype:** [bharat-workplace-engine.vercel.app](https://bharat-workplace-engine.vercel.app)
* **Code Repository:** [github.com/hrabhishekrajan/cap061-bharat-workplace-engine](https://github.com/hrabhishekrajan/cap061-bharat-workplace-engine)
