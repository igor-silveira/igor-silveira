<div align="center">

# Igor Silveira

**Senior Software Engineer**

7 years building backend systems that move real metrics - engagement, revenue, reliability.

Fintech | Media | Healthcare

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/igor-silveira/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:igorrsilveira05@gmail.com)

</div>

---

### Where I've shipped code

**Globo** (Top 5 media company worldwide) - Recommendation platform serving 25M+ users/day. Boosted engagement 30%. Collaborated directly with Google on the [Media Recommendations](https://cloud.google.com/solutions/media-entertainment) product.

**GoodRx** - Go & Python services powering the Gold subscription platform for millions of users. Grew subscribers by 2.3%.

**B3 (Brazilian Stock Exchange)** - Designed data infrastructure for a $20M cloud migration to AWS. Built a Python quality framework that raised data reliability by 90%.

---

### Featured Projects

<a href="https://github.com/igor-silveira/cortex-browser">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=cortex-browser&theme=github_dark&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=cortex-browser&hide_border=true" />
    <img alt="cortex-browser" src="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=cortex-browser&hide_border=true" />
  </picture>
</a>

**[cortex-browser](https://github.com/igor-silveira/cortex-browser)** - Browser perception layer for AI agents. Converts web pages into token-efficient semantic snapshots. Rust, MCP server.

```
Pipeline     Prune → Role Map → Collapse → Merge
Output       Compact accessibility tree with stable ref IDs
Reduction    90-95% fewer tokens than raw HTML
Transports   MCP stdio | Streamable HTTP + SSE
```

Key design decisions:
- **4-stage DOM pipeline** - strips scripts, styles, hidden elements, then maps ARIA semantics, collapses wrappers, and merges siblings
- **Stable ref IDs** - hash-based refs survive DOM mutations, enabling reliable element interaction across snapshots
- **Viewport-aware snapshots** - marks off-screen elements, supports scroll navigation, and returns diffs instead of full re-snapshots
- **Multi-tab state management** - independent tab state with CDP connection pooling and DOM mutation observers

---

<a href="https://github.com/igor-silveira/Pincer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=Pincer&theme=github_dark&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=Pincer&hide_border=true" />
    <img alt="Pincer" src="https://github-readme-stats.vercel.app/api/pin/?username=igor-silveira&repo=Pincer&hide_border=true" />
  </picture>
</a>

**[Pincer](https://github.com/igor-silveira/Pincer)** - A self-hosted, security-first AI assistant gateway. Single Go binary, zero runtime dependencies.

```
Messaging       Telegram | Discord | Slack | WhatsApp | Matrix | WebChat
LLM Providers   Anthropic | OpenAI | Gemini | Ollama
Security        AES-256-GCM encryption | Ed25519 skill signing | sandboxed tools
Protocols       HTTP | WebSocket | gRPC | MCP client | A2A server
```

Key design decisions:
- **Sandboxed tool execution** - process-level and container-level isolation for shell, file, HTTP, and browser tools
- **Persistent memory** - structured key-value store with immutable key protection and content-addressed hashing
- **Human-in-the-loop** - configurable approval modes per tool (auto / ask / deny)
- **Smart context windowing** - hash-based change detection to avoid redundant token usage

---

### Other Projects

| Project | Description |
|---------|-------------|
| [video-encoder-microservice](https://github.com/igor-silveira/video-encoder-microservice) | Go microservice that converts MP4 to MPEG-DASH for adaptive streaming. RabbitMQ + Bento4 + GCS. |
| [python-boilerplate](https://github.com/igor-silveira/python-boilerplate) | Production-ready Python project template |
| [ray-tracing](https://github.com/igor-silveira/ray-tracing) | Ray tracer built from scratch |
| [terraform-provider-tsuru](https://github.com/igor-silveira/terraform-provider-tsuru) | Terraform provider for the Tsuru PaaS |

---

### Tech Stack

<div align="center">

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Infrastructure & Cloud**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)

**Frameworks & Tools**

![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

</div>

---

<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=igor-silveira&show_icons=true&theme=github_dark&hide_border=true&hide_title=true&hide_rank=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=igor-silveira&show_icons=true&hide_border=true&hide_title=true&hide_rank=true" />
    <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=igor-silveira&show_icons=true&hide_border=true&hide_title=true&hide_rank=true" />
  </picture>

</div>
