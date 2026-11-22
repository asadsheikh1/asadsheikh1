# Asad Sheikh — AI Engineer

<img src="./github_banner.png" alt="Asad Sheikh — AI Engineer: LLM systems, AI agents and AI infrastructure" width="100%">

**AI Engineer building production LLM applications, AI agents and the Python backends behind them.**
I own AI features end to end: system design, retrieval and agent architecture, evaluation, deployment and monitoring.

- 🧠 Head of AI Development at **8ration (CoreCodez)** (joined as AI Developer Nov 2025, promoted Mar 2026) — tool-calling AI records assistant, RAG chatbot, model-inference platform on AWS
- 💼 Previously Freelance AI Engineer on **Upwork** (Mar 2024 – Nov 2025) — Top Rated, 100% Job Success, 18 contracts (US, Europe, Middle East)
- 🛠️ Building **[SENTINEL](https://github.com/asadsheikh1/sentinel)** — an autonomous AI Site Reliability Engineer (in active development)
- 🌍 Karachi, Pakistan (UTC+5) · open to remote roles and to relocating to KSA / UAE
- 📫 [asadtsheikh@gmail.com](mailto:asadtsheikh@gmail.com) · [LinkedIn](https://www.linkedin.com/in/asadsheikh1/) · [Upwork](https://www.upwork.com/freelancers/asadsheikh) · [Medium](https://medium.com/@asadtsheikh)

---

## Featured work

| Project | What it is | Stack |
|---|---|---|
| [**SENTINEL**](https://github.com/asadsheikh1/sentinel) | AI SRE, in active development. Built: OpenTelemetry telemetry pipeline, auth/RBAC and the first detection layer (alert rule packs, signals, deploy and GitHub webhooks). Planned: LangGraph root-cause agents on local LLMs, pgvector memory, repair sandbox, published precision/recall. | Python, FastAPI, PostgreSQL, OpenTelemetry, Prometheus, Loki, Jaeger, React, Podman |
| [**AVIRO**](https://github.com/asadsheikh1/aviro-shop) | Microservice demo shop with fault injection — the system SENTINEL monitors and is evaluated against | FastAPI, PostgreSQL, Celery, Valkey, Locust, OpenTelemetry |
| **AI Records Assistant** *(case study, client code private)* | Natural-language → confirmed CRUD across 32 modules, permission-aware retrieval, human confirmation | Python, FastAPI, OpenAI, LangChain, FAISS, Azure AI Document Intelligence |

## Tech stack

**LLMs & agents** — OpenAI · Anthropic Claude · Gemini · Qwen3 / Llama via Ollama & vLLM · LangChain · LlamaIndex · Pydantic AI · MCP · tool calling · structured outputs
**Retrieval** — hybrid search (BM25 + dense) · cross-encoder reranking · pgvector · FAISS · Qdrant
**Evaluation & LLMOps** — eval harnesses · LLM-as-judge · Langfuse · guardrails · prompt-injection testing
**Backend** — Python · FastAPI · asyncio · PostgreSQL · Supabase · Redis/Valkey · Celery · REST & WebSockets · OAuth2 · RBAC
**Cloud & observability** — AWS (EC2, ALB, ECS, Lambda, Bedrock, S3) · Azure AI Document Intelligence · Docker · Podman · Kubernetes · OpenTofu/Terraform · GitHub Actions · OpenTelemetry · Prometheus · Grafana · Loki · Jaeger
**ML** — scikit-learn · TensorFlow · LoRA/QLoRA fine-tuning (Hugging Face TRL, Unsloth)

## How I build AI systems

- **Deterministic where it matters.** Rules and validation first; the LLM handles ambiguity, never unchecked writes.
- **Humans approve actions.** State-changing operations go through explicit confirmation and an audit trail.
- **Measured, not claimed.** Evaluation sets and regression tests before shipping a prompt or model change.
- **Results, not adjectives.** 10+ AI-powered apps deployed, 7M+ rows of hospital data structured (80% less manual processing), 30% faster ML APIs.
- **Observable by default.** Structured logs, metrics and traces from day one.

---

<sub>Older student, mobile and coursework projects are archived. Ask me about the Flutter/iOS apps I shipped before moving fully into AI engineering.</sub>
