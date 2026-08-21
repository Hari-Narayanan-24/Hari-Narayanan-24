<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7E600&background=FF000000&width=700&lines=Hari+Narayanan+Bhaskar;I+build+agentic+AI+systems+and+the+infrastructure+that+keeps+them+alive+in+production." alt="Typing SVG" />
</h1>

<p align="center">
  <b>I build agentic AI systems - and the infrastructure that keeps them alive in production.</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/hari-narayanan-bhaskar-174480205">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:harinarayanan_bhaskar@outlook.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

```python
class Hari:
    def __init__(self):
        self.location   = "United Kingdom"
        self.building   = "Turning ideas into working software"
        self.curious_about = ["multi-agent orchestration", "LLM observability",
                              "progressive delivery", "DevOps"]
        self.currently  = "Engineering daily, shipping side projects nightly"
```

---

## What I've built

### 🚀 AI-Assisted Multi-Cloud Release Orchestrator
Deployments shouldn't need a human staring at Grafana at midnight. So I built something that does the staring.

It watches live canary rollouts across **AWS EKS and Azure AKS** simultaneously, pulls latency, error-rate, CPU and replica metrics every 15 seconds, and runs an ML risk engine that scores SLO-violation probability at each rollout step then hands a recommendation to a human instead of pretending it knows best.


`Kubernetes` `Terraform` `Prometheus` `Grafana` `Argo Rollouts` `Jenkins` `Python`

---

### 🧠 Production RAG Platform
A retrieval system that actually holds up under load - document ingestion through serverless functions into a FAISS vector store, served by an async FastAPI backend with TTL caching and Redis-backed conversation state.

The interesting part was the rewrite: moving the orchestration layer from LangChain to **LangGraph** turned a brittle chain into a real state machine with approval routing. Autonomous tool selection replaced hardcoded intent classification — **60% better response efficiency**, and human-in-the-loop approval got **30% more effective** because the graph could finally pause in the right places.

`LangGraph` `FastAPI` `FAISS` `Redis` `Azure OpenAI`

---

### ⚡ Infrastructure that pays for itself
Terraform automation plus scheduled teardown of idle test environments — **70% cut in cloud spend**, zero developer complaints. The best infrastructure work is the kind nobody notices.

`Terraform` `Azure Functions` `CI/CD`

---

## Toolkit

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**AI & Agents**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## What I'm into right now

- **Agents that know when to stop** — human-in-the-loop design is the unglamorous half of agentic AI and the half that decides whether it ships
- **Observability for LLM systems** — we have decades of tooling for "is the service up" and almost none for "is the model still making sense"
- **Progressive delivery** — canaries, automated rollback, and letting data decide instead of vibes

---

<p align="center">
  <i>👨‍💻 Software Engineer | Building things, breaking things, learning things | Let’s talk computing.</i>
</p>
