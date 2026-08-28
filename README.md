# Hi there, I'm Surbhit

**Software Engineer in San Francisco**, building LLM-powered systems — agents, retrieval, and the data plumbing underneath them. MS in Computer Science from **USC** (Dec 2025). I like taking messy, fragmented internal data and turning it into something you can just *ask a question of*.

<p align="left">
<a href="https://linkedin.com/in/surbhit-pratik" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:surbhitpratik15@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<img src="https://img.shields.io/badge/San_Francisco,_CA-2b2b2b?style=for-the-badge&logo=googlemaps&logoColor=white" alt="San Francisco, CA" />
</p>

---

## What I'm Working On

**Software Engineer @ [Easley Dunn Productions](https://easleydunnproductions.com/)** *(Feb 2026 - Present)*

- Built an **LLM-driven observability pipeline** over GCP BigQuery + Firebase — schema-grounded SQL generation with execution guardrails, behind a conversational agent interface. Automates ~80% of ad-hoc analytics requests.
- Designed a **stateful memory layer** with dynamic context compression for multi-turn analytical sessions, cutting token consumption ~35%.
- Shipped an **MCP server on Cloud Run** exposing 3 custom tools that index fragmented internal data (Firebase, GitHub, meeting transcripts) behind one retrieval interface.
- Instrumented **70+ gameplay events** in a Unity/C# app via Firebase Analytics, routing 12 user flows into Looker Studio dashboards.

---

## Projects I'm Proud Of

| Project | What it is |
|---|---|
| **[Mia](https://github.com/surbhit20/mia)** — [demo](https://youtu.be/PSs0ckJ0jt4) | A real-time voice agent that joins your Google Meet as a live participant. Streaming STT + Claude Opus over rolling call state, concurrent Calendar/Meet tool calls, ~2.9s p95 speech-to-speech. An async intent classifier suppresses prompt injection and out-of-scope completions at <150ms added p95. |
| **[CodeSense](https://github.com/surbhit20/CodeSense)** — [demo](https://youtu.be/YI1jCXRi_IU) | Agentic codebase retrieval and chat. A custom **AST-based RAG** system paired with SQLite FTS BM25 for precise, lazy context lookups — 68% less code exploration time, 73.4% less model context burned. |
| **[Multi-Agent Orchestration](https://github.com/surbhit20/multi-agent-orchestration)** | Made AI play Mafia. 6+ autonomous agents in async social deduction — no turn order, just a shared conversation each agent decides when to interrupt. Two-part brain architecture (Scheduler & Generator) over a concurrency-safe shared context. |
| **[analystbot](https://github.com/surbhit20/discord-agentic)** | A Discord bot that turns game analytics in BigQuery into a teammate you can talk to. Schema-grounded SQL, cost-aware dry runs, and honest refusals when the data genuinely can't answer. |

---

## Where I've Been

- **Amphenol** — *Software Engineering Intern (Summer 2025)*: Built a lightweight Internal Developer Portal (Python webhook engine + GitHub/Jira REST APIs) that automated repo provisioning and naming governance, cutting project setup time >30%. Plus a nomenclature microservice that reduced downstream quoting errors 23%.
- **HighRadius** — *Software Developer Intern (2022)*: Full-stack loan repayment prediction app (React/Node + Java Servlets, JDBC, MySQL) with server-side pagination and indexed queries; Random Forest & Gradient Boosting models cut repayment discrepancies 14.3%.
- **Coal India Ltd** — *Software Developer Intern (2021)*: Accommodation search app on Django + PostgreSQL, containerized with Docker, deployed with Terraform over AWS S3 and RDS.

---

## Tech Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-4B32C3?style=flat-square&logo=meta&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

**Infra**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## GitHub at a Glance

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=surbhit20&theme=radical" alt="GitHub stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=surbhit20&theme=radical" alt="Top languages by commit" />
</p>

---

<p align="center"><i>Always up for a conversation about agents, retrieval, or anything that makes a codebase easier to live in.</i></p>
