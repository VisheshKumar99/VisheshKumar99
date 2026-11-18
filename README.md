# 👋 Hi, I'm Vishesh Kumar

### Senior Backend Engineer | GenAI / LLM Engineer | Distributed Systems

> Building **high-scale backend systems** and **production-oriented AI applications** with Golang, Node.js, AWS, Kafka, Redis, LLMs, RAG and Agentic AI.

[![GitHub](https://img.shields.io/badge/GitHub-visheshkumar99-181717?style=for-the-badge\&logo=github)](https://github.com/visheshkumar99)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vishesh%20Kumar-0A66C2?style=for-the-badge\&logo=linkedin)](#)
[![LeetCode](https://img.shields.io/badge/LeetCode-visheshkumar99-FFA116?style=for-the-badge\&logo=leetcode)](#)

---

## 🧠 About Me

I'm a **Backend Engineer with 5+ years of experience** designing and building distributed, event-driven systems.

My core engineering experience includes:

* ⚡ High-throughput backend systems using **Golang & Node.js**
* 🧩 Microservices and distributed system architecture
* 📡 Real-time systems using **WebSockets, Kafka & Redis**
* 🗄️ PostgreSQL, MongoDB, SQL Server & Redis
* ☁️ AWS, Docker, Kubernetes & CI/CD
* 📈 Performance optimization, scalability & fault tolerance
* 🤖 LLM applications, RAG & Agentic RAG
* 🧠 LangChain & LangGraph based AI workflows
* 🔌 MCP-based AI tool integration
* 🧪 LLM evaluation, observability & LLMOps

Currently expanding from **Backend Engineering → Backend + GenAI Engineering**.

---

# 🚀 GenAI Engineering

I'm building practical AI systems rather than only experimenting with chatbots.

### LLM Stack

```text
LLMs
├── OpenAI
├── Ollama
├── Hugging Face
└── Local / Open-source LLMs
```

### AI Application Stack

```text
LangChain
LangGraph
LangSmith
RAG
Agentic RAG
MCP
Embeddings
Vector Databases
Prompt Engineering
Tool Calling
Structured Outputs
LLM Evaluation
LLMOps
```

### Current GenAI Architecture

```text
                    ┌──────────────────────┐
                    │       User           │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    AI Application    │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      LangGraph       │
                    │   Agent Orchestration│
                    └──────────┬───────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        ┌───────────┐   ┌────────────┐   ┌────────────┐
        │    RAG    │   │    MCP     │   │   Tools    │
        └─────┬─────┘   └──────┬─────┘   └──────┬─────┘
              │                │                │
              ▼                ▼                ▼
        ┌───────────┐   ┌────────────┐   ┌────────────┐
        │ Vector DB │   │ MCP Server │   │ APIs / DB  │
        └───────────┘   └────────────┘   └────────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │        LLM           │
                    │ OpenAI / Ollama / HF │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ LangSmith / Eval     │
                    │ Observability        │
                    └──────────────────────┘
```

---

# 🛠️ Tech Stack

## Languages

<p>
<img src="https://skillicons.dev/icons?i=go,python,nodejs,typescript,javascript" />
</p>

**Golang · Python · Node.js · TypeScript · JavaScript**

---

## Backend & APIs

<p>
<img src="https://skillicons.dev/icons?i=graphql" />
</p>

**REST APIs · GraphQL · gRPC · WebSockets · Microservices**

---

## Databases

<p>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis" />
</p>

**PostgreSQL · MongoDB · SQL Server · Redis**

---

## Messaging & Streaming

**Apache Kafka · RabbitMQ · AWS SQS · Event-Driven Architecture**

---

## Cloud & Infrastructure

<p>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,linux,nginx,git,github" />
</p>

**AWS · Docker · Kubernetes · CI/CD · Nginx · Linux · Git**

---

## GenAI

<p>
<img src="https://img.shields.io/badge/LLM-Engineering-black?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAG-AI-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/Agentic%20AI-LangGraph-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/LangChain-AI-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/LangSmith-Observability-purple?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCP-Tools-blue?style=for-the-badge" />
</p>

**LLMs · Prompt Engineering · LangChain · LangGraph · LangSmith · RAG · Agentic RAG · MCP · Embeddings · Vector Databases · Tool Calling · LLM Evaluation · LLMOps · Ollama · Hugging Face**

---

# 🔥 Featured Projects

## 🤖 Personal AI / Portfolio Agent

An agentic RAG system that understands my professional profile and can answer questions about my:

* Resume
* GitHub projects
* Technical experience
* Skills
* Professional background
* Learning journey

### Architecture

```text
Resume / GitHub / LinkedIn
            │
            ▼
       Document Loader
            │
            ▼
      Text Processing
            │
            ▼
        Embeddings
            │
            ▼
       Vector Database
            │
            ▼
        ┌──────────┐
        │  Agent   │
        └────┬─────┘
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
      RAG   MCP   Tools
       │     │     │
       └─────┼─────┘
             ▼
            LLM
             │
             ▼
      Grounded Response
```

**Stack:** Python · LangChain · LangGraph · LangSmith · RAG · Vector DB · Ollama · OpenAI

---

# 📄 Resume Intelligence Agent

A document-analysis agent capable of processing resumes and extracting structured information.

### Pipeline

```text
PDF
 │
 ▼
Document Loader
 │
 ▼
Text Extraction
 │
 ▼
LLM Analysis
 │
 ├── Skills
 ├── Experience
 ├── Projects
 ├── Education
 └── Achievements
 │
 ▼
Embeddings
 │
 ▼
Vector Database
 │
 ▼
RAG / Agent
```

**Stack:** Python · LangChain · LangGraph · Ollama · Embeddings · Vector DB · RAG

---

# 📊 Market Mojo – Data Ingestion & Analytics Platform

Designed Kafka-based event-driven data pipelines handling **50M+ daily events**.

### Key Engineering

* Kafka partitioning
* Consumer groups
* Retry queues
* Idempotent processing
* Scheduled workflows
* PostgreSQL
* Redis
* Golang concurrency
* AWS infrastructure

Achieved **40–60% performance improvements** through storage and processing optimizations.

---

# 📡 Real-Time Stock Broadcasting

Low-latency market-data broadcasting platform.

```text
Market Data
     │
     ▼
   Kafka
     │
     ▼
  Processing
     │
     ▼
   Redis
     │
     ▼
 WebSockets
     │
     ▼
   Clients
```

**Stack:** Golang · Kafka · Redis · WebSockets · PostgreSQL · MongoDB

Designed for high-concurrency real-time market data distribution.

---

# 🚆 Railway Real-Time Telemetry

Real-time train telemetry and streaming system capturing:

* GPS
* Speed
* Vibration
* Train telemetry

### Architecture

```text
Train Sensors
     │
     ▼
   Kafka
     │
     ▼
Stream Processing
     │
     ▼
 WebSocket
     │
     ▼
Monitoring UI
```

Supported **50+ concurrent train runs**.

---

# 🔔 Multi-Channel Notification System

Event-driven notification platform using:

**Golang + Kafka + RabbitMQ + Redis + MongoDB**

Implemented:

* Retry mechanisms
* Fault tolerance
* Event-driven processing
* Monitoring
* Reliable message delivery

---

# 🧱 System Design

I regularly work with:

```text
Microservices
Distributed Systems
Event-Driven Architecture
CQRS
Caching
Database Sharding
Replication
Message Queues
Load Balancing
Rate Limiting
Circuit Breaker
Fault Tolerance
High Availability
Horizontal Scaling
Observability
```

### Typical Architecture

```text
                 ┌──────────────┐
                 │   Clients    │
                 └──────┬───────┘
                        │
                        ▼
                 ┌──────────────┐
                 │ Load Balancer│
                 └──────┬───────┘
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
        ┌───────────┐       ┌───────────┐
        │ API Node  │       │ API Node  │
        └─────┬─────┘       └─────┬─────┘
              │                   │
              └─────────┬─────────┘
                        ▼
                  ┌───────────┐
                  │   Redis   │
                  └─────┬─────┘
                        │
                        ▼
                  ┌───────────┐
                  │  Kafka    │
                  └─────┬─────┘
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
        ┌───────────┐       ┌───────────┐
        │ Consumer  │       │ Consumer  │
        └─────┬─────┘       └─────┬─────┘
              │                   │
              └─────────┬─────────┘
                        ▼
                   PostgreSQL
```

---

# 📈 Engineering Focus

```text
Backend Engineering
        +
Distributed Systems
        +
System Design
        +
Cloud Engineering
        +
GenAI
        +
Agentic AI
```

My long-term focus is building **AI-powered distributed systems** that can operate reliably at production scale.

---

# 🧪 Currently Learning

```text
LLM Architecture
Transformer Architecture
LLM Pre-training
Fine-tuning
LoRA / QLoRA
RLHF / DPO
RAG Optimization
Agentic RAG
Multi-Agent Systems
MCP
LLM Evaluation
LLMOps
AI Observability
Inference Optimization
Model Serving
Distributed AI Systems
```

---

# 🎯 Engineering Philosophy

> **Build systems that are simple first, scalable when required, observable in production, and measurable through data.**

I care about:

* Correctness
* Scalability
* Reliability
* Performance
* Maintainability
* Developer experience
* Production observability

---

# 📊 GitHub Stats

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=visheshkumar99&show_icons=true&theme=github_dark&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=visheshkumar99&theme=dark&hide_border=true" />

</p>

---

# 🐍 Contribution Graph

![snake gif](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg)

---

# 🎬 Engineering in Motion

<p align="center">

<img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="600"/>

</p>

> **Code → Architecture → AI → Production**

---

# 📫 Connect With Me

**Email:** [visheshkumar.work@gmail.com](mailto:visheshkumar.work@gmail.com)

**GitHub:** [github.com/visheshkumar99](https://github.com/visheshkumar99)

---

<p align="center">

### ⚡ Backend Engineer × GenAI Engineer

**Golang • Distributed Systems • Kafka • Redis • AWS • LLM • RAG • Agentic AI**

</p>
