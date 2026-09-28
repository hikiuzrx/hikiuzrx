<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=HIKI%20ZRX&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=fff&desc=Software%20Engineer%20%7C%20Backend%20and%20DevOps&descAlignY=55&descSize=20"/>

# Hi, I'm Ramzi "Hiki ZRX" Gueracha 👋

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&lines=Software+Engineer;Backend+and+DevOps;Distributed+and+Event-Driven+Systems;AI-Powered+Backends" alt="Typing SVG" /></a>

<img src="https://komarev.com/ghpvc/?username=hikiuzrx&color=blueviolet&style=for-the-badge&label=PROFILE+VISITORS" />
<img src="https://img.shields.io/github/followers/hikiuzrx?style=for-the-badge&color=blue&label=FOLLOWERS&logo=github" />

</div>

<br/>

I'm a **software engineer** from Algeria working across **backend** and **DevOps**.

I like owning a system end to end: designing the services, wiring them together, and getting them running reliably in the cloud.

- ⚙️ **Backend** — microservices in NestJS, FastAPI and Go, event-driven with NATS JetStream and Kafka, gRPC and WebSockets for real-time
- ☁️ **DevOps** — Docker, CI/CD with GitHub Actions, infrastructure on AWS and GCP, observability with Prometheus and Grafana
- 🤖 **AI systems** — agent pipelines, RAG and self-hosted LLMs wired into production backends
- 🗄️ **Data** — PostgreSQL, MongoDB, Redis, Cassandra, ClickHouse, InfluxDB, Oracle

<br/>

---

<br/>

<!-- Tech Stack Section -->
<div align="center">

## 🛠️ **Technology Arsenal**

### **Languages**
<p>
<img src="https://skillicons.dev/icons?i=typescript,python,go,cs,c,java,javascript,bun&theme=dark" />
</p>

### **Backend & Frameworks**
<p>
<img src="https://skillicons.dev/icons?i=nestjs,fastapi,express,dotnet,nodejs,laravel&theme=dark" />
</p>

### **Messaging & Real-Time**
<p>
<img src="icons/messaging.svg" />
</p>

### **Databases & Caching**
<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite,prisma&theme=dark" />
</p>
<p>
<img src="icons/databases.svg" />
</p>

### **Frontend & UI**
<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css,sass&theme=dark" />
</p>

### **DevOps & Cloud**
<p>
<img src="https://skillicons.dev/icons?i=docker,aws,gcp,git,github,githubactions,linux,postman&theme=dark" />
</p>

</div>

<br/>

---

<br/>

<!-- Projects Showcase -->
<div align="center">

## 🚀 **Flagship Projects**

</div>

<details open>
<summary><b>📜 Derham - AI-Driven Contract Lifecycle Management</b></summary>
<br/>

> **From upload to decision** — reads contracts, checks them against your own policies, and gives teams a real review workflow

```yaml
Ingestion: DOCX, PDF, scanned documents (OCR), pasted text
AI Pipeline: Clause segmentation → contract classification → policy compliance
Messaging: NATS JetStream job queue feeding extraction & compliance workers
Retrieval: Policy clauses embedded in Qdrant
Models: Local Ollama by default, or Qwen on a self-hosted vLLM GPU with automatic fallback
```

**Tech Stack:**
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white"/>
<img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge&logo=vllm&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
</p>

**Key Features:**
- 🔍 **Clause-level analysis** — segments contracts and scores each clause against a policy library with cited findings
- 🤖 **Provider-agnostic LLM layer** — one model factory for Ollama, vLLM, OpenAI, Anthropic, Google or any OpenAI-compatible endpoint
- 👥 **Review workflow** — comments, @mentions, reviewer sign-off and conflict-safe editing
- 🧾 **Tamper-evident activity log** — every action on a contract is traceable
- 💬 **AI chat agent** — reaches data only through a permission-enforcing MCP bridge
- ⚡ **Live updates** — SSE streaming from backend to UI

🔗 [Repository](https://github.com/wailbentafat/Contract-Lifecycle-Management)

</details>

<details>
<summary><b>🤖 CAPI - Intelligent Analytics Engine</b></summary>
<br/>

> **AI-Powered Data Analysis Platform** — Transforming raw data into actionable insight

```yaml
Backend: FastAPI service with LangChain agents
Retrieval: ChromaDB vector store over PostgreSQL data
Focus: Dynamic, natural-language analytics
```

**Tech Stack:**
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Key Features:**
- 🧠 AI-driven insights over structured data
- ⚡ Real-time data processing
- 🔐 Layered security
- 📊 Interactive visualization dashboards

</details>

<details>
<summary><b>🎥 VAST - Real-Time Collaboration Platform</b></summary>
<br/>

> **Microservices-Based Collaboration System** — Built for low-latency communication

```yaml
Architecture: Distributed microservices
Media Layer: WebRTC SFU in Go
Concurrency: Goroutines + channel-based routing
Security: Casbin access control + AuthN/AuthZ
Data: PostgreSQL + ClickHouse
```

**Tech Stack:**
<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black"/>
</p>

**Core Highlights:**
- 🧩 **Microservices Design** — Independent services for collaboration flows
- ⚡ **High-Performance SFU** — Optimized media forwarding and connection handling
- 🔐 **Policy-Driven Security** — Casbin-based access control integrated with authentication
- 🧾 **Audit-First Architecture** — Centralized logs across services for traceability

</details>

<details>
<summary><b>🛰️ RedSentinel - Redis Observability Platform</b></summary>
<br/>

> **Real-time Redis Observability & Command Tracing** — Full visibility into Redis workloads

```yaml
Domain: Redis / Redis Cluster observability
Streaming: NATS JetStream event backbone
Storage: Structured command logs in SQLite
Monitoring: Prometheus + Grafana
```

**Tech Stack:**
<p>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
</p>

**Core Features:**
- 🔍 Capture Redis commands across standalone and cluster deployments
- 📡 Durable event streaming and replay via JetStream
- 🗂️ Queryable command traces for dashboards and analytics
- 🧠 Cluster-aware visibility across nodes, slots and replica topology

</details>

<details>
<summary><b>🔔 SkyBell - Notification Infrastructure</b></summary>
<br/>

> **Multi-Tenant Notification Service** — Real-time delivery over gRPC and WebSockets

```yaml
Architecture: Distributed notification system
Protocols: gRPC + WebSocket
Queue: BullMQ backed by Redis
```

**Tech Stack:**
<p>
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGZpbGw9IiNmZmYiIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBkPSJNOC44IDM4IDAgNDdsOSA4LjggMy40LTMuNUg5LjNsLTUuNC01LjQgNS4zLTUuNGgzLjJ6bTMuNiAzLjUuNy43LjctLjd6bS43LjctNCA0LjFoOHptNCA0IC42LjctLjYuNmgxMS40bC0uNi0uNy42LS42em0xMS40IDBoNC4ybC0yLjEtMmgyLjNsMi43IDIuNi0yLjcgMi43aC0yLjNsMi41IDIuNSA1LjItNS4yLTUuMi01LjJ6bTIuMSAzLjMgMi0yaC00em0tMTMuNS0yaC04bDQgNHptLTQgNC0uNy44aDEuNHptMTAyLjQtNy43YTE4IDE4IDAgMCAwLTEyLjYgNSAxNyAxNyAwIDAgMC0zLjcgNS43UTk4IDU3LjggOTggNjEuNnEwIDQgMS4zIDcuMWExNyAxNyAwIDAgMCAxNi4zIDEwLjdxMiAwIDQtLjVhMTcgMTcgMCAwIDAgMy41LTEuMyAxMyAxMyAwIDAgMCAyLjktMmwyLjEtMi40LTIuOC0ycS0xIDEuNS0yIDIuNGExMCAxMCAwIDAgMS0yLjUgMS42cS0xLjIuNi0yLjYuOGwtMi42LjJhMTQgMTQgMCAwIDEtMTAuMi00LjQgMTQgMTQgMCAwIDEtMi43LTQuNiAxNiAxNiAwIDAgMS0xLTUuNnEwLTMgMS01LjZhMTMgMTMgMCAwIDEgMTUuNi04LjcgMTMgMTMgMCAwIDEgNC41IDIuNXExIC45IDEuNSAxLjZsMy0yLjJxLTIuMi0zLTUuNC00LjFhMTcgMTcgMCAwIDAtNi4zLTEuM20tNzEuNS45djMzLjhoMy40VjYyLjhoNS43bDkuMyAxNS43aDQuMmwtOS43LTE2cTQuMi0uNCA2LjQtMi44YTggOCAwIDAgMCAyLjItNnEwLTQuNS0zLTYuOHQtOC4xLTIuMnptMjguNSAwdjMzLjhINzZWNjIuOGg2LjRxNS4xIDAgOC0yLjN0My02LjgtMy02LjgtOC0yLjJ6bS0yNS4xIDMuMmg2LjFxMi4yIDAgMy45LjR0Mi42IDEuM3EuOS43IDEuMyAxLjkuNSAxIC41IDIuMnQtLjUgMi4zYTUgNSAwIDAgMS0xLjMgMnEtMSAuNy0yLjYgMS4ydC0zLjkuNGgtNi4xem0yOC42IDBoNS41cTIuMyAwIDMuOS40dDIuNSAxLjNxMSAuNyAxLjQgMS45YTYgNiAwIDAgMSAuNSAyLjJxMCAxLjMtLjUgMi4zYTUgNSAwIDAgMS0xLjQgMnEtLjkuNy0yLjUgMS4yLTEuNS40LTQgLjRINzZ6bS01My4zIDcuN3EtMi41IDAtNC42LjlhMTEgMTEgMCAwIDAtMy42IDIuNCAxMiAxMiAwIDAgMC0yLjMgMy43IDEyIDEyIDAgMCAwIDAgOSAxMSAxMSAwIDAgMCAyLjUgMy43IDEyIDEyIDAgMCAwIDMuNyAyLjRxMi4xLjggNC42LjhhMTIgMTIgMCAwIDAgNC42LTEgOSA5IDAgMCAwIDMuNy0zLjJoLjF2NHEwIDEuOS0uNCAzLjRhNyA3IDAgMCAxLTEuNSAyLjggNyA3IDAgMCAxLTIuNyAycS0xLjcuNi00IC42LTIuOCAwLTUtMS4xYTEwIDEwIDAgMCAxLTMuNi0zbC0yLjQgMi41QTE0IDE0IDAgMCAwIDIyLjYgOTBhMTQgMTQgMCAwIDAgNi0xLjIgMTAgMTAgMCAwIDAgMy43LTIuOCAxMCAxMCAwIDAgMCAxLjgtMy44cS41LTIuMS41LTMuOVY1Ni4yaC0zLjJ2My43cS0xLTEuMy0yLjEtMi4xTDI3IDU2LjRsLTIuMi0uNnptLjQgMi45cTEuOSAwIDMuNS42dDIuNyAyYTggOCAwIDAgMSAxLjYgMi42IDEwIDEwIDAgMCAxIC42IDMuNHEwIDEuOS0uNiAzLjVhOCA4IDAgMCAxLTEuOCAyLjcgOSA5IDAgMCAxLTIuOCAxLjcgOSA5IDAgMCAxLTMuMi42cS0xLjggMC0zLjMtLjZhOSA5IDAgMCAxLTIuNi0yIDkgOSAwIDAgMS0xLjgtMi42IDkgOSAwIDAgMS0uNy0zLjMgOSA5IDAgMCAxIC43LTMuNCA5IDkgMCAwIDEgMS44LTIuNyA5IDkgMCAwIDEgMi42LTEuOSA4IDggMCAwIDEgMy4zLS42Ii8%2BPC9zdmc%2B"/>
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

**Core Features:**
- 🎯 **Dynamic Namespaces** — Multi-tenant isolation
- 🔐 **Auth & Authorization** — JWT-based security
- ⚙️ **Job Concurrency** — Queue-based delivery with retries
- 📡 **Bi-directional Comms** — Real-time updates to clients

</details>

<br/>

---

<br/>

<!-- Organizations -->
<div align="center">

## 🌐 **Community & Organizations**

**Capturini** • **Envirm** • **GDG Algiers** • **ISDBI** • **Orka-Tatweer** • **RooninKai** • **Saitrm** • **The Basee**

</div>

<br/>

---

<br/>

<!-- Coding Activity -->
<div align="center">

## 📈 **Contribution Activity**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hikiuzrx/hikiuzrx/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/hikiuzrx/hikiuzrx/output/github-contribution-grid-snake.svg" />
</picture>

</div>

<br/>

---

<br/>

<!-- Connect Section -->
<div align="center">

## 🤝 **Let's Connect**

<a href="https://github.com/hikiuzrx">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://linkedin.com/in/hikiuzrx">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/hikiuzrx">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="mailto:hikiuzrx@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br/><br/>

**Open for:** Collaboration • Freelance & Consulting • Open Source


<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling"/>

</div>
