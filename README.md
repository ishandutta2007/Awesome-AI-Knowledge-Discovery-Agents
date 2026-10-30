# Awesome AI Knowledge Discovery Agents 🤖🔍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-AI-Knowledge-Discovery-Agents/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ishandutta2007/Awesome-AI-Knowledge-Discovery-Agents/graphs/commit-activity)

> **A curated directory of leading SaaS platforms and open-source GitHub projects for AI-powered Enterprise Search, RAG with Citations, Permission-Aware Retrieval, Knowledge Graphs, and Autonomous Knowledge Agents.**

---

## 📖 Overview

Organizations generate mountains of unstructured intelligence scattered across disparate SaaS silos (Slack, Google Drive, Notion, Confluence, Jira, GitHub, Zendesk, Salesforce). Traditional keyword search fails across this fragmentation. 

**AI Knowledge Discovery Agents** bridge this gap by indexing distributed organizational data, adhering strictly to enterprise Access Control Lists (ACLs), synthesizing contextual answers with passage-level citations via Retrieval-Augmented Generation (RAG), and orchestrating multi-step agentic workflows.

This list tracks:
- **Commercial SaaS Platforms:** Fully managed, turn-key workplace intelligence and cognitive search engines.
- **Open-Source Systems & Frameworks:** Self-hostable, privacy-preserving, air-gapped, and local-first AI search infrastructure.

---

## 📊 Sector Overview & Market Dynamics

The AI-driven enterprise search and knowledge discovery sector is valued between **$6.4B and $7.5B** (projected to reach over **$14B+ by the early 2030s** at an 8.5%–14% CAGR, accelerated by enterprise generative AI and agentic RAG adoption). 

The market exhibits a **bifurcated hybrid structure: highly concentrated at the platform core, yet extensively fragmented across independent specialized vendors**. Tech hyperscalers (Microsoft 365 Copilot/Azure AI Search, Google Vertex AI Search, and ServiceNow) capture broad enterprise desktop mindshare; however, high corporate data fragmentation and strict access control requirements sustain a vibrant, fragmented ecosystem of specialized search engines (Glean, Coveo, Hebbia) and rapidly maturing open-source platforms (Onyx, PipesHub, RAGFlow, Khoj).

---

## 📑 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS & Hosted Enterprise Platforms](#-saas--hosted-enterprise-platforms)
- [Open-Source GitHub Projects](#-open-source-github-projects)
- [Architectural Patterns & Key Differentiators](#-architectural-patterns--key-differentiators)
- [How to Contribute](#-how-to-contribute)
- [Disclaimer & Security Considerations](#-disclaimer--security-considerations)

---

## 🏢 SaaS & Hosted Enterprise Platforms

| Product | Company Scale / Valuation | Pricing (Starting Tier) | Free Tier Limits / Trial | Core Capabilities & Best For |
|:---|:---|:---|:---|:---|
| **[Atlassian Rovo](https://www.atlassian.com/platform/artificial-intelligence)** | **$55B - $57B** Market Cap (NASDAQ: TEAM) | **$10/user/mo** (Jira/Confluence Cloud Standard tier; includes 25 pooled Rovo credits/seat/mo; excess at $0.01/credit) | **Forever-free plan capped at 10 users** (limited basic AI trials; no pooled Rovo credits) | Enterprise teamwork graph indexing Jira, Confluence, and 3rd-party connectors. Best for teams deeply invested in the Atlassian Cloud ecosystem. |
| **[Notion Q&A](https://www.notion.com/)** | **$11B - $12B** Valuation ($865M+ ARR) | **$20/user/mo** billed annually ($24 monthly on Business plan, which bundles full Notion AI, Notion Agent, and Enterprise Search) | **Forever-free plan with 20 complimentary Notion AI trial responses**; 30-day trial for Business plan | Unified AI search across Notion workspaces and connected tools (Slack, Google Drive, GitHub). Best for Notion-centric teams wanting zero-setup search. |
| **[Glean](https://www.glean.com/)** | **$7.2B** Valuation ($300M+ ARR) | **$45/user/mo** (enterprise packages typically range $45–$75/user/mo billed annually; minimum 100-seat contract size starting ~$45k–$50k/yr) | **No free tier**; 30-day custom enterprise pilot/POC upon sales approval | Comprehensive Work AI platform with 100+ native connectors, deep permission-aware ACL search, and custom agent builder. The commercial category leader. |
| **[Moveworks](https://www.moveworks.com/)** | **$2.85B** Acquisition by ServiceNow ($100M+ ARR) | **$15/employee/yr** (contract pricing ranges ~$15–$45/employee/yr based on total headcount; median enterprise ACV ~$130k/yr) | **No free tier**; custom vendor sandbox/guided POC for enterprise buyers | Autonomous agentic employee support resolving IT, HR, and facilities tickets across enterprise systems. Best for enterprise IT automation. |
| **[Hebbia](https://www.hebbia.com/)** | **$700M** Valuation ($13M+ ARR) | **$250/seat/mo** (billed annually at ~$3,000 to $15,000+/seat/yr for specialized analyst seats) | **No free tier**; guided institutional pilot on select deal rooms/document sets | "Matrix" multi-agent tabular analysis over millions of documents, SEC filings, contracts, and data rooms. Best for private equity, investment banking, and legal due diligence. |
| **[Coveo](https://www.coveo.com/)** | **$330M - $350M** Market Cap (TSX: CVO) | **$990/mo** (Coveo for Salesforce Pro+ starting tier billed annually; core enterprise search suites scale upwards of $10,000/mo) | **No free tier**; 30-day proof-of-concept trial available through enterprise sales | Enterprise cognitive search and relevance generative answering (RGA) engine with fine-grained index tuning and deep commerce/service integrations. |
| **[GoSearch](https://www.gosearch.ai/)** | **$108M** Valuation / ~$27M Funding ($25M–$50M ARR) | **$20/user/mo** (Pro plan with no seat minimums, unlimited searches, unlimited GoAI conversations, and advanced LLM access) | **Forever-free tier capped at 10 searches/day**, 3 GoAI queries/day, and 1 file upload (5 MB max) | Fast-to-deploy multimodal enterprise search across workplace tools, unified with GoLinks workspace navigation. |
| **[Guru](https://www.getguru.com/)** | **$70M+** Total Funding (~$15M–$25M ARR) | **$15/user/mo** (historical starter base tier; custom-scoped quotes for enterprise AI knowledge agents) | **30-day free trial** with access to core AI search and verification extensions (no credit card required) | AI-powered verified knowledge cards with contextual answer delivery directly inside Slack, MS Teams, and web browsers. |
| **[Dashworks](https://www.dashworks.ai/)** | **$12M+** Funding (Acquired by HubSpot) | **$12/seat/mo** ($10/seat/mo billed annually on Team plan; Business plan starts at $15/seat/mo with 10-seat min) | **14-day free trial** with full access to 50+ integrations and Slack bot (no credit card required) | Turn-key AI knowledge assistant integrating 50+ SaaS apps, offering instant conversational answers and automated workflows. |
| **[Slite AI](https://slite.com/)** | **$15.5M** Total Funding (~$5M ARR) | **$10/user/mo** (Basic plan billed annually; Pro plan at $20/user/mo adds unlimited AI search and 50 agent credits/seat/mo) | **14-day free trial** with full document collaboration and AI Q&A features (no credit card required) | Collaborative team wiki with built-in "Ask AI" assistant and automated knowledge verification. |

---

## 💻 Open-Source GitHub Projects

All repositories are sorted descending by community GitHub star count. Star counts reflect real-time live metrics.

| Project | GitHub Stars | License | Architecture & Key Features | Deployment & Best For |
|:---|:---:|:---:|:---|:---|
| **[Open WebUI](https://github.com/open-webui/open-webui)** | [![Stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social&color=white)](https://github.com/open-webui/open-webui/stargazers) | Open Source (Custom) | Self-hosted, user-friendly AI interface with built-in RAG, document ingestion, web search, multi-model support, Ollama orchestration, and granular RBAC. | Docker / Kubernetes. Best for organizations wanting an internal private ChatGPT-like knowledge portal over local or cloud models. |
| **[RAGFlow](https://github.com/infiniflow/ragflow)** | [![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers) | Apache-2.0 | Deep document understanding engine based on OCR and vision-language extraction. Handles complex tables, slide decks, PDFs, multi-modal cross-referencing, and grounded citations. | Docker Compose. Best for enterprises processing complex, unstructured documents (PDFs, scans, manuals) needing high-accuracy extraction. |
| **[MetaGPT](https://github.com/geekan/MetaGPT)** | [![Stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social&color=white)](https://github.com/geekan/MetaGPT/stargazers) | MIT | Multi-agent collaborative framework that assigns distinct roles (architect, engineer, QA, researcher) to autonomously discover, synthesize, and execute knowledge-intensive software workflows. | Python CLI / Docker. Best for complex multi-agent discovery and automated research pipelines. |
| **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** | [![Stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social&color=white)](https://github.com/Mintplex-Labs/anything-llm/stargazers) | MIT | All-in-one AI enterprise knowledge base application. Offers multi-user workspaces, document vectorization, web scraping, custom agent skills, and full local LLM/vector DB support. | Desktop / Docker / Cloud. Best for teams wanting an out-of-the-box local or cloud knowledge management tool. |
| **[Khoj](https://github.com/khoj-ai/khoj)** | [![Stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers) | AGPL-3.0 | Personal AI research assistant and second brain. Indexes local documents (PDF, Markdown, Org-mode), GitHub repos, Notion, and web; features scheduled routines and multimodal voice/chat. | Self-hosted (Docker) or Khoj Cloud. Best for researchers, technical writers, and power users wanting an autonomous personal knowledge assistant. |
| **[Onyx (formerly Danswer)](https://github.com/danswer-ai/onyx)** | [![Stars](https://img.shields.io/github/stars/danswer-ai/onyx?style=social&color=white)](https://github.com/danswer-ai/onyx/stargazers) | MIT | Full-featured open-source enterprise search and chat platform. Connects to 35+ enterprise apps (Slack, Drive, Confluence, Jira, GitHub), respects document permissions, provides inline citations, and supports custom LLM agents. | Docker Compose / Helm / Kubernetes. Best for companies seeking an open-source, permission-aware Glean alternative. |
| **[STORM](https://github.com/stanford-oval/storm)** | [![Stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social&color=white)](https://github.com/stanford-oval/storm/stargazers) | MIT | Stanford-developed LLM knowledge curation engine. Uses multi-perspective question-asking and simulated discourse to autonomously discover information across the web and synthesize comprehensive, citation-backed Wikipedia-style reports. | Python CLI. Best for automated deep research, literature reviews, and topic briefing. |
| **[Docmost](https://github.com/docmost/docmost)** | [![Stars](https://img.shields.io/github/stars/docmost/docmost?style=social&color=white)](https://github.com/docmost/docmost/stargazers) | AGPL-3.0 | Modern open-source collaborative wiki and documentation software with real-time editing, nested spaces, permission governance, and native AI answering integrations. | Docker. Best for organizations wanting an open-source alternative to Notion or Confluence with AI-powered search. |
| **[PandaWiki](https://github.com/chaitin/PandaWiki)** | [![Stars](https://img.shields.io/github/stars/chaitin/PandaWiki?style=social&color=white)](https://github.com/chaitin/PandaWiki/stargazers) | Open Source | AI-native documentation and technical wiki system. Features multi-source ingestion, vector retrieval RAG pipelines, embeddable widgets, and interactive Q&A bots for product documentation. | Containerized / Self-hosted. Best for engineering and developer-relations teams building AI-assisted developer portals. |
| **[PipesHub](https://github.com/pipeshub-ai/pipeshub-ai)** | [![Stars](https://img.shields.io/github/stars/pipeshub-ai/pipeshub-ai?style=social&color=white)](https://github.com/pipeshub-ai/pipeshub-ai/stargazers) | Apache-2.0 | Self-hosted enterprise AI search and agent platform. Features 50+ enterprise connectors, strict permission-aware ACL inheritance, hybrid vector + Neo4j knowledge graphs, MCP server support, and agent action guardrails. | Docker Compose / On-Prem / Air-gapped. Best for organizations requiring an on-premise Glean alternative with knowledge graph navigation. |
| **[XWiki Platform](https://github.com/xwiki/xwiki-platform)** | [![Stars](https://img.shields.io/github/stars/xwiki/xwiki-platform?style=social&color=white)](https://github.com/xwiki/xwiki-platform/stargazers) | LGPL-2.1 | Mature enterprise wiki engine with extensive extension ecosystem. Integrates LLM applications and semantic vector search filtered strictly according to user view rights and group permissions. | Docker / Debian / Tomcat. Best for large enterprises, universities, and government agencies with strict on-premise documentation policies. |
| **[Viglet Turing ES](https://github.com/openviglet/turing-ce)** | [![Stars](https://img.shields.io/github/stars/openviglet/turing-ce?style=social&color=white)](https://github.com/openviglet/turing-ce/stargazers) | Apache-2.0 | Open-source enterprise cognitive search and Generative AI platform. Implements hybrid BM25 + kNN vector search (Solr, Elasticsearch, embedded Lucene), faceted semantic navigation, MCP servers, and inline RAG citations. | Docker Compose / Kubernetes. Best for enterprises seeking a self-hosted Coveo or Algolia alternative with complete relevance control. |
| **[OpenBeam](https://github.com/kuluruvineeth/openbeam)** | [![Stars](https://img.shields.io/github/stars/kuluruvineeth/openbeam)](https://github.com/kuluruvineeth/openbeam/stargazers) | AGPL-3.0 | Multi-source knowledge discovery unifying SaaS data with physical IoT operations (Samsara, Verkada, MQTT, BACnet). Features 6 pre-built autonomous agents on Temporal cron schedules and sub-200ms hybrid search. | Docker Compose / Edge (SQLite). Best for industrial, logistics, and facilities enterprises bridging digital and physical telemetry. |
| **[okforge](https://github.com/okforge/okforge)** | [![Stars](https://img.shields.io/github/stars/okforge/okforge?style=social&color=white)](https://github.com/okforge/okforge/stargazers) | Open Source | Local-first knowledge base engine that compiles unstructured documents into an interlinked Markdown wiki with page citations. Features locate-then-read query agents and MCP server integration. | Python CLI (`pip install okforge`). Best for privacy-focused individuals and analysts wanting offline, portable citation-backed knowledge bases. |
| **[Synaptane](https://github.com/synaptane/synaptane)** | [![Stars](https://img.shields.io/github/stars/synaptane/synaptane?style=social&color=white)](https://github.com/synaptane/synaptane/stargazers) | AGPL-3.0 | Git-backed self-hosted team wiki with embedded AI assistant, local Ollama semantic search, MCP connectors for Claude/ChatGPT, and automated knowledge hygiene routines. | Docker Compose. Best for small developer teams seeking a Git-native wiki with AI context. |
| **[Red Arch KM2](https://github.com/redarchlabs/red-arch-km)** | [![Stars](https://img.shields.io/github/stars/redarchlabs/red-arch-km?style=social&color=white)](https://github.com/redarchlabs/red-arch-km/stargazers) | Apache-2.0 | Role-based enterprise document brain and governed agent application builder. Combines PostgreSQL RLS, Qdrant vectors, Neo4j graphs, and field-level permission enforcement. | Docker Compose. Best for security teams needing governed, verifiable multi-tenant AI agents. |

---

## 🏗️ Architectural Patterns & Key Differentiators

When evaluating AI Knowledge Discovery and Enterprise Search solutions, tools generally fall into three distinct architectural categories:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        Enterprise Search Layer                         │
│  (Glean, Onyx, PipesHub, Turing ES, Coveo, Moveworks)                  │
│  • 50–100+ connectors (Slack, Google Drive, Jira, GitHub)             │
│  • Pre-query Access Control List (ACL) permission filtering           │
│  • Hybrid Vector (Qdrant/Milvus) + Keyword (BM25/Solr) + Graph (Neo4j) │
└────────────────────────────────────────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                      Workspace & AI Wiki Hubs                          │
│  (Notion Q&A, Atlassian Rovo, Docmost, PandaWiki, XWiki)              │
│  • Collaborative documentation native to the team's authoring workflow │
│  • Scoped workspace search and conversational Q&A                      │
│  • Native agent authoring and automated meeting/page summaries         │
└────────────────────────────────────────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   Local-First & Autonomous Research                    │
│  (AnythingLLM, Khoj, STORM, okforge, Synaptane)                        │
│  • Air-gapped, zero data retention, local LLM execution (Ollama)      │
│  • Model Context Protocol (MCP) servers for Cursor / Claude Desktop    │
│  • Deep web discourse simulation and synthesized briefings            │
└────────────────────────────────────────────────────────────────────────┘
```

### 1. Permission-Aware Retrieval (ACL Enforcement)
* **Pre-Query Filtering (Enterprise Standard):** Search queries evaluate the user's authenticated identity against the source document's Access Control Lists (ACLs) *before* similarity ranking occurs. A user never receives vector results or synthesized LLM answers derived from private files they lack credentials to view.
* **Post-Query Filtering (Unsafe for Enterprise):** Retrieving top-k chunks blindly and filtering afterward leaks sensitive metadata and causes truncated or hallucinated answers.

### 2. Retrieval Mechanisms: Vector vs. Hybrid vs. Graph
* **Pure Vector (Dense):** Captures semantic intent but misses exact codes, SKUs, ticket keys (`PROJ-1042`), and names.
* **Hybrid Search (Dense + BM25 Sparse):** Uses Reciprocal Rank Fusion (RRF) to combine keyword precision with semantic embeddings.
* **Graph-RAG (Knowledge Graphs):** Maps organizational hierarchies, entity relationships, and cross-document references (e.g., Neo4j) to prevent hallucinated relationship queries.

### 3. Model Context Protocol (MCP) Integration
Modern knowledge platforms now expose **MCP endpoints**, allowing developer environments (Cursor, Claude Desktop, VS Code) to securely query the enterprise knowledge graph as an external memory tool.

---

## 🤝 How to Contribute

We welcome community contributions! To add a new platform or update existing metrics:

1. **Fork** this repository.
2. Ensure your proposed addition meets the scope (Enterprise Search, RAG with Citations, Permission-Aware Access, or Autonomous Knowledge Agents).
3. If proposing a **SaaS platform**, include starting pricing and explicit free tier/trial limits.
4. If proposing an **Open-Source project**, verify that the repo is publicly accessible and provides an active open-source license.
5. Create a descriptive commit and submit a **Pull Request**.

---

## 🔒 Disclaimer & Security Considerations

- **Community Maintained:** This repository is a curated informational index and does not represent an endorsement of any vendor or codebase.
- **Enterprise Data Compliance:** When indexing enterprise repositories containing PII, HIPAA, or intellectual property, thoroughly audit connector permissions, data retention policies, and SOC2/ISO-27001 compliance.
- **Local vs. Cloud Execution:** For air-gapped environments or strictly regulated entities, prefer self-hosted platforms with local model weights (via Ollama/vLLM) and isolated vector stores.
