# Awesome-Real-Time-Regulatory-Change-Monitors

## Top Real-Time Regulatory Change Monitors Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Regulatory Radar, Control Mapping & Compliance Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real-Time Regulatory Change Monitors**. These tools crawl government and regulatory websites, detect new publications and amendments, map them to your internal control frameworks, and surface a prioritized triage queue — turning regulatory chaos into a manageable workflow.

**Examples** include Regology, Compliance.ai, FiscalNote, CUBE ContentIQ, Single Rulebook, Corlytics, Ascent RegTech, Thomson Reuters Regulatory Intelligence, Wolters Kluwer OneSumX, and LexisNexis (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom regulator feeds, and transparent compliance mapping — ideal for fintech compliance teams prioritizing data sovereignty, developers building RegTech pipelines, and organizations avoiding enterprise-priced closed-source platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Regology](https://www.regology.com/)**  
  AI-powered regulatory intelligence platform with real-time tracking across global jurisdictions, control mapping, and change impact analysis.

- **[Compliance.ai](https://www.compliance.ai/)**  
  Regulatory change management platform with AI-curated content, personalized alerts, and compliance workflow automation.

- **[FiscalNote](https://www.fiscalnote.com/)**  
  Policy and regulatory intelligence platform with real-time legislative tracking, risk analysis, and stakeholder mapping.

- **[CUBE ContentIQ](https://cube.global/)**  
  Global regulatory intelligence platform covering 1,800+ regulators with AI-powered change detection and control mapping.

- **[Single Rulebook](https://www.singlerulebook.com/)**  
  Regulatory intelligence platform focused on EU financial services regulation with structured rule mapping.

- **[Corlytics](https://www.corlytics.com/)**  
  Regulatory risk intelligence platform with enforcement action tracking, fine analytics, and compliance risk scoring.

- **[Ascent RegTech](https://www.ascentregtech.com/)**  
  AI-powered regulatory compliance platform with obligation extraction, rule mapping, and change management.

- **[Thomson Reuters Regulatory Intelligence](https://www.thomsonreuters.com/)**  
  Enterprise regulatory intelligence with global coverage, expert analysis, and compliance workflow tools.

- **[Wolters Kluwer OneSumX](https://www.wolterskluwer.com/)**  
  Regulatory compliance suite with change management, reporting, and risk analytics for financial institutions.

- **[LexisNexis](https://www.lexisnexis.com/)**  
  Legal and regulatory research platform with news, analysis, and compliance monitoring capabilities.

## Open-Source GitHub Projects

- **[GRCX](https://github.com/grcx-dev/grcx)**  
  **Open-source regulatory radar for financial services.** Monitors publications from Bank of England, FCA, MAS, SEC, and ESMA via IMAP, RSS, and HTTP feeds [citation:9]. Maps each new publication to your control frameworks (ISO 27001, FCA SYSC, MAS TRM, NIST CSF, BCBS 239, SOC 2) using an LLM [citation:9]. Features severity triage, affected control highlighting, and a prioritized queue [citation:9]. **Cryptographically chained audit log** (SHA-256, append-only, verifiable) for every detection and assessment [citation:9]. Human override feeds back into the resolver for accuracy improvement [citation:9]. Adding a new regulator is a config change in `grcx.yaml`, not a code change [citation:9]. Runs with `grcx watch --poll 900` and a Flask dashboard on port 5001 [citation:9].

- **[GovPing MCP Server](https://www.npmjs.com/package/govping-mcp-server)**  
  **Free regulatory intelligence for AI agents.** Searches 27,000+ regulatory changes across 2,000+ government sources worldwide [citation:1]. Publishes structured data in **ORCA format** (Open Regulatory Change Annotation) with 40+ fields across 7 groups: identity, authority, classification, taxonomy, temporal, intelligence, and references [citation:1]. Covers FDA, SEC, OSHA, EPA, CFPB, FTC, DOJ, FINRA, state AGs, courts, and more [citation:1]. Checked hourly to daily depending on source [citation:1]. **No API key required** — public data, open access [citation:1]. MIT licensed. Available as MCP server for Claude Desktop, Harvey, OpenAI, and Claude Code [citation:1]. Rate limit: 100 requests/hour per IP [citation:1].

- **[Probo](https://github.com/getprobo/probo)**  
  **Open-source GRC platform with full regulatory compliance lifecycle.** ISC licensed, self-hostable with Docker [citation:2]. Covers risk management, controls and frameworks (ISO 27001, SOC 2, GDPR, NIST AI RMF, EU AI Act, and more), vendor risk, data privacy (DPIA/TIA), access reviews, audit programs, and document approval workflows [citation:2]. **270+ MCP tools** expose every entity and operation for AI agent integration [citation:2]. CLI (`prb`), GraphQL API, and n8n community node for no-code automation [citation:2]. Policy-based RBAC, immutable audit logs, electronic document sign-off, and evidence chains [citation:2].

- **[TrustOps Security Data Lake](https://pypi.org/project/trustops-security-data-lake/)**  
  **Open-source, self-hosted compliance automation platform.** Apache-2.0 licensed with no per-seat fees [citation:7]. Includes **20 framework packs** (SOC 2, ISO 27001, NIST CSF 2.0, NIST AI RMF, CIS Controls, CMMC 2.0, EU AI Act, NIST 800-53, FedRAMP, HIPAA, PCI DSS, GDPR, NIS2, DORA) with **94 reusable safeguards** and **2,245 catalogued requirements** [citation:7]. Common Control Framework maps safeguards to framework requirements with reviewed or proposed status [citation:7]. Features audit workflow, readiness assessments, trust-center shares, access reviews, and OSCAL export [citation:7]. Deploy via Docker Compose, Helm, or EKS Terraform [citation:7].

- **[VerifyWise](https://github.com/verifywise/verifywise)**  
  **Open-source AI governance platform** for managing EU AI Act, ISO/IEC 42001, and NIST AI RMF compliance [citation:10]. Central repository for AI systems, models, agents, applications, and suppliers with structured inventory [citation:10]. Conducts risk assessments, documents governance decisions, performs evaluations, assigns responsibilities, and tracks mitigation measures [citation:10]. Maps governance activities across multiple frameworks simultaneously — evidence recorded once is reused across EU AI Act and ISO 42001 obligations [citation:10]. 360 GitHub stars [citation:10].

- **[Agent-Gov](https://pypi.org/project/agent-gov/)**  
  **AI agent governance and compliance engine with policy enforcement.** Declarative YAML policy schema with versioned rules and per-rule severity [citation:6]. **Four built-in rule types** — PII check, role check, cost limit, and keyword block [citation:6]. **Compliance framework stubs for EU AI Act, GDPR, HIPAA, and SOC 2** that map rule violations to specific regulatory articles and controls [citation:6]. Append-only audit logger with structured JSON entries and search API [citation:6]. Apache 2.0 licensed [citation:6].

- **[Arka Protocol Core](https://www.npmjs.com/package/@arka-protocol/core)**  
  **Pure, deterministic compliance rules engine** for regulatory and policy enforcement systems [citation:8]. Zero runtime dependencies, no network I/O [citation:8]. **Deterministic evaluation** — same inputs always produce identical outputs, perfect for audit trails [citation:8]. **Multi-jurisdiction harmonization** handles overlapping regulatory requirements across regions [citation:8]. **Time-travel simulation** tests rule changes against historical data before deployment [citation:8]. Adaptive risk scoring with configurable factors [citation:8]. Bytecode compilation (RTVM) for high-performance evaluation [citation:8].

- **[RegRadar](https://github.com/kingabzpro/RegRadar)**  
  **AI-powered regulatory compliance assistant.** Regulatory web crawler monitors SEC, FDA, FTC, ESMA, BIS for recent updates and compliance changes (last 30 days) [citation:14]. Regulatory search engine aggregates industry-specific compliance information across multiple sources [citation:14]. Memory system remembers past queries and personalizes results [citation:14]. AI analysis engine summarizes findings and generates actionable compliance recommendations and executive summaries [citation:14]. Smart report type detection — quick answers, summaries, or full compliance reports [citation:14].

- **[Anaya](https://pypi.org/project/anaya/)**  
  **Policy-pack-agnostic compliance-as-code engine.** CLI for local and CI usage (`anaya scan`) [citation:11]. Loads rule packs from YAML with built-in or user-authored external policy packs [citation:11]. Ships five generic OSS packs for secrets, OWASP, PII handling, TLS, and audit logging [citation:11]. Covers 29 built-in rules with Python and JavaScript fixture tests [citation:11]. GitHub App foundation with webhook verification, PR scanning, Check Run updates, and SARIF output [citation:11]. AGPL-3.0 licensed [citation:11].

- **[Comp AI](https://github.com/comp-ai/comp-ai)**  
  **Open-source compliance platform targeting SOC 2, ISO 27001, HIPAA, and GDPR.** Direct alternative to Vanta and Drata [citation:15]. **AI Policy Editor** drafts and updates security policies through natural language interface with diff viewer [citation:15]. **Automated Evidence** collects recurring evidence tasks via plain-language prompts [citation:15]. **Device Agent** checks employee devices for disk encryption, antivirus, password policy, and screen lock timeout — every hour, no personal data collected [citation:15]. Cloud integrations for AWS, GCP, and Azure [citation:15]. AGPLv3 licensed with Open Core model [citation:15].

### Additional Strong Open-Source Options

- **OpenFisca** — Rules as Code engine for collaboratively making laws and regulations computable over APIs. AGPL-3.0 licensed, deployed by France's DINUM, Spain, Australia NSW, and New Zealand Department of Internal Affairs [citation:12].
- **GDPR Tracker** — Crowdsourced directory tracking compliance and security practices of cloud services and subprocessors [citation:4].
- **PRArulebook (Bank of England)** — Scrape the Prudential Regulation Authority (PRA) rulebook [citation:4].
- **EBArulebook** — Scrape the European Banking Authority (EBA) rulebook and Q&As [citation:4].
- **SuadeLabs/fire** — Financial Regulation (FIRE) Data Standard for regulatory data exchange [citation:4].
- **Parajudica** — RDF-based reasoner and metamodel for multi-framework context-dependent data compliance assessments with HIPAA, GDPR, EMA, and Italian DPA implementations [citation:16].

**Frameworks for building custom systems**: Combine **GRCX** for financial regulator monitoring with cryptographic audit trails, **GovPing MCP Server** for AI-agent-accessible regulatory intelligence across 2,000+ sources, **Probo** for full GRC lifecycle with MCP tools, **TrustOps Security Data Lake** for framework mapping and audit readiness, and **Agent-Gov** for AI agent governance enforcement to build a complete self-hosted regulatory change monitoring stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Regulatory change monitors must comply with data protection regulations (GDPR, CCPA), and their outputs should be reviewed by qualified compliance professionals. **AI-mapped regulatory changes may contain errors and must be verified before acting upon.** LLM-based mapping is an augmentation of compliance team judgment, not a replacement [citation:9].
- Self-hosted open-source solutions require proper security hardening, regulator feed maintenance, and ongoing validation of control mappings.

---

**Made for compliance officers, RegTech engineers, fintech legal teams, and developers building regulatory intelligence platforms.**  
Let's make real-time regulatory change monitoring more open, auditable, and accessible.
