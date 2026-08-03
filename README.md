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

### How It All Connects

> _This is the system I'm building — every project is a node in a larger AI infrastructure._

```mermaid
graph LR
    subgraph " "
        direction LR

        USER["🧑‍💻 User / Agent"]
        ROUTER["🔀 MCP Dynamic Router"]
        SPOTIFY["🎵 Spotify MCP"]
        GHOST["👻 ghostint"]
        BURN["📊 Burnmeter"]

        USER -- "natural language" --> ROUTER
        ROUTER -- "BM25 + semantic\nreranking" --> SPOTIFY
        ROUTER -- "tool dispatch" --> GHOST
        ROUTER -. "all LLM calls" .-> BURN

        SPOTIFY -- "gRPC + Protobuf" --> ROUTER
        GHOST -- "identity graph" --> USER
        BURN -. "cost telemetry" .-> USER
    end

    style USER fill:#1a1b27,stroke:#7aa2f7,color:#c0caf5
    style ROUTER fill:#1a1b27,stroke:#bb9af7,color:#c0caf5
    style SPOTIFY fill:#1a1b27,stroke:#1db954,color:#c0caf5
    style GHOST fill:#1a1b27,stroke:#f7768e,color:#c0caf5
    style BURN fill:#1a1b27,stroke:#e0af68,color:#c0caf5
```

<details>
<summary><b>🔍 What's happening here?</b></summary>
<br/>

The **MCP Dynamic Router** is the brain — it receives natural language requests and uses a 2-stage ranking pipeline (BM25 lexical matching → semantic embeddings → LLM reranking) to route them to the right tool server.

**Spotify MCP** and **ghostint** are tool servers that speak gRPC + MCP protocol back to the router. **Burnmeter** silently observes every LLM call across the system and tracks token usage & cost in real-time.

The goal: a modular, observable AI infrastructure where adding a new capability is just deploying another MCP server.
</details>

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

### 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kavinbm)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kavin-bm)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kavinbm16@gmail.com)
