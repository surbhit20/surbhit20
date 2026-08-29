# Hi, I'm Surbhit

Software engineer in San Francisco. I build **agents** — voice agents that hold a real-time conversation, retrieval agents that can navigate a codebase or a warehouse, and multi-agent systems where a room full of them argue with each other and nobody is in charge.

The kinds I keep coming back to:

| Kind | What makes it interesting |
|---|---|
| **Voice** | Real-time speech in, speech out. Latency is the whole game — anything above a beat and it stops feeling like a conversation. Knowing when *not* to talk matters as much as what it says. |
| **Retrieval** | Agents grounded in something real — an AST, a BM25 index, a live SQL schema — so they pull actual functions and actual numbers instead of plausible-looking guesses. |
| **Multi-agent** | No turn order, no central scheduler. Every agent watches a shared conversation and decides for itself when to speak, which is where the interesting emergent behaviour lives. |
| **Tool-using** | Agents wired into real APIs, where a wrong call has consequences. Most of the work is deciding what the model is *not* allowed to do. |

Most of what I find interesting lives at the unglamorous end of this: grounding a model in a real schema so it can't make things up, keeping context small enough to stay cheap, and deciding what an agent should refuse to answer. The demo is easy; the guardrails are the actual project.

<p align="left">
<a href="https://surbhitpratik.com" target="_blank"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio" /></a>&nbsp;
<a href="https://linkedin.com/in/surbhit-pratik" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:surbhitpratik15@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<img src="https://img.shields.io/badge/San_Francisco,_CA-2b2b2b?style=for-the-badge&logo=googlemaps&logoColor=white" alt="San Francisco, CA" />
</p>

---

## What I'm Building

**[Mia](https://github.com/surbhit20/mia)** · *voice agent* — joins your Google Meet as a live participant

Say "Hey Mia" mid-call and she looks up your schedule, drafts an email, or proposes an event — acknowledging out loud the moment she hears you, then confirming once it's done. When the meeting ends she writes a sectioned summary to a Google Doc and mails it to you. The interesting part was latency and knowing when to stay quiet.

<a href="https://youtu.be/PSs0ckJ0jt4" title="Watch the Mia demo on YouTube"><img src="https://img.youtube.com/vi/PSs0ckJ0jt4/maxresdefault.jpg" width="420" alt="Mia demo video thumbnail" /></a>

<a href="https://youtu.be/PSs0ckJ0jt4">&#9654;&#65039;&nbsp; <b>Watch the demo</b></a>

**[CodeSense](https://github.com/surbhit20/CodeSense)** · *retrieval agent* — every repo, finally making sense

Paste a GitHub URL and get an interactive graph of the codebase you can click through, with an agent that explains what any file actually does. Built on AST-based retrieval and BM25 rather than naive embedding chunks, so it pulls whole functions instead of arbitrary 500-character windows.

<a href="https://youtu.be/YI1jCXRi_IU" title="Watch the CodeSense demo on YouTube"><img src="https://img.youtube.com/vi/YI1jCXRi_IU/maxresdefault.jpg" width="420" alt="CodeSense demo video thumbnail" /></a>

<a href="https://youtu.be/YI1jCXRi_IU">&#9654;&#65039;&nbsp; <b>Watch the demo</b></a>

**[Multi-Agent Orchestration](https://github.com/surbhit20/multi-agent-orchestration)** · *multi-agent framework* — I made AI play Mafia

A framework for social deduction games between LLM agents. No turn order: every player watches a shared conversation and decides for itself when to speak, so you get interruptions, overlapping replies, and genuine "is typing…" pressure. Agents lie, form alliances, and occasionally out themselves.

**[analystbot](https://github.com/surbhit20/discord-agentic)** · *tool-using agent* — talk to your analytics in Discord

Ask it a question in plain English and it writes SQL against your real BigQuery schema. Dry-runs every query so it never surprises you with a bill, and tells you honestly when the data simply can't answer what you asked instead of guessing.

---

## Currently Poking At

- MCP servers — putting scattered internal data behind one retrieval interface
- Async orchestration: letting agents interrupt each other without deadlocking
- Keeping multi-turn agent context small without losing the thread
- Speech-to-speech latency, and how much of it you can hide
- Prompt injection defense that doesn't cost you a second round trip
- Evaluating agents that are allowed to say "I don't know"

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
