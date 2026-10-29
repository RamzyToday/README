# README

<div align="center">

# Ramzy Ismail

**Building and testing ai-native tools and workflows that support founders, operators, and investors in impacting their customers, communities, and colleagues.**
Ex-Techstars Investment Principal · Founding Director, Flat6Labs Abu Dhabi · Co-Founder, Stoic Scratch Labs

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramzyis-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramzyis/)
[![Writing](https://img.shields.io/badge/Writing-Medium-000000?logo=medium&logoColor=white)]([https://bit.ly/Medium_RI](https://medium.com/@ramzyis/data-on-venture-capital-in-the-middle-east-d9004230ebc4))
[![Tweet X](https://img.shields.io/badge/Tweet-X-000000?logo=medium&logoColor=white)]([https://bit.ly/Medium_RI](https://x.com/Ramzyis))
[![Email](https://img.shields.io/badge/Email-Ramzytoday%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:Ramzytoday@gmail.com)
![Based in](https://img.shields.io/badge/U.S.%20%7C%20GCC%20%7C%20Berlin-555555)

</div>

---

## About

I spent ten years on both sides of the startup table. As an investor, I backed 50 early-stage companies across Techstars and Flat6Labs. As an operator, I was the first commercial hire at two venture-backed startups and built the partner channels that drove their growth.

Now I build the tools I wished I had in both jobs. At **Stoic Scratch Labs**, I help SMB owners and startup founders put AI to work across sales, marketing, and partnerships: agent workflows, enrichment pipelines, research systems, and the operating playbooks around them.

This profile is where that work lives in public. Everything here is built to be forked, adapted, and improved.

> **Delta Hug:** my operating principle. Close the gap between where a founder is and where they need to be, whether that is fundraising, partnerships, go-to-market, or just getting unstuck.

---

## What I'm building

### RAM_OS: a personal AI operating system

The backbone for everything below. It's a set of Claude Skills, live MCP connections, and protocols that turn one operator into a small team.

```mermaid
flowchart LR
    subgraph Sources["Data sources (MCP)"]
        A[Apollo] & B[Clay] & C[Gmail / Calendar] & D[Google Drive]
    end
    subgraph Brain["Reasoning layer"]
        E[Claude + Claude Skills]
        F[Unknowns Protocol<br/>pre-flight check]
        G[Loop Architecture<br/>5-ring agent design]
    end
    subgraph Memory["Knowledge + execution"]
        H[(Notion<br/>knowledge layer)]
        I[Linear<br/>kanban]
        J[Vercel<br/>deploys]
    end
    Sources --> E
    F --> E
    G --> E
    E --> H & I & J
    H -. context .-> E
```

### Shipped and in use

| Project | What it does | Stack | Status |
|---|---|---|---|
| **`job-search-workflow`** (Claude Skill) | 7-phase career coaching pipeline: CV audit, rewrite, gap analysis, company research, interview prep, strategy | Claude Skills, Markdown | Shipped |
| **`loop-architecture`** (Claude Skill) | Pre-build design pass for agentic systems using a 5-ring loop taxonomy, so agents get designed before they get coded | Claude Skills | Shipped |
| **`finding-your-unknowns`** (Claude Skill) | A 4-move pre-flight check that surfaces hidden assumptions before any build starts | Claude Skills | Shipped |
| **`write-clearly`** (Claude Skill) | Clear-writing framework (after Edward T. Thompson) that auto-triggers on application and outreach copy | Claude Skills | Shipped |
| **GTM Systems Library** | Outbound and partner GTM for B2B startups entering the U.S. and GCC: enrichment, sequencing, WhatsApp-first and PDPL-safe LinkedIn motions, full SOP set | Clay, n8n, WhatsApp Business API, Notion | In use |
| **MENA Signal Pipeline** | Turns raw WhatsApp community exports into a funding and regulation signal report, with a Notion regulatory register that new exports append to | Claude, Notion API | In progress |
| **MENA AI Consumer Operating Model** | 12-tab, 10,000+ formula operating model for AI subscription businesses across three Middle East markets: two-tier churn, Saudization/GOSI, Zakat, three scenarios | Excel | Shipped |
| **AI-Native Job Search System** | CV variants per role cluster, cover letters, referral mapping, and outreach drafts generated from one locked fact sheet | Claude, docx, Gmail MCP | In use |
| **PATCH NYC Hackathon 2025** | Terminal-style financial data tool for SMBs | TypeScript | Hackathon |

### Coming to this profile

- [ ] Open-source the four Claude Skills as installable repos with examples
- [ ] `gtm-playbooks`: templated partner-program and startup-program playbooks from building Clara Accelerate (20+ partners, 37% of revenue)
- [ ] `vc-memo-archive`: a structured, searchable archive of 44 real venture memos for founders and new investors
- [ ] Evals for every agent workflow, with trace logs and error analysis published alongside the code

---

## Toolbox

| Layer | Tools |
|---|---|
| **AI and agents** | Claude, Claude Code, Cowork, Claude Skills, MCP, Lovable, Replit, Kimi K2, Zhipu AI |
| **GTM data and automation** | Apollo, Clay, n8n, WhatsApp Business API, HubSpot, Salesforce |
| **Knowledge and ops** | Notion, Linear, Google Workspace, Vercel |
| **Research and intel** | Klue, Remesh |
| **Certifications** | AWS Certified AI Business Strategist (2026), Pendo AI for Product Management (2025) |

---

## How I build

1. **Find the unknowns first.** Every build starts with a pre-flight check on assumptions, constraints, and what "done" means.
2. **Design the loop before the agent.** Map inputs, decisions, feedback, and failure modes before writing a prompt.
3. **Measure the delta.** Trace logs, error analysis, and before/after measurement, or it didn't happen.
4. **Make it multiplayer.** Tools should work for a team, not just for me.
5. **Ship in public.** Work that lives in a private doc can't help anyone else.

---

## Track record

```mermaid
timeline
    title Investor to operator to builder
    2015 : Flat6Labs Abu Dhabi : Founding Program Director : 18 investments, 85% follow-on
    2016 : Techstars : Investment Principal, EMEA : 32 investments, 90+ startups supported
    2022 : EQL Finance : B2B Growth Lead : Equifax + BGE partnerships
    2024 : Clara Technologies : Head of Venture GTM and Partnerships : acquired 2026
    2026 : Stoic Scratch Labs : Co-Founder : AI-native GTM studio
```

- **Techstars (2016 to 2022):** Led 32 investments and became Techstars' first Investment Principal. Ran portfolio services for 90+ startups and scaled EMEA portfolio services from 3 to 15 programs, with programs in New York, Baltimore, and Dubai.
- **Flat6Labs Abu Dhabi (2015 to 2016):** Co-built the city's first $10M seed fund and equity accelerator with twofour54. Backed Washmen (>50x ROIC) and Unnyhog, Abu Dhabi's first Y Combinator company.
- **Clara Technologies (2024 to 2026):** Built Clara Accelerate, a program with 20+ accelerators, VCs, and venture studios that grew from 21% to 37% of revenue and lifted partner-sourced pipeline 184%. Clara was acquired in Q1 2026.
- **EQL Finance (2022 to 2024):** First commercial hire. Closed partnerships with Equifax and Baltimore Gas and Electric to expand embedded financial access to underserved communities.

---

## Community

I've built founder communities on three continents and want this profile to be another one.

- **StartupUAE Slack:** founder and investor community for the UAE and MENA
- **Berlin 2nd Tuesdays:** recurring founder, operator, and investor meetup
- **Equitech Happy Hour:** weekly gathering for Baltimore's tech community
- **TechFugees Dubai:** technology for displaced people and refugees

**Founders:** if one of these tools could help you, open an issue or email me. I'll help you adapt it.
**Builders:** PRs, forks, and "this broke for me" reports are all welcome.

---

<div align="center">
<sub>Berlin-based builder, tester, and tech fiddler.</sub>
</div>
