# Hi, I'm Kavin 👋

**Applied AI Engineer** at [Machani Robotics](https://machani.tech) · Building production AI infrastructure for robotics

I work at the intersection of **LLMs** and **real-world systems** — designing gRPC-MCP server architectures, real-time speech pipelines, and local-first observability tools.

```
📍 Bangalore / Chennai, India
🎓 B.E. Computer Science — College of Engineering, Guindy (Anna University)
⚡ Currently: Production AI Infra for Robotics & Stream RAG Routing
```

---

### What I Build

| | Project | What it does |
|---|---|---|
| 🔀 | **[MCP Dynamic Router](https://github.com/Kavin-bm/Mcp-Dynamic-Router)** | High-performance tool router for Model Context Protocol — BM25 + semantic embeddings + LLM reranking with Stream RAG for partial speech transcripts |
| 📊 | **[Burnmeter](https://github.com/Kavin-bm/Burnmeter)** | Local-first LLM token usage & cost observability dashboard — tracks spend across OpenAI, Gemini, and other providers |
| 🎵 | **[Spotify MCP Server](https://github.com/Kavin-bm/Spotify-MCP)** | Hybrid gRPC + MCP server exposing Spotify as AI-native tools for LLM agents |
| 👻 | **[ghostint](https://github.com/Kavin-bm/ghostint)** | AI-powered OSINT framework that traces digital footprints & maps identity graphs |

---

### Tech

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
  <img src="https://img.shields.io/badge/Protobuf-00599C?style=flat-square" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-7B61FF?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

**Core:** LLMs · RAG · Agentic Workflows · Vector DBs · Model Evaluation · Prompt Engineering  
**Infra:** gRPC · Protobuf · MCP · GraphQL · NATS · OpenTelemetry · PostgreSQL

---

<details>
<summary>📦 <code>kavin.Dockerfile</code></summary>
<br/>

```dockerfile
FROM ubuntu:latest AS kavin

LABEL maintainer="kavinbm16@gmail.com"
LABEL version="2026.08"
LABEL description="Applied AI Engineer — ships infra, not just notebooks"

ENV LOCATION="Bangalore, India"
ENV FUEL="black coffee, no sugar, infinite refills"
ENV EDITOR="vscode + vim motions"
ENV DEBUGGER="printf and prayer"

# Install core runtime
RUN apt-get update && apt-get install -y \
    golang python3 grpc protobuf-compiler \
    curiosity stubbornness patience \
    && rm -rf /var/lib/apt/lists/*

# Things I mass-uninstalled
RUN apt-get purge -y \
    impostor-syndrome \
    "it-works-on-my-machine" \
    sleep

WORKDIR /home/kavin

EXPOSE 50051 8080
HEALTHCHECK CMD curl -f http://localhost/coffee-level || exit 1

CMD ["make", "impact"]
```

</details>

---

### 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kavinbm)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kavin-bm)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kavinbm16@gmail.com)
