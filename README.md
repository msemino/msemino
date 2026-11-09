<div align="center">

# Delta Labs 👋

### AI Platform Engineer · Agentic AI · AIOps · RAG · LLM-Ops · 30+ years in systems engineering

**I design and run AI systems that actually ship — RAG pipelines, agents, and local-first infrastructure on hardware I own.** Less "I tried an LLM", more "here's the distributed system, the compliance guardrails, the observability, and why it runs unattended for months."

[![Open to remote](https://img.shields.io/badge/Open%20to-Remote%20roles-3DA639)](https://proyectos-msemino.vercel.app)

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
![CUDA](https://img.shields.io/badge/CUDA%20·%20NVIDIA%20GPU-76B900?logo=nvidia&logoColor=white)

---

## 🚀 Featured projects

| Project | What it shows |
|---|---|
| **[netbox-mcp](https://github.com/msemino/netbox-mcp)** ⭐ | A **read-only MCP server over NetBox, served over HTTP** so a whole engineering team queries live IPAM from their AI assistants — nobody installs anything, and the API token never leaves the server. In production on a telecom infrastructure team. Read-only *by construction* (GET-only) **and** by token, because one of those will eventually be a mistake. **→ authoring MCP, not just consuming it.** |
| **[agent-governance-ci](https://github.com/msemino/agent-governance-ci)** ⭐ | Two coding agents from different vendors write to the same repository. The rules live in one file and each agent's instructions only point at it; structural work needs a **versioned claim** with an owner and an expiry; and CI fails a commit that walks into an area another agent holds. Enforced in CI because only one of the two clients supports hooks. Stdlib only, 34 tests, governed by its own checks. **→ AI policy turned into controls an agent cannot skip.** |
| **[infra-sentinel](https://github.com/msemino/infra-sentinel)** ⭐ | LLM-in-the-loop infrastructure watchdog: polls Zabbix + Prometheus and invokes a **self-hosted LLM only on the delta** to turn raw triggers into one impact-aware alert. The interesting part is the guardrails — dedup-with-cooldown, mass-outage circuit breaker, no-fallback retries — pure, unit-tested functions. **→ agentic AI + production judgment.** |
| **[evidence-gate](https://github.com/msemino/evidence-gate)** | Reads a published page, pulls out every claim that can be checked — a test name, a file path, a measured figure, a promise of code — and **fails the build** when a fresh clone of the repository does not back it. Built for the confident, checkable detail a language model writes as fluently as the truth. **→ a written rule, enforced by the build.** |
| **[llm-extraction-eval](https://github.com/msemino/llm-extraction-eval)** | Structured extraction from operations e-mail with a local LLM, scored **per class**. No headline accuracy figure: a real mailbox is mostly not alerts, so the majority class swallows any average, and the four classes carry different costs — a missed cancellation is a crew standing by for work that was called off. **→ evaluating an LLM pipeline in earnest.** |
| **[private-clinical-rag](https://github.com/msemino/private-clinical-rag)** | A citation-grade RAG pipeline for high-stakes manuals: hierarchical chunking, ChromaDB, transparent re-ranking, cited answers, and a refusal gate. Embeddings + LLM run on local Ollama — zero data egress. **→ sovereign RAG + judgment.** |
| **[insight-rag](https://github.com/msemino/insight-rag)** ⭐ | Production-shaped, local-first customer-insight RAG for regulated domains: Qdrant vector search + a knowledge graph (hybrid GraphRAG), compliance-aligned prompting, full observability, a **LoRA adapter trained on a single 24 GB NVIDIA GPU**, and a versioned FastAPI service with green CI. **→ end-to-end RAG + LLM-ops + MLOps.** |
| **[inference-cost-bench](https://github.com/msemino/inference-cost-bench)** | What self-hosted inference costs, in tokens per second and in watts. One machine, one variable: **11.3 tok/s on the GPU, 1.2 forced onto the CPU**. Every power sample is kept raw and the published table is re-derived from it in CI, so the numbers can be recomputed rather than trusted. **→ measuring the thing you keep asserting.** |
| **[local-agent-orchestrator](https://github.com/msemino/local-agent-orchestrator)** | A 24/7 agent orchestrator with an uncensored local-LLM brain on a single 24 GB NVIDIA GPU — the tuning that took replies from 398 s to 33 s. **→ local LLM ops.** |

**Also built:** [llm-chat-gateway](https://github.com/msemino/llm-chat-gateway) — stdlib web chat gateway to a self-hosted LLM · [noc-live-boards](https://github.com/msemino/noc-live-boards) — NOC wall boards over Zabbix + Prometheus, credential-free frontend · [ops-daily-panel](https://github.com/msemino/ops-daily-panel) — start-of-day ops panel · [self-hosted-ai-lab](https://github.com/msemino/self-hosted-ai-lab) — two-node brain/body personal AI system · [agente-book](https://github.com/msemino/agente-book) — LangGraph price auditor that dropped the LLM · [portal-sentinel](https://github.com/msemino/portal-sentinel) — resilient runner for scheduled web actions · [local-voice-recorder](https://github.com/msemino/local-voice-recorder) — tray app: speak, transcribe on GPU, text to clipboard · [whatsapp-voice-transcriber](https://github.com/msemino/whatsapp-voice-transcriber) — local transcription of WhatsApp voice notes

---

## 🧠 How I think about AI

- **Local-first, cloud on-demand.** Run what you can on hardware you own; reach for the cloud when capability — not habit — requires it.
- **Knowing when *not* to use an LLM** is as valuable as knowing how to use one.
- **An instruction an agent has to remember is a request, not a control.** Policies go where every agent passes: the tool boundary, the policy module, the build.
- **Unattended means observable.** Retries, structured results, graceful degradation, and alerts that fire only when a human must act.
- **Architecture over scripts.** Brain/body splits, swappable components, defense in depth.

---

<div align="center">
<sub>Systems engineer for 30+ years · now building the AI/automation layer on top · based in Argentina, working remote</sub>
</div>
