<div align="center">

<!-- Animated Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=HIKI%20ZRX&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=fff&desc=Backend%20Architect%20%7C%20Distributed%20Systems%20Engineer&descAlignY=55&descSize=20"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&lines=Building+Scalable+Distributed+Systems;Event-Driven+Architecture;Microservices+%7C+Real-Time+Systems;AI-Powered+Backends" alt="Typing SVG" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=hikiuzrx&color=blueviolet&style=for-the-badge&label=PROFILE+VISITORS" />
<img src="https://img.shields.io/github/followers/hikiuzrx?style=for-the-badge&color=blue&label=FOLLOWERS&logo=github" />

</div>

<br/>

---

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A9FEF7&center=true&vCenter=true&width=440&lines=%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB+Ramzi+%22Hiki+ZRX%22+Gueracha" alt="Name Animation" />
</div>

<br/>

Backend engineer focused on **distributed systems**, **event-driven architecture** and **real-time platforms**. I build microservices in NestJS, FastAPI and Go, wire them together with NATS JetStream, Kafka and gRPC, and increasingly put AI agents on top of them.

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
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=white" />
<img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" />
<img src="https://img.shields.io/badge/BullMQ-FF6B6B?style=for-the-badge" />
</p>

### **Databases & Caching**
<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite,prisma&theme=dark" />
</p>
<p>
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white" />
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
<img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge" />
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
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge"/>
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
<img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6584?style=for-the-badge"/>
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
<img src="https://img.shields.io/badge/Casbin-409EFF?style=for-the-badge"/>
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
<img src="https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white"/>
<img src="https://img.shields.io/badge/BullMQ-FF6B6B?style=for-the-badge"/>
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

## ⏱️ **Coding Insights**

</div>

<!--START_SECTION:waka-->
**🐱 My GitHub Data** 

> 📦 156.1 kB Used in GitHub's Storage 
 > 
> 🏆 476 Contributions in the Year 2026
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 33 Public Repositories 
 > 
> 🔑 26 Private Repositories 
 > 
**I Mostly Code in TypeScript** 

```text
TypeScript               47 repos            ██████████████░░░░░░░░░░░   54.65 % 
Python                   13 repos            ████░░░░░░░░░░░░░░░░░░░░░   15.12 % 
Go                       6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   06.98 % 
Swift                    3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   03.49 % 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   02.33 % 
```



**Timeline**

![Lines of Code chart](https://raw.githubusercontent.com/hikiuzrx/hikiuzrx/master/assets/bar_graph.png)


 Last Updated on 28/09/2026 23:04:25 UTC
<!--END_SECTION:waka-->

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hikiuzrx&theme=react-dark&hide_border=true&area=true&bg_color=0D1117&color=F85D7F&line=F8D866&point=F85D7F" />

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
