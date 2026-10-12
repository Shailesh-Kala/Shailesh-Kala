## Hi, I'm Shailesh Kala <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="28px">

**Software Engineer · Tech Lead · AI/LLM Engineering** — Gurugram, India

I build AI-powered, multi-tenant, and government-scale platforms end to end. 4+ years of full-stack work, most recently shipping production LLM systems: provider-agnostic LangChain cores across OpenAI and Anthropic Claude, multi-agent pipelines, RAG, and MCP.

[LinkedIn](https://linkedin.com/in/shailesh-kala-142954182) · [Email](mailto:shaileshkala00@gmail.com)

---

### At a glance

- **Tech Lead / Lead Engineer at [ColoredCow](https://coloredcow.com)** (Apr 2022 – Sep 2026) on five flagship engagements: PMG Portal (Invest India / DPIIT), VallamAI (Madhi Foundation), SankalpTaru, WisdomCircle, and Unos y Otros
- **4,371 commits · 643 merged PRs · 22 repositories**, plus **672 PRs reviewed** for teammates
- Integrated two national platforms (IIG ↔ PMG) and **migrated 3,000+ users with zero downtime**
- Cleared a background-job bottleneck that **held up at 4x concurrency with no extra server spend**

---

### Featured work

**VallamAI: AI assessment & lesson planning** · Madhi Foundation · *Lead Engineer*
Deployed for a foundation working across **37,000+ Tamil Nadu government schools**. I owned four repos: backend, AI service, mobile, and admin.
- Re-architected a 34k-LOC AI service onto a **LangChain-native, provider-agnostic core**. Switching between OpenAI and Claude is now a config change, with no call-site edits.
- `llm_core` task registry with a capability system that rejects invalid task↔model pairings **at startup**, not as runtime 400s
- **Multi-agent lesson-plan generator**: 5 parallel context layers feeding 4 concurrent LLM sub-agents and an orchestrator that emits schema-validated JSON
- **RAG pipeline** (curriculum PDFs + YouTube transcripts → hierarchical chunking → FAISS/pgvector + reranking) and a custom **MCP server**
- **Langfuse** prompt management with fallback to in-code prompts, tracing, cost attribution, and PII redaction; a **RAGAS / LLM-as-judge** harness as a release gate
- Offline-first **React Native** app (54+ screens) with speech-driven AI assessments

`Python` `Flask` `Django/DRF` `LangChain` `OpenAI` `Claude` `Langfuse` `RAG` `MCP` `pgvector` `Celery` `React Native` `Next.js`

**PMG Portal: Government of India project monitoring** · Invest India / DPIIT · *Tech Lead*
The national platform for unblocking infrastructure projects above ₹500 crore. I authored 240 PRs and reviewed 514 over 16 months.
- Delivered the **IIG–PMG integration**: bidirectional sync, linking 2,000+ projects worth ~₹60 lakh crore
- **Keycloak SSO** replacing legacy auth; a six-role permission model spanning ministries, states, and districts
- Rebuilt the reporting engine and optimized Elasticsearch reindexing · [Case study →](https://coloredcow.com/work/coloredcow-moves-pm-gati-shakti-initiative-forward/)

`Java` `Spring Boot` `React` `Elasticsearch` `Keycloak`

**SankalpTaru: tree-plantation donation platform** · *Tech Lead, 2.5+ years*
- Owned four codebases (storefront, Laravel platform, admin, RN field app) and delivered two full e-commerce revamps
- Six-factor weighted search ranking; Redis + CDN; **k6 load testing** that root-caused the slow-request bottleneck
- Blockchain-backed provenance for 139,000+ trees

`PHP` `Laravel` `WordPress` `React Native` `Redis` `k6`

**More:** Unos y Otros (Laravel + OpenAI, empty repo → v1.6.0) · [AI Student Community](https://aistudent.community) (MERN, built solo) · SRG Profiler · I4F India–Israel R&D Fund · Swataleem · Gramhal

---

### Side projects

- [**answerbubble**](https://github.com/Shailesh-Kala/answerbubble): instant FAQ answers + WhatsApp chat for any website. One copy-paste, no server, no tracking. [Live demo →](https://shailesh-kala.github.io/answerbubble/)
- [**alarm-clock-cli**](https://github.com/Shailesh-Kala/alarm-clock-cli): a terminal alarm clock in Python, using only the standard library

---

### Stack

| | |
|---|---|
| **AI / LLM** | LangChain, OpenAI API, Anthropic Claude API, Langfuse, RAG, MCP, multi-agent systems, RAGAS |
| **Languages** | Python, Java, PHP, JavaScript, SQL |
| **Backend** | Spring Boot, Laravel, Django/DRF, Flask, Node.js/Express, Celery |
| **Frontend & Mobile** | React, Next.js, React Native |
| **Data** | PostgreSQL (pgvector), MySQL, MongoDB, Elasticsearch, FAISS, Redis |
| **DevOps** | AWS, Docker, Nginx, GitHub Actions, Jenkins, Cloudflare, Sentry, PostHog |
| **Auth & Testing** | Keycloak (SSO/OIDC), Sanctum, JWT · TDD, Playwright, k6 |
