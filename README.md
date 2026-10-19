# Hi, I'm Tanakorn 👋

**Backend Developer @ SwiftDynamic (Sitearound)** · Bangkok, Thailand 🇹🇭
🏆 1st Place — AI Hackathon Thailand

I build enterprise backends that talk to ERP systems — workflow engines, SAP integrations, document & signing pipelines. Heading toward **Senior Software Engineer → Solutions Architect**.

> “Keep it simple. Make it scale.”

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanakorn-aphiwanphakdee-93b470261)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:tanakorn.aphiwan@gmail.com)

---

## 🛠 Tech Stack

| Area | Tools |
|---|---|
| **Backend** | Python · Django 5.x · Django REST Framework · Celery · httpx (async) |
| **Data** | PostgreSQL · Redis |
| **Integration** | SAP ERP (OData / BAPI / ABAP debugging) · Azure Entra SSO |
| **Documents** | WeasyPrint (PDF) · Apryse WebViewer (XFDF signing) · Outlook-safe HTML email |
| **Frontend** | React · TypeScript · Ant Design v5 |
| **Infra** | Docker · Traefik · S3 (MinIO) |
| **AI / Agents** | Claude Code · MCP (Playwright, Context7, GitHub, Jira, Excalidraw) · Ollama · OpenRouter |
| **Env** | Arch / CachyOS · Hyprland · Zed · zsh + Starship · yazi |

---

## 🏗 What I'm Building — PayStation

Construction payment management platform for a large enterprise real-estate client, integrated with SAP ERP. I own the backend end-to-end.

- **Generic `BaseWorkflowEngine`** — one engine for multiple document types: step state machines, approval sub-step injection, cycle tracking, SAP PR creation triggers (evaluated List+inject vs. DAG designs)
- **Service-layer architecture** — thin serializers → DTOs → thick services; soft delete via `django-safedelete`; DRF permission registry + `BaseScopedViewSet`; multi-tenant permissions
- **SAP OData client** — CSRF token caching, retry + circuit breaker, async httpx, Celery integration
- **SAP debugging** — traced ERP business logic through ABAP source to reproduce budget calculations and pin down data bugs in custom OData services
- **Document pipeline** — WeasyPrint PDF generation, Apryse/XFDF digital signatures with coordinate-system handling, Outlook/OWA-compatible HTML email templates
- **Variation Order workflow** — data model, service layer, SAP PO creation
- **QA** — led UAT for Phase 2: 207 test cases across 16 modules

---

## 📂 Open Source

| Project | What it is |
| :--- | :--- |
| 📄 [**pdf-template-custom**](https://github.com/OmTanakorn/pdf-template-custom) | PDF template engine — Template JSON + data JSON → PDF, with a drag-and-drop studio. Thai-first (Sarabun, พ.ศ. dates, bahttext). |
| 📈 [**backend-engineering**](https://github.com/OmTanakorn/backend-engineering) | 12-month Senior/Lead roadmap, learning in public — architecture, data layer, distributed systems, security, cloud. |
| ⚔️ [**tong-calc-ro**](https://github.com/OmTanakorn/tong-calc-ro) | Ragnarok Online damage calculator (fork, extending). |
| 🧟 [**project-zomboid-server**](https://github.com/OmTanakorn/project-zomboid-server) | Dockerized Project Zomboid game server. |

---

## 🤖 AI-Assisted Engineering

- Parallel agent workflows with **Claude Code + git worktrees**
- Reusable skills: DRF review, docx templates, UAT playbook, tech translator, Jira ↔ Obsidian sync
- Jira status automation via **GitHub Actions** (no-admin workaround)
- Token optimization: prompt caching, model routing, CLAUDE.md slimming
- LLM wiki knowledge bases with Obsidian; local models via Ollama

---

## 🎲 Side Projects

- **3D Print Shop** — tabletop/fantasy miniatures (40K / D&D style) + custom customer prints; building a standalone storefront with a custom-print order flow
- **Ragnarok Online tools** — item search via Divine Pride API, damage calculator (React + FastAPI)
- **Dark-fantasy pixel art** — Aseprite / Krita; working on HD-2D style short story clips

---

## ☕ Off-keyboard

Pour-over coffee (V60, Ethiopia naturals) · Colony/survival games — Dwarf Fortress, Kenshi, Songs of Syx, Battle Brothers, Path of Exile 2 · Radiohead on repeat · INTP
