<div align="center">

# Yasaswin Palukuri
**Data Engineer · AI/ML Engineer · LLMOps Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasaswin-palukuri/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/yasaswinpalukuri)
[![Location](https://img.shields.io/badge/Toronto%2C%20Canada-🍁-red)](https://www.google.com/maps/place/Toronto)

</div>

---

## What I'm Building

**[Groot](https://github.com/yasaswinpalukuri/Groot-Agent-System)** — A self-hosted multi-agent AI system running 24/7 on bare metal hardware. 6 autonomous agents (Groot, Einstein, Tony, Siva, Job Search, Career) orchestrated via LangGraph + FastAPI, with Ollama for CPU-only local inference, Hybrid RAG (BM25 + dense vectors), Slack/Telegram integrations, and a live React dashboard.

> Not a demo. Running right now on a Lenovo M720Q in Toronto.

---

## Current Stack

```python
stack = {
    "languages":   ["Python", "SQL", "Java", "PySpark"],
    "ai_ml":       ["LangGraph", "Ollama", "ChromaDB", "LangChain",
                    "FastAPI", "MLflow", "SHAP", "Scikit-learn"],
    "data":        ["AWS Glue", "S3", "Lambda", "Redshift",
                    "Apache Spark", "Hadoop", "Kafka"],
    "devops":      ["Docker", "Git", "Pytest", "Ruff", "Bandit", "CI/CD"],
    "viz":         ["Tableau", "Power BI", "Streamlit"],
    "currently":   ["LLMOps", "Agentic AI", "Self-hosted inference"],
}
```

---

## Projects

| Project | Stack | Status |
|---------|-------|--------|
| [Groot Multi-Agent System](https://github.com/yasaswinpalukuri/Groot-Agent-System) | LangGraph · FastAPI · Ollama · ChromaDB · Docker | 🟢 Live |
| LLM Eval / Red-Teaming Framework | DeepEval · Llama Guard · Python | 🟡 Planned |
| Text-to-SQL (qwen2.5-coder) | Python · SQLite · FastAPI | 🟡 Planned |
| Credit Risk Scoring with XAI | SHAP · Scikit-learn · Streamlit | ✅ Complete |

---

## Groot Architecture (running on my desk right now)

```
┌─────────────────────────────────────────────┐
│              Lenovo M720Q                    │
│         i5-8500T · 16GB · Ubuntu 22.04      │
├─────────────────────────────────────────────┤
│  Groot (Supervisor)    → qwen2.5:7b         │
│  Einstein (Researcher) → deepseek-r1:14b    │
│  Tony (Developer)      → qwen2.5-coder:7b   │
│  Siva (Tutor)          → phi3:medium        │
│  Job Search Agent      → qwen2.5:7b         │
│  Career Agent          → mistral:7b         │
├─────────────────────────────────────────────┤
│  Hybrid RAG · BM25(40%) + Dense(60%)        │
│  6 ChromaDB collections · RBAC enforced     │
│  guardrails-ai · Ragas evals                │
│  Slack (9ch) · Telegram · n8n workflows     │
│  React dashboard · Tailscale VPN            │
└─────────────────────────────────────────────┘
```

---

## Ragas Eval Results (Groot RAG Pipeline)

| Metric | Score |
|--------|-------|
| Faithfulness | **1.000** |
| Answer Relevancy | **0.676** |
| Overall | **0.838** |

*Evaluated with qwen2.5:7b as judge · nomic-embed-text embeddings*

---

## Experience

- **Verita Network** — Data Engineer (Volunteer) · AWS ETL pipelines (S3, Glue, Lambda, Redshift) · May 2026–present
- **Groot Project** — LLMOps Engineer · Self-directed · Jan 2026–present
- **Credit Risk XAI** — ML Engineer · SHAP + Scikit-learn · May–Jun 2025

---

## Education

- 🎓 **Lambton College** — Graduate Certificate, AI & Machine Learning (2025)
- 🎓 **KL University** — B.Tech (Honors), Computer Science (2023)

---

## Open To

`Data Engineer` · `ML Engineer` · `LLMOps Engineer` · `AI Engineer`

Remote · Toronto · Vancouver · India

---

<div align="center">
<i>Building Groot one agent at a time.</i>
</div>
