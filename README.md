<h1 align="center">Nathan Phillips</h1>
<h3 align="center">I build AI systems that are measured, not asserted.</h3>

<p align="center">
  <a href="https://linkedin.com/in/nmp-dsci"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nmpdsci@gmail.com"><img src="https://img.shields.io/badge/Email-nmpdsci%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://nmp-dsci.github.io"><img src="https://img.shields.io/badge/Portfolio-nmp--dsci.github.io-222?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio" /></a>
</p>

<p align="center">
Data scientist turned AI engineer — four production-style LLM agents, every one shipped with an eval harness, a golden set, and a number I can defend.<br>
🚀 <b>Open to AI / ML / Data Science roles across Australia</b>
</p>

---

## 🧪 What I've built

#### 💬 ConvFinQA Agent — multi-turn financial Q&A

- **Problem** — Analysts ask chained questions over financial reports that mix prose and tables.
- **Built** — A four-stage agent pipeline with a live admin console: eval runs, GEPA prompt-optimisation experiments, question-by-question diffs between versions, and a public demo that can't spend money by construction.
- **Result** — **77.7% accuracy** on never-seen conversations (770-question set); GEPA-optimised prompts +4.9 pts over baseline.
- `Pydantic AI` `GEPA` `Docker` → [repo](https://github.com/nmp-dsci/ConvFinQA-agent)

#### ⚖️ CUAD Legal Agent — contract clause extraction

- **Problem** — Lawyers spend hours reading contracts to answer the same 41 standard review questions.
- **Built** — A legal-review agent evaluated across five context strategies (raw, dense, hybrid, hierarchical BM25 / dense) against human-labelled golden spans.
- **Result** — **83.7% token-F1** on 2,050 contract/question pairs — +43.6 pts over the v1 baseline.
- `LangChain` `DSPy` `BM25 + dense retrieval` → [repo](https://github.com/nmp-dsci/CUAD-agent)

#### 🎧 transcript·lab — evaluation-first RAG workbench

- **Problem** — "Does RAG work?" is the wrong question. "Which retrieval config ranks the evidence best, and how do you know?" is the right one.
- **Built** — Four answer paths (single-hop, recursive multi-hop, agentic ReAct, GraphRAG) over one shared hybrid-retrieval stack, with an ablation harness and a CI eval-regression gate.
- **Result** — Every retrieval claim backed by a committed, reproducible eval run.
- `Neo4j` `MiniLM` `RRF fusion` `cross-encoder rerank` → [repo](https://github.com/nmp-dsci/transcript-rag-agent)

#### 📊 Data Pilot — governed text-to-SQL agent

- **Problem** — Self-serve analytics breaks the moment users can see data they shouldn't.
- **Built** — A conversational data agent that compiles natural language into governed SQL, with Postgres row-level security so two users asking the same question get different (correct) answers.
- **Result** — Whole stack boots with one `make up` — Postgres + pgvector, dlt + dbt pipeline, API, agent, frontend.
- `Postgres` `pgvector` `dlt` `dbt` `Docker` → [repo](https://github.com/nmp-dsci/data-qa-agent)

📌 [All repositories →](https://github.com/nmp-dsci?tab=repositories)

---

## ⚙️ How I work

Every repo above carries an `ai_specs/` folder that pins the problem, the eval, and the acceptance bar *before* any code — then Claude Code / Codex agents build against that spec. Systematic, not vibes.

---

## 🛠️ Skills

| | |
|---|---|
| **AI / LLM** | RAG (dense, hybrid, hierarchical, GraphRAG) · multi-agent pipelines · text-to-SQL · prompt optimisation (GEPA, DSPy) · SFT / RAFT · LLM evals |
| **Data science** | Python · SQL · statistics & econometrics · ML engineering · data visualisation |
| **Data engineering** | Pipelines & ETL (dlt, dbt) · data quality · Postgres / pgvector |
| **Cloud & infra** | Azure · AWS · Terraform · Docker · CI/CD |
| **Delivery** | End-to-end project delivery · stakeholder management · data strategy |

---

## 🎓 Background

BSc / BCom (Statistics, Finance & Econometrics), Macquarie University. Data scientist across tech, consulting, startup and corporate — comfortable owning a problem from data pipeline to stakeholder decision.
