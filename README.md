# Awesome-AI-Knowledge-Discovery-Agents

# Awesome-AI-Knowledge-Discovery-Agents
**Top AI Knowledge Discovery Agents (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Enterprise Search, RAG with Citations, Permission-Aware Retrieval & Agentic Knowledge Access*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Knowledge Discovery & Agents**. These tools enable organizations to unify scattered knowledge across SaaS apps, wikis, and code repositories, then surface it through AI chat with citations, semantic search, and agentic workflows—from fully managed enterprise platforms with deep connectors and governance to self-hosted systems that give teams complete control over their data and model choices.

**Examples** include Glean, Atlassian Rovo, Guru, Coveo, Hebbia, GoSearch, Dashworks, Notion Q&A, Slite AI, and Moveworks (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, enterprise search, and open RAG infrastructure. **Critical note**: The open-source space here has matured significantly—PipesHub and Turing are production-oriented alternatives to Glean and Coveo—but no open-source project matches Glean's 100+ connector breadth or Moveworks' agentic action execution at enterprise scale. The projects below range from full enterprise search platforms to local-first knowledge compilers and agent orchestrators.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Glean](https://www.glean.com/)**
  **Enterprise AI search and knowledge discovery** platform connecting 100+ SaaS apps with permission-aware retrieval and AI assistants. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: large enterprises wanting the most mature, connector-rich search layer across their entire SaaS stack.

- **[Atlassian Rovo](https://www.atlassian.com/platform/artificial-intelligence)**
  **AI teammate within Atlassian Cloud** with Teamwork Graph connecting Jira, Confluence, and third-party connectors. **Pricing**: Credits in cloud subscription; extra usage $0.01 per credit . **Free tier**: Limited credits. **Best for**: organizations deeply invested in Atlassian wanting native AI search across their workspace.

- **[Guru](https://www.getguru.com/)**
  **AI-powered knowledge management** with verified answers and contextual delivery in Slack, Teams, and browsers. **Pricing**: Quote-only; per-user tiers. **Free tier**: None. **Best for**: teams wanting curated, verified knowledge cards rather than open-ended search.

- **[Coveo](https://www.coveo.com/)**
  **AI-powered enterprise search and relevance** platform with commerce and service applications. **Pricing**: Quote-only; metered by records/queries/seats . **Free tier**: None. **Best for**: enterprises wanting relevance tuning and analytics across complex content sources.

- **[Hebbia](https://www.hebbia.com/)**
  **AI knowledge discovery for document-heavy workflows** (finance, legal, due diligence). **Pricing**: Quote-only. **Free tier**: None. **Best for**: professionals needing deep analysis across large document sets, not general enterprise search.

- **[GoSearch](https://www.gosearch.ai/)**
  **AI enterprise search** with connectors and personalized results. **Pricing**: Quote-only. **Free tier**: Trial available. **Best for**: mid-market teams wanting a Glean alternative with faster deployment.

- **[Dashworks](https://www.dashworks.ai/)**
  **AI knowledge assistant** with 50+ connectors and Slack/Teams integration. **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting an AI assistant that answers questions across connected apps.

- **[Notion Q&A](https://www.notion.com/)**
  **AI search within Notion** workspaces. **Pricing**: Included with Notion AI add-on; per-user. **Free tier**: Limited AI trials. **Best for**: Notion-centric teams wanting AI search without third-party tools.

- **[Slite AI](https://slite.com/)**
  **AI-powered knowledge base** with Ask AI and collaborative docs. **Pricing**: Quote-only; per-user tiers. **Free tier**: Limited. **Best for**: teams wanting a wiki with built-in AI Q&A.

- **[Moveworks](https://www.moveworks.com/)** (ServiceNow)
  **AI employee support** with agentic resolution across IT, HR, and finance systems. **Pricing**: Quote-only; requires ServiceNow licensing post-acquisition. **Free tier**: None. **Best for**: enterprises wanting AI that takes actions (ticket creation, access requests), not just answers questions.

## Open-Source GitHub Projects

- **[PipesHub](https://github.com/pipeshub-ai/pipeshub-ai)**
  **Open-source, self-hosted enterprise AI search and agent platform** (Apache 2.0) — **the most direct open-source alternative to Glean**, with ~3,850 GitHub stars and active development . **Features**: **50+ connectors** (Slack, Jira, GitHub, Google Drive, Notion, Confluence, Salesforce, Zendesk, Microsoft 365); **permission-aware search**—inherits source app permissions so users only see what they're allowed to see; **knowledge graph** (Neo4j/ArangoDB) for structural relationships; **hybrid vector + graph search** (Qdrant); **RAG with passage-level citations**; **AI agent builder** with no-code interface and Python/Go/TypeScript SDKs; **MCP server** for Claude, Cursor, VS Code; **Bring Your Own Model** (OpenAI, Anthropic, Google, Mistral, or local Ollama); **code graphs** for repository analysis (v1.0.0) ; guardrails for agent actions (delete requires approval, SQL runs read-only by default) . **Tech stack**: Python (backend), TypeScript/React (UI), Qdrant, Neo4j, MongoDB, Redis. **Deploy**: Self-hosted (Docker Compose), VPC, on-premise, or air-gapped . **Trade-off**: **Newer than Glean**—connector depth and polish are still maturing compared to the commercial leader. Agentic action execution is more limited than Moveworks. **Best for**: organizations wanting a self-hosted Glean alternative with permission-aware search, citations, and agent capabilities—without sending data to a vendor cloud.

- **[Viglet Turing ES](https://github.com/openviglet/turing-ce)**
  **Open-source enterprise search + generative AI platform** (Apache 2.0) — **the most mature open-source alternative to Coveo and Algolia**, built on production search engines . **Features**: **Hybrid BM25 + kNN vector search** with Reciprocal Rank Fusion; **faceted semantic navigation** (spotlights, targeting rules, autocomplete, multi-language); **RAG chat with inline citations**; **AI agents** with native provider tools (web search, code execution); **MCP servers**; **multi-engine support** (Apache Solr, Elasticsearch, embedded Lucene—swap without rewriting); **indexing API** with schema-as-code; **connectors** via Viglet Dumont (Adobe AEM, WordPress, databases, filesystem, web crawls); **Apache Tika** for PDF/Office parsing. **Tech stack**: Java (Spring Boot), React 19 (admin console), Solr/Elasticsearch/Lucene. **Deploy**: Docker Compose (full stack), Kubernetes manifests, or packaged installers . **Trade-off**: **Search-engine-centric**—requires Solr/Elasticsearch expertise. Not a plug-and-play SaaS replacement; you configure indexing pipelines and relevance tuning. **Best for**: organizations wanting a Coveo alternative with full control over search infrastructure and no per-query metering—especially in regulated or air-gapped environments.

- **[Red Arch Knowledge Manager (KM2)](https://github.com/redarchlabs/red-arch-km)**
  **Open-source, role-based platform for organizational knowledge** (Apache 2.0) — **the most feature-complete open-source knowledge platform with governed AI agents** found in this research. **Features**: **Enterprise document brain** with RAG, passage-level citations, vector search, and knowledge graph; **no-code application layer** (custom entities, forms, views, dashboards, BPMN-style workflows); **governed org of AI agents** with model tiering, authority engine, approvals, and schedules; **fine-grained RBAC** down to field level (`server_only`, `workflow_only`) with PostgreSQL Row-Level Security; **in-app assistant** that can author entities, forms, views, and workflows on request; **multi-tenant isolation**; release-based change management with diff/preview/rollback . **Tech stack**: FastAPI (Python), Next.js (React), PostgreSQL 18 (RLS), Qdrant, Neo4j, Redis, MinIO, Clerk (OIDC). **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Complex platform**—requires operational maturity to deploy and govern. Clerk dependency for authentication. Go rewrite of core services is in progress but Python services remain authoritative . **Best for**: organizations wanting an enterprise knowledge platform with truly governed AI agents and field-level security—not just search, but a foundation for building knowledge apps.

- **[OpenBeam](https://github.com/kuluruvineeth/openbeam)**
  **Open-source Glean for SaaS and the physical world** (AGPL) — **the most ambitious open-source project in scope**, unifying digital and physical data sources with autonomous agents . **Features**: **87 connectors** spanning SaaS (Slack, GitHub, Notion, Linear, Salesforce, Jira, Gmail), IoT (Samsara, Verkada, AWS IoT), and industrial protocols (MQTT, OPC-UA, BACnet); **hybrid semantic + keyword search** with sub-200ms p99 latency; **AI agents** with 100+ composable tools; **six pre-built autonomous agents** (Knowledge Digest, Stale Content Detector, Connector Health, Search Quality, Onboarding Curator, Compliance Watchdog) on Temporal cron schedules with approval gating; **MCP server**; **permission-aware**; **edge-ready** with offline SQLite deployment . **Tech stack**: Go (CLI), Docker Compose. **Deploy**: Self-hosted or edge. **Trade-off**: **Ambitious scope but early-stage**—connector reliability and agent quality across 87 sources will vary. The physical/IoT focus is unique but may be overkill for pure digital knowledge discovery. **Best for**: organizations wanting to unify SaaS and operational/physical data in one search layer—especially industrial, logistics, or facilities teams.

- **[okforge](https://pypi.org/project/okforge/)**
  **Local-first LLM knowledge-base engine** (license per repo) — **the most privacy-focused open-source option**, compiling documents into an interlinked wiki before retrieval . **Features**: **Compiles sources into curated Markdown wiki** (per-document summaries, cross-document concept/entity pages, extracted images) with **(p. N) citations** back to source; **OKF (Open Knowledge Format)** for portability—wiki readable in Obsidian or any editor; **locate-then-read query agent** (reads curated pages first, then drills with `grep_wiki`) rather than re-embedding everything; **MCP server** (stdio and Streamable HTTP) for Claude, Cursor, etc.; **any OpenAI-compatible LLM** (local llama.cpp, Ollama, OpenRouter, hosted providers); **vision-OCR plugin** for scanned documents . **Tech stack**: Python (CLI), Markdown output. **Deploy**: Local CLI (`pip install okforge`); MCP server runs locally. **Trade-off**: **Single-user CLI tool, not a multi-tenant enterprise platform**—no permissions, no connectors to SaaS apps, no web UI. It is a personal/team knowledge compiler, not a Glean replacement. **Best for**: individuals and small teams wanting a portable, citation-backed knowledge base they can query locally or via MCP—without cloud dependency.

- **[PandaWiki](https://landscape.jimmysong.io/projects/pandawiki/)**
  **Open-source AI-native knowledge base system** (license per Chaitin) — **a focused, embeddable knowledge base for docs and FAQs** . **Features**: **Multi-source ingestion** (web pages, RSS, Markdown, HTML, Word, PDF); **vector retrieval with RAG pipelines**; semantic search and QA; **embeddable frontend plugins and SDKs** for websites and chatbots; TypeScript and Go components; containerized deployment . **Tech stack**: TypeScript, Go, vector database. **Deploy**: Self-hosted (containerized). **Trade-off**: **Narrower scope**—knowledge base for docs/FAQs, not enterprise-wide search across SaaS apps. No permission-aware connectors or agentic actions. **Best for**: teams wanting an intelligent documentation/FAQ center with RAG, embeddable into their product or website.

- **[Khoj](https://github.com/khoj-ai/khoj)**
  **Open-source AI personal research assistant** (AGPL) — **the most mature open-source alternative to Notion Q&A and Rovo for personal/small-team use**, with ~34,600 GitHub stars . **Features**: Cross-document and web search; research paper management with citations; personal agent building; local AI execution; multimodal support; available as web and desktop app; API and SDK . **Tech stack**: Python, Django, PostgreSQL. **Deploy**: Self-hosted or Khoj Cloud. **Trade-off**: **Personal/small-team focus**—not enterprise search with SaaS connectors or permission inheritance. Designed for individual knowledge workers, not organizational discovery. **Best for**: researchers and individuals wanting an AI assistant over their own documents and notes with local execution.

- **[Synaptane](https://pypi.org/project/synaptane/)**
  **Self-hosted wiki with AI and MCP** (AGPL, pre-release) — **a privacy-first team wiki with AI assistant capabilities** . **Features**: **Git-backed wiki** with spaces; **AI assistant** for queries and routines; **MCP server** for Claude.ai and ChatGPT connectors; semantic search with embeddings (Ollama works locally); **OAuth and SSO**; inbox and nightly tidy-up routines; French/English UI . **Tech stack**: Python, Docker, Git. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Alpha software**—the project explicitly states "expect rough edges," API and config may change, and some features are untested. No enterprise connectors or permission-aware search across SaaS apps. **Best for**: small teams wanting a self-hosted wiki with AI Q&A and MCP integration, willing to accept pre-release stability.

### Additional Strong Open-Source Options

- **XWiki (with LLM Application)** — Enterprise wiki (LGPL-2.1) with configurable AI answer filtering by view rights. **Note**: Wiki-first; AI is an add-on, not the core. Permission behavior must be verified before use with restricted content . **Best for**: organizations wanting a mature wiki with optional AI search.
- **Open WebUI** — Self-hosted LLM interface (license per repo) with knowledge base support. **Note**: Access is per knowledge base, not per document—unsuitable for mixed-permission content without segmenting into separate KBs . **Best for**: teams wanting a private ChatGPT-like interface over their own models.
- **Docmost** — Collaborative wiki with AI Answers (AGPL for Community). **Note**: AI Answers requires Business/Enterprise license; searches only visible spaces . **Best for**: teams wanting a modern wiki with native AI.

**Frameworks for building custom systems**: Combine **PipesHub** as the permission-aware enterprise search and agent layer with **Viglet Turing** for hybrid search and relevance tuning, **Red Arch KM2** for governed agent workflows and field-level security, and **okforge** for local-first knowledge compilation—creating a knowledge discovery stack. **None of these match Glean's 100+ connectors or Moveworks' agentic action breadth**; organizations needing the deepest connector coverage or action execution will require commercial platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI knowledge discovery platforms handling enterprise data must comply with data protection regulations (GDPR, CCPA, etc.) and implement permission-aware retrieval—**search must filter by the caller's permissions before returning results**, not after.
- **The "permission-aware enterprise search" vs. "local-first knowledge compiler" vs. "AI wiki assistant" distinction is critical.** **PipesHub, Viglet Turing, Red Arch KM2, OpenBeam, and Glean** are **enterprise search platforms**—they connect to SaaS apps, inherit permissions, and index at organizational scale. **okforge** is a **local-first compiler**—it builds a portable wiki from documents you feed it, with no SaaS connectors or multi-user permissions . **PandaWiki, Khoj, and Synaptane** are **focused knowledge tools**—for docs/FAQs, personal research, or team wikis respectively. **Choose based on whether you need organization-wide discovery, personal knowledge management, or a documentation Q&A layer.**
- **PipesHub is the strongest open-source Glean alternative** with 50+ connectors, permission inheritance, knowledge graphs, and agent builder . **The trade-off**: it is newer than Glean, and connector depth is still maturing. v1.0.0 added code graphs and tighter agent guardrails, signaling active production hardening .
- **Viglet Turing is the strongest open-source Coveo alternative** for search relevance and hybrid retrieval, built on Solr/Elasticsearch . **The trade-off**: it requires search-engine expertise and does not provide SaaS connectors out of the box (Viglet Dumont handles AEM/WordPress/databases).
- **Red Arch KM2 is uniquely ambitious** with governed AI agents, field-level RBAC, and no-code app building . **The trade-off**: complexity—it is a platform to build on, not a turnkey search tool.
- **okforge is not an enterprise search replacement.** It has no SaaS connectors, no permission model, and no web UI for teams . **It is a privacy-first, local knowledge compiler** for individuals who want citation-backed answers over their own documents—and it works exceptionally well for that use case.
- **Pricing opacity is universal across commercial vendors.** Glean, Guru, Coveo, Hebbia, GoSearch, Dashworks, Slite, and Moveworks require sales contact. Atlassian Rovo uses credit-based pricing ($0.01/credit) . Notion Q&A requires the AI add-on. **Validate with direct vendor conversations against your connector count and user base.**
- Self-hosted open-source solutions require proper infrastructure (vector databases, graph databases, workers), model API key management or local GPU provisioning, and ongoing maintenance. **Enterprise knowledge data is highly sensitive**—ensure your deployment meets your organization's security and privacy requirements, and **verify permission inheritance works correctly before exposing search to users**.

---

**Made for developers, IT teams, and organizations building transparent AI knowledge discovery solutions.**
Let's make AI Knowledge Discovery & Agents more open, data-driven, and permission-aware.
