---
title: "RPDev Blog & Research"
description: "Applied cybersecurity research, autonomous AI swarms, localized LLM control planes, technical whitepapers, systems engineering monographs, and engineering leadership essays by Richard P. Dissell."
aliases:
  - /blog
  - /blog/index
  - /posts
  - /articles
tags:
  - blog
  - articles
  - research
  - engineering
  - security
  - ai
  - systems
  - hardware
  - leadership
---

# ✍️ RPDev Technical Blog & Research

> **The sovereign publication hub for applied cybersecurity research, autonomous multi-agent swarms, localized LLM control planes, long-form systems architecture monographs, and asynchronous technical leadership essays.**

<nav class="projects-category-bar">
  <a href="#articles" class="cat-pill"><span class="cat-icon">📝</span> Articles & Field Guides</a>
  <a href="#security-ai-research" class="cat-pill"><span class="cat-icon">🛡️</span> Security & AI Research</a>
</nav>

---

<section id="articles" class="project-category-section">

## 📝 [[articles/index|Articles & Technical Field Guides]]

Long-form architectural essays, systems complexity theory, zero-trust edge implementations, and bare-metal repair logs.

### 🏗️ Systems Architecture & Automation
- **[[articles/Systems_Automation|Systems & Automation Architecture: Layer 2 Networks, Storage Tiering & GitOps]]**  
  *Declarative orchestration, Layer 2 non-NAT container networks, hardware-aware storage tiering (NVMe vs. NFS), and GitOps operational loops.*
- **[[articles/MCP_Enterprise|Model Context Protocol (MCP): The Nervous System for Local AI Agent Swarms]]**  
  *Standardizing local AI agent interaction with enterprise infrastructure via deterministic, stateful Model Context Protocol servers and Server-Sent Events (SSE).*

### 🛡️ Zero Trust & Cyber Warfare Systems Theory
- **[[articles/Zero_Trust_Edge|Zero Trust at the Edge: Hardening OpenWrt with CrowdSec & Cloudflare Tunnels]]**  
  *Custom OpenWrt edge routing, DNS-over-HTTPS (DoH), dual-engine IDS/IPS boundary defense, and zero-open-ports ingress.*
- **[[articles/Systems_Theory|Games & Systems Theory: War Games, Adversary Emulation & Cognitive Attack Surfaces]]**  
  *Applied mathematical game theory, cyber war gaming, Red vs. Blue payoff matrices, deception meshes, and cognitive attack surface mitigation.*

### 🔬 Hardware Engineering & Diagnostics
- **[[articles/Component_Repair|From Cathode Ray Tubes to Silicon Interposers: 20 Years of Component-Level Repair]]**  
  *Component-level diagnostics, electronics repair, analog CRT oscilloscopes, micro-soldering, and automotive embedded control units.*
- **[[articles/Lab_Workstation|Uses: Workstation, Homelab & Security Toolchain Specification]]**  
  *Comprehensive inventory of physical workstations, edge compute nodes, hardware security keys (FIDO2/U2F), and daily software toolchains.*

### 👥 Engineering Leadership & Culture
- **[[articles/Philosophy|Leadership Philosophy: Asynchronous Autonomy, AI Augmentation & Psychological Safety]]**  
  *Modern technical leadership, remote-first async operating models, pervasive AI augmentation, blameless post-mortems, and engineering velocity.*

</section>

---

<section id="security-ai-research" class="project-category-section">

## 🛡️ [[research/index|Security & AI Systems Applied Research]]

Autonomous multi-agent defense swarms, localized LLM control planes, high-dimensional vector memory retrieval, and empirical RF anomaly modeling.

### Capstone Theses & Security Monographs

| Monograph / Research Track | Focus & Mathematical Primitives |
|---|---|
| **[[research/index|Master Thesis & Capstone Executive Summary]]** | Central thesis statement, operational roadmap, and problem definition. |
| **[[research/Agents_and_Architecture|Multi-Agent Swarm Topology & Execution Boundaries]]** | Autonomous agent hierarchy, quorum gating consensus, and MCP execution boundaries. |
| **[[research/Vector_Knowledge_and_Telemetry|Vector Knowledge Base & Memory Datastore]]** | Mathematical foundation of 768-dim Cosine vector space, HNSW indexing ($M=16, ef=100$), and 11,814 chunked vectors in `dev_memory_main`. |
| **[[research/Empirical_Telemetry_and_RF_Analysis|Empirical Telemetry & RF Anomaly Modeling]]** | Log-distance path loss propagation math, continuous dwell-time anomaly scoring, and physical SDR telemetry. |
| **[[research/Research_Tracks_Taxonomy|26 Prioritized Research Tracks Taxonomy]]** | Comprehensive academic classification across AI security, Post-Quantum Cryptography, eBPF rootkits, and 5G NTN. |
| **[[research/Lab_Validated_Playbooks|Lab-Validated Defense Playbooks & SOAR]]** | Production-grade Sigma detection rules, Suricata signatures, and automated OpenWrt quarantine scripts. |
| **[[research/DFIR_and_Playbooks|Digital Forensics, Incident Response & eBPF]]** | Live memory acquisition, Volatility 3 kernel symbol forensics, and runtime eBPF telemetry auditing. |
| **[[research/Compliance_and_Governance|Regulatory Compliance, Zero Trust & AI Safety]]** | Control mappings across NIST SP 800-53 Rev 5, NIST SP 800-207 (Zero Trust), ISO 27001:2022, and EU AI Act. |
| **[[research/Lab_Requirements|Physical & Virtual Lab Specifications]]** | Hardware ledgers, network interface topology, SDR sensor arrays, and GPU compute specs. |
| **[[research/Sources_and_Matrix|Threat Intelligence Ingestion & Attack Matrix]]** | Curated OSINT feeds, Shodan vulnerability mapping, CVE indexing, and MITRE ATT&CK tactic mappings. |
| **[[research/Skills_and_Gaps|Security Methodology Skill Trees]]** | Granular breakdown of 2,574 security skill definitions, execution frameworks, and open research horizons. |
| **[[research/Tools_and_Telemetry|Operational Instrumentation & Approved Toolsets]]** | Command references, sandboxed execution binaries, and telemetry pipeline configurations. |

### LLM Control Planes, Agent Gateways & Arcana

| Research Track | Description | Key Technologies |
|---|---|---|
| **[[research/LLM_Control_Plane|Gemini CLI Workspace: Control & Data Plane]]** | Decoupled Control Plane (`llm-project`) and Data Plane (`llmdata-core`) orchestrating parallel subagents and SSE streams. | Python, SSE, Subagents |
| **[[research/MCP_Gateway_Tool_Router|MCP Gateway: Enterprise Model Context Protocol]]** | Stateful proxy and aggregator bridging diverse agent runtimes via Model Context Protocol. | TypeScript, MCP, Node |
| **[[research/Serverless_Cloudflare_MCP|Serverless Remote MCP on Cloudflare Workers]]** | Edge-native Model Context Protocol server executing tools on Cloudflare's distributed edge with sub-15ms SSE. | Workers, Edge, SSE |
| **[[research/Coral_Edge_TPU_Computer_Vision_NVR|Coral Edge TPU Computer Vision & Low-Latency NVR]]** | Google Coral Edge TPU coprocessor (100+ FPS real-time detection), `go2rtc` WebRTC broker, and tmpfs RAM buffers. | Coral TPU, WebRTC, Go |
| **[[research/Substrate_Digital_Nervous_System|Substrate — Digital Nervous System]]** | Distributed microservices backbone orchestrating multi-node telemetry and automated proactive agent loops. | Microservices, EventBus |
| **[[research/Local_LLM_Architecture|Zero-Trust Local LLM Ingress Architecture]]** | Hardware-accelerated localized LLM inference via Ollama, Qdrant vector retrieval, and Cloudflare SSE tunnels. | Ollama, Qdrant, Tunnels |
| **[[research/Codex_Arcana|Codex Arcana Growth Vault]]** | Systematic documentation of hard-won engineering lessons, root-cause analyses, and breakthrough solutions. | Knowledge Vault |

</section>

---

## 🌐 Sovereign Ecosystem Navigation

Part of the **[RPDev Sovereign Network](https://iamrp.dev)**:
- **Portfolio & Executive Summary**: [iamrp.dev](https://iamrp.dev)
- **Production Documentation Wiki**: [wiki.iamrp.dev](https://wiki.iamrp.dev)
- **RPDev Launcher Portal**: [launcher.iamrp.dev](https://launcher.iamrp.dev)
- **RPDev Feed Companion**: [feed.launcher.iamrp.dev](https://feed.launcher.iamrp.dev)
- **Software Distribution Hub**: [repo.iamrp.dev](https://repo.iamrp.dev)
- **Source Code & Organizations**: [github.com/RPDevs-Builds](https://github.com/RPDevs-Builds)

