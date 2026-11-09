# Hi, I'm Devnull (@devnullg) ⚡

> **Autonomous Multi-Agent Swarms · Vibe Coding · Production AI Systems · Open-Source Blueprints**

[![X Follow](https://img.shields.io/badge/X-@devnullg-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/devnullg)
[![GitHub](https://img.shields.io/badge/GitHub-myprofile2403--design-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/myprofile2403-design)
[![Core Stack](https://img.shields.io/badge/Stack-Python_•_Claude_•_LangGraph_•_FastAPI-0052CC?style=for-the-badge)](https://x.com/devnullg)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

### 🛠️ Personal Manifesto & Philosophy

I build and test autonomous AI software, multi-agent swarms, browser automation engines, and algorithmic financial tools — entirely in public. 

* **No generic AI wrapper slop.** Real architectures, deterministic state machines, and reproducible code.
* **Radical transparency.** Production post-mortems, failure logs, and live telemetry shared openly.
* **Human-in-the-loop + Autonomous execution.** Designing autonomous loops with rigorous verification gates.

---

### 📐 Open-Source Blueprints & Architecture

```
                  [ Task Dispatcher / Ingress ]
                                │
                                ▼
  ┌───────────────────────────────────────────────────────────┐
  │               CENTRAL AGENT ORCHESTRATOR                  │
  │    • LangGraph State Machine    • Postgres Checkpointer    │
  │    • Acceptance Gates           • Anti-Hallucination Guard│
  └─────────────────────────────┬─────────────────────────────┘
                                │
          ┌─────────────────────┼─────────────────────┐
          ▼                     ▼                     ▼
  ┌───────────────┐     ┌───────────────┐     ┌───────────────┐
  │ Code & Logic  │     │ Headless CDP  │     │ Token Control │
  │  Synthesizer  │     │   Browser     │     │   & Routing   │
  │ (Claude/Grok) │     │ (Port :9223)  │     │   (LiteLLM)   │
  └───────────────┘     └───────────────┘     └───────────────┘
          │                     │                     │
          ▼                     ▼                     ▼
    [ PR & Review ]      [ Live Web DOM ]      [ Per-Agent ROI]
```

#### 1. 🤖 Multi-Agent Autonomous Swarms
- Distributed task runners coordinated via centralized state management (`PostgresSaver`).
- Non-overlapping operational boundaries with escalation channels and deterministic recovery.

#### 2. 🌐 Headless CDP Browser Automation
- Native Chrome DevTools Protocol (`CDP`) integration on isolated ports with dedicated profiles.
- Human-like kinetic movement: character-by-character typing cadence, heuristic DOM waiting, zero raw page injections.
- Strict live-DOM verification before any state transition or completion confirmation.

#### 3. ⚖️ Token Economy & Cost-Control Proxy
- `LiteLLM` multi-provider routing layer (Claude Opus, Grok 4, GPT-4o).
- Context compression and Anthropic prompt caching (delivering up to 90% input token cost reduction).
- Per-agent budget limits, fallback cascades, and real-time usage observability.

#### 4. 📈 Algorithmic Bots & Micro-Tools
- High-frequency market data streams (CCXT, WebSockets) paired with deterministic risk engines.
- Micro-SaaS tools built with Cursor, Claude Code, and modern reactive frontends.

---

### 💻 Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | Python 3.12, TypeScript, Bash, Modern SQL |
| **Agentic AI** | Claude 3.5 Sonnet / Opus, Grok, LangGraph, LiteLLM |
| **Infrastructure** | Linux (Debian/Ubuntu), Docker, PostgreSQL, Supabase, Caddy, systemd |
| **Automation** | Chrome DevTools Protocol (CDP), Playwright, WebSockets |
| **Workflow** | Cursor, Claude Code, Git, GitHub Actions, CI/CD |

---

### 📊 Public Telemetry & Production Rules

1. **Verify Live, Always:** A task is never marked done until live DOM, DB rows, or process states confirm success.
2. **Deterministic Schemas:** Unstructured LLM outputs are strictly validated against strict Zod/Pydantic schemas.
3. **Graceful Degrade:** Every autonomous script handles rate-limits, auth expired states, and network drops with structured escalation.

---

### 🤝 Connect & Follow the Build

I share daily build logs, architecture breakdowns, code snippets, and performance analytics on X:

👉 **Follow [@devnullg on X (Twitter)](https://x.com/devnullg)** for real-time updates, engineering breakdowns, and raw build logs.
