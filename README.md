<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0d1117,100:2d2a40&text=tanakorn&fontColor=d4d4e0&fontSize=60&fontAlignY=38&desc=bangkok%20%C2%B7%20backend%20%C2%B7%20pixels%20and%20coffee&descAlignY=60&descSize=15&animation=fadeIn" width="100%" alt="tanakorn" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3200&pause=1400&color=8B8BA7&center=true&vCenter=true&width=520&lines=backend+engineer+%C2%B7+erp+%26+sap+integrations;workflow+engines+%C2%B7+document+pipelines;keep+it+simple.+make+it+scale." alt="typing" />

<br/>

**backend developer @ swiftdynamic (sitearound)** &nbsp;·&nbsp; 🏆 1st place — ai hackathon thailand
<br/>
<sub>building enterprise backends that talk to erp systems — heading toward senior engineer → solutions architect</sub>

<br/><br/>

<a href="https://www.linkedin.com/in/tanakorn-aphiwanphakdee-93b470261"><img src="https://img.shields.io/badge/linkedin-1a1b26?style=for-the-badge&logo=linkedin&logoColor=8b8ba7" alt="LinkedIn" /></a>&nbsp;<a href="mailto:tanakorn.aphiwan@gmail.com"><img src="https://img.shields.io/badge/email-1a1b26?style=for-the-badge&logo=gmail&logoColor=8b8ba7" alt="Email" /></a>

</div>

<br/>

### ⟡ &nbsp;stack

<img src="https://skillicons.dev/icons?i=python,django,fastapi,postgres,redis,docker,react,ts,githubactions,linux,arch,obsidian&theme=dark&perline=12" alt="stack" />

<sub>
<b>integration</b> &nbsp;sap erp (odata · bapi · abap) · azure entra sso &nbsp;&nbsp;
<b>documents</b> &nbsp;weasyprint · apryse xfdf signing · outlook-safe html &nbsp;&nbsp;
<b>agents</b> &nbsp;claude code · mcp · ollama · openrouter &nbsp;&nbsp;
<b>env</b> &nbsp;cachyos · hyprland · zed · zsh + starship · yazi
</sub>

<br/><br/>

### ⟡ &nbsp;now building — paystation

Construction payment platform for an enterprise real-estate client, wired into SAP ERP. I own the backend end-to-end.

<details>
<summary><sub>&nbsp;open the notebook ↓</sub></summary>
<br/>

- **generic `BaseWorkflowEngine`** — one engine for multiple document types: step state machines, approval sub-step injection, cycle tracking, SAP PR creation triggers (weighed List+inject vs. DAG)
- **service-layer architecture** — thin serializers → DTOs → thick services; soft delete via `django-safedelete`; DRF permission registry + `BaseScopedViewSet`; multi-tenant permissions
- **SAP OData client** — CSRF token caching, retry + circuit breaker, async httpx, Celery
- **SAP debugging** — traced ERP business logic through ABAP source to reproduce budget calculations and pin down data bugs in custom OData services
- **document pipeline** — WeasyPrint PDFs, Apryse/XFDF digital signatures with coordinate-system handling, Outlook/OWA-safe HTML email
- **variation order workflow** — data model, service layer, SAP PO creation
- **QA** — led Phase 2 UAT: 207 test cases across 16 modules

</details>

<br/>

### ⟡ &nbsp;open source

<table>
<tr>
<td width="50%" valign="top">

**[pdf-template-custom](https://github.com/OmTanakorn/pdf-template-custom)**
<br/><sub>template json + data json → pdf, with a drag-and-drop studio. thai-first — sarabun, พ.ศ. dates, bahttext.</sub>

</td>
<td width="50%" valign="top">

**[backend-engineering](https://github.com/OmTanakorn/backend-engineering)**
<br/><sub>a 12-month senior / lead roadmap, learned in public — architecture, data, distributed, security, cloud.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[tong-calc-ro](https://github.com/OmTanakorn/tong-calc-ro)**
<br/><sub>ragnarok online damage calculator — forked, being extended.</sub>

</td>
<td width="50%" valign="top">

**[project-zomboid-server](https://github.com/OmTanakorn/project-zomboid-server)**
<br/><sub>a dockerized project zomboid server, for long nights with friends.</sub>

</td>
</tr>
</table>

<br/>

### ⟡ &nbsp;how i work

- parallel agent workflows — **claude code + git worktrees**
- hand-made skills: drf review, docx templates, uat playbook, tech translator, jira ↔ obsidian sync
- jira status automation through github actions (a no-admin workaround)
- token thrift: prompt caching, model routing, slim CLAUDE.md
- llm wiki knowledge bases in obsidian; local models via ollama

<br/>

### ⟡ &nbsp;after hours

- 🎲 **3d print shop** — tabletop & fantasy miniatures (40k / d&d), custom prints; building its storefront
- ⚔️ **ragnarok online tools** — item search on the divine pride api, damage calculator (react + fastapi)
- 🕯️ **dark-fantasy pixel art** — aseprite / krita; drafting hd-2d short story clips

<br/>

<div align="center">

<sub>☕ v60 · ethiopia naturals &nbsp;&nbsp;·&nbsp;&nbsp; 🏰 dwarf fortress · kenshi · songs of syx · battle brothers · poe2 &nbsp;&nbsp;·&nbsp;&nbsp; 🎧 radiohead on repeat &nbsp;&nbsp;·&nbsp;&nbsp; intp</sub>

<br/><br/>

<i>“for a minute there, i lost myself.”</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:2d2a40,100:0d1117&section=footer" width="100%" alt="" />
