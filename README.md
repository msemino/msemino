<div align="center">

# Hi, I'm Marcelo Semino 👋

### AI / LLM Engineer · RAG · LLM-Ops · 30+ years in systems engineering

**I design and run AI systems that actually ship — RAG pipelines, agents, and local-first infrastructure on hardware I own.** Less "I tried an LLM", more "here's the distributed system, the compliance guardrails, the observability, and why it runs unattended for months."

[![Open to remote](https://img.shields.io/badge/Open%20to-Remote%20roles-3DA639)](mailto:m_semino@hotmail.com)
[![Email](https://img.shields.io/badge/Email-m__semino@hotmail.com-0078D4?logo=maildotru&logoColor=white)](mailto:m_semino@hotmail.com)

</div>

---

## 🛠️ What I work with

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama%20·%20local%20LLMs-000000?logo=ollama&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%20·%20systemd-FCC624?logo=linux&logoColor=black)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?logo=tailscale&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA%20·%20RTX%203090-76B900?logo=nvidia&logoColor=white)

---

## 🚀 Featured projects

| Project | What it shows |
|---|---|
| **[insight-rag](https://github.com/msemino/insight-rag)** ⭐ | Production-shaped, local-first customer-insight RAG for regulated domains: Qdrant vector search + a knowledge graph (hybrid GraphRAG), compliance-aligned prompting, full observability, a **LoRA adapter trained on the RTX 3090**, and a versioned FastAPI service with green CI. **→ end-to-end RAG + LLM-ops + MLOps.** |
| **[infra-sentinel](https://github.com/msemino/infra-sentinel)** ⭐ | LLM-in-the-loop infrastructure watchdog: polls Zabbix + Prometheus and invokes a **self-hosted LLM only on the delta** to turn raw triggers into one impact-aware alert. The interesting part is the guardrails — dedup-with-cooldown, mass-outage circuit breaker, no-fallback retries — pure, unit-tested functions. **→ agentic AI + production judgment.** |
| **[private-clinical-rag](https://github.com/msemino/private-clinical-rag)** | A citation-grade RAG pipeline for high-stakes manuals: hierarchical chunking, ChromaDB, transparent re-ranking, cited answers, and a refusal gate. Embeddings + LLM run on local Ollama — zero data egress. **→ sovereign RAG + judgment.** |
| **[llm-chat-gateway](https://github.com/msemino/llm-chat-gateway)** | A ~230-line stdlib web chat gateway to a self-hosted Ollama LLM — one GPU-backed model, a whole team, zero cloud egress; the browser never learns where the GPU lives. **→ minimalist LLM serving.** |
| **[noc-live-boards](https://github.com/msemino/noc-live-boards)** & **[ops-daily-panel](https://github.com/msemino/ops-daily-panel)** | Real-time NOC/ops dashboards: a FastAPI caching proxy over Zabbix + Prometheus with a **credential-free frontend** (the browser never sees a secret), animated wall boards and a start-your-day ops panel. **→ observability UX + secure boundaries.** |
| **[self-hosted-ai-lab](https://github.com/msemino/self-hosted-ai-lab)** | A two-node (brain/body) personal AI system: a 24/7 agent orchestrator with a local-LLM brain, controlled over chat, with on-device voice transcription. 100% self-hosted. **→ distributed AI architecture.** |
| **[local-agent-orchestrator](https://github.com/msemino/local-agent-orchestrator)** | A 24/7 agent orchestrator with an uncensored local-LLM brain on a single RTX 3090 — the tuning that took replies from 398 s to 33 s. **→ local LLM ops.** |
| **[agente-book](https://github.com/msemino/agente-book)** | An extensible LangGraph price-auditing agent — and the engineering call to *drop the LLM* when a deterministic scraper was the right tool. **→ agents + judgment.** |
| **[attendance-clock-bot](https://github.com/msemino/attendance-clock-bot)** | An idempotent web automation bot and the three-architecture journey (cloud cron → Cloudflare Worker → self-hosted systemd) to make it truly reliable. **→ resilient automation.** |
| **[local-voice-recorder](https://github.com/msemino/local-voice-recorder)** | A Windows system-tray app: click to record, whisper.cpp large-v3 transcribes on your own GPU, text lands in the clipboard. No cloud STT, no audio leaves the machine. **→ privacy-first local AI.** |
| **[whatsapp-voice-transcriber](https://github.com/msemino/whatsapp-voice-transcriber)** | Async two-node pipeline that transcribes incoming WhatsApp voice notes locally (Whisper on RTX 3090) and sends the text back to your self-chat. Queue survives PC sleep. **→ async pipelines + privacy.** |

---

## 🧠 How I think about AI

- **Local-first, cloud on-demand.** Run what you can on hardware you own; reach for the cloud when capability — not habit — requires it.
- **Knowing when *not* to use an LLM** is as valuable as knowing how to use one.
- **Unattended means observable.** Retries, structured results, graceful degradation, and alerts that fire only when a human must act.
- **Architecture over scripts.** Brain/body splits, swappable components, defense in depth.

---

<div align="center">
<sub>Systems engineer for 30+ years · now building the AI/automation layer on top · based in Argentina, working remote</sub>
</div>
