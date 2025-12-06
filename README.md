<h1 align="center">👋 Hi, I'm <span style="color:#4B9CD3">Sourabh Gupta</span></h1>
<h3 align="center">Senior Python Developer | AI Engineer | Agentic Systems Architect | Backend & DevOps | Cloud Practitioner</h3>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
  <!-- <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="500"> -->
  <img src="https://user-images.githubusercontent.com/74038190/212747107-5b654ba5-31c6-4366-b42b-51b822e9bc52.gif" width="400">
  <img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="135">
  <!-- <img src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="230"/> -->
  <!-- <img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="200"> -->
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="1000">

## 🧑‍💻 About Me

I am a **Python Developer & AI Automation Engineer** with hands-on experience building **agentic workflows**, **multi-agent NL2SQL systems**, **AI-assisted DevOps**, and **end-to-end backend architectures** deployed in enterprise environments.

My specialization is in **LLM-driven automation systems**, where I combine:
- Multi-agent reasoning  
- RAG pipelines  
- Vector search (FAISS, Chroma)  
- High-performance FastAPI microservices  
- DuckDB + Parquet Lakehouses  
- AWS cloud infrastructure  
- DevOps automation (CI/CD, Docker, Jenkins)

I have operational experience delivering **production-grade enterprise AI solutions** for global clients across USA, Singapore & India.

---

## 🚀 Technical Expertise Summary

**Core Skills**
- Python (FastAPI, Django, Flask)
- Data Engineering (DuckDB, Parquet, ETL)
- Agentic AI (LangChain, LangGraph, Multi-Agent)
- RAG Systems (Embeddings, FAISS, Chroma, Hybrid Search)
- LLM Orchestration (OpenAI, Gemini, Ollama)
- Backend Microservices (REST APIs, Async, SQLModel)
- DevOps (Docker, Jenkins, CI/CD Pipelines, GitHub Actions)
- Cloud (AWS EC2, Lambda, S3, VPC, ECS, IAM)
- Databases (MySQL, PostgreSQL, MongoDB, Redis, DynamoDB)
- Automation (SDK-driven scripts, network automation, workflow engines)

**Strength Areas**
- End-to-end system architecture  
- Multi-layer enterprise automation  
- High scalability backend design  
- Secure & confidential LLM deployment  
- Observability + structured logging  
- Performance optimization  


<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,aws,docker,jenkins,redis,mongodb,postgres,mysql,linux,git,github,sqlite"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=cloudflare,bash,nginx,terraform,kubernetes,ansible,powershell" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LangGraph-5C2D91?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FAISS-0052CC?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DuckDB-FFF200?style=for-the-badge&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000" />
  <img src="https://img.shields.io/badge/Ollama-fff?logo=ollama&logoColor=000" />
  <img src="https://img.shields.io/badge/Google%20Gemini-886FBF?logo=googlegemini&logoColor=fff" />
  <img src="https://img.shields.io/badge/OpenAPI-6BA539?logo=openapiinitiative&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1c3c3c.svg?logo=langchain&logoColor=white" />
  <img src="https://custom-icon-badges.demolab.com/badge/Cursor-000000?logo=cursor-ai-white" />
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">


## 🔥 Featured GitHub Projects

### 🧠 Multi-Agent Analytics Gateway (MAAG)
**Tech:** FastAPI, LangChain, LangGraph, FAISS, DuckDB, Parquet, OpenAI, Ollama  
**Repo:** *[(Github/SourabhGupta/MAAG)](https://github.com/SourabhGuptaGit/Multi-Agent-Analytics-Gateway)*

- Built a **multi-agent NL2SQL system** turning natural language queries into validated SQL  
- Designed a **Lakehouse architecture** using Parquet + DuckDB capable of scaling beyond **100GB**  
- Embedded schema & table metadata into **FAISS vectors** for instant lookup  
- Created a **safety engine** to verify & optimize SQL queries  
- Delivered API responses with **p95 < 250ms** latency  

**Workflow**

### 🧠 MAAG – Multi-Agent NL2SQL Workflow Diagram

Below is the end-to-end reasoning flow of the **multi-agent NL2SQL pipeline**, visualized using Mermaid.

```mermaid
flowchart TD

    A[User Query] --> B[Intent Classifier Agent]
    B --> C{Query Type?}

    C -->|Analytical Query| D[Schema Retriever Agent]
    C -->|Operational Query| E[Metadata Lookup Agent]

    D --> F[FAISS Vector Search]
    F --> G[Top-K Schema Chunks]

    E --> H[Operational Metadata]

    G --> I[NL2SQL Generator Agent]
    H --> I

    I --> J[SQL Validator Agent]
    J --> K{Valid SQL?}

    K -->|No| L[Correction Agent]
    L --> I

    K -->|Yes| M[DuckDB Executor]

    M --> N[Summarizer Agent]
    N --> O[Final Analytics Response]

    O --> P[FastAPI API Layer Response]
```


---

### ⚙️ Network Automation & Agentic Reasoning Platform
**Tech:** FastAPI, LangChain, LangGraph, Redis, PostgreSQL, Docker, Jenkins, Ollama  
<p>
<b>Repo:</b> <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3gxOTJtMHh2ZGF2MWExejE4N2VyNmt0OHZ4NThzeWp3eDgzNmE2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/hhbsgAvBkZqkKx2ys7/giphy.gif" width="100" height="30">
</p>

- Converted multi-vendor network CLI workflows into a **secure backend API platform**  
- Implemented **agentic LLM-based reasoning** to:  
  - Extract routing insights  
  - Detect config deltas  
  - Generate compliance summaries  
- Ingested live device metadata + logs into Redis & PostgreSQL  
- Used **on-prem LLM inference via Ollama** for confidential data  
- Deployed fully on AWS with containerized microservices  

---

### 📊 Engineering Analytics & Developer Productivity Suite
**Tech:** Django, MySQL, SQLAlchemy, LangChain, RAG, Docker  
<p>
<b>Repo:</b> <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3gxOTJtMHh2ZGF2MWExejE4N2VyNmt0OHZ4NThzeWp3eDgzNmE2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/hhbsgAvBkZqkKx2ys7/giphy.gif" width="100" height="30">
</p>

- Aggregated Jira, Bitbucket & Jenkins events  
- Built dashboards for real-time developer insights  
- Implemented RAG for PR summarization & CI/CD failure detection  
- Added automated daily email updates with AI-generated summaries  
- Containerized the system with Docker  

---

### 🛠 Python API + Data Automation Toolkit
**Tech:** Python, Pandas, SMTP, FastAPI, Redis, Jenkins
<p>
<b>Repo:</b> <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3gxOTJtMHh2ZGF2MWExejE4N2VyNmt0OHZ4NThzeWp3eDgzNmE2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/hhbsgAvBkZqkKx2ys7/giphy.gif" width="100" height="30">
</p>
- Automated Excel & CSV generation pipelines  
- Integrated multiple REST APIs for enterprise reporting  
- Added email automation with templated summaries  
- Replaced up to **70–80%** of manual operational processes  

---

## 🏢 End-to-End Enterprise Projects Delivered

### 🇸🇬 Prudential (Singapore) — Agentic Network Automation Platform  
- Multi-agent LLM abstraction over complex network operations  
- Config interpretation, routing insights & compliance analysis  
- Secure on-prem LLM execution using **Ollama**  
- Metadata ingestion from SDKs & multi-vendor devices  

---

### 🇺🇸 General Motors (USA) — Engineering Analytics & Dev Productivity  
- CI/CD failures summarization using LLMs  
- PR-level insights & engineering metrics  
- Automated dashboards using Django  
- Daily email alerts with AI summaries  

---

### 🇺🇸 WhyGrene – MAAG: Multi-Agent Analytics Gateway  
- Fully automated analytics system  
- NL → SQL agentic reasoning  
- FAISS + DuckDB lakehouse  
- Multi-LLM execution pipeline  

---

### 🇮🇳 People Tech – Automation Systems  
- SCA violation analysis  
- CI diagnostics automation  
- Daily test execution & AI-based classification  

---

### 🇮🇳 PureSoftware — Backend AI & DevOps  
- FastAPI microservices with structured logging  
- Jenkins CI/CD pipelines  
- Secure LLM integration  
- Network intelligence platform  

---

## 📈 Weekly Activity
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SourabhGuptaGit&theme=tokyo-night" />
</p>

---

## 🔮 What I'm Learning Now

- Multi-agent orchestration patterns  
- Advanced RAG (hybrid search, hierarchical routing)  
- High-throughput FastAPI microservices  
- AWS Lambda-based automation workflows  
- Distributed system design  

---

## 📨 Connect With Me
<img src="https://github.com/user-attachments/assets/fddcdbcd-5ea2-4416-9f59-ca7fd9394aca" width="300">
<p align="center">
  <a href="https://www.linkedin.com/in/sourabh-gupta-239949210"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:sourabhgupta.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/SourabhGuptaGit"><img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## ⭐ Final Notes
This README represents my journey building **AI-powered automation**, **multi-agent systems**, and **enterprise-grade backend platforms**.  
I continuously improve my craft by designing systems that are:
- ✔ Reliable
- ✔ Scalable
- ✔ Multi-agent aware
- ✔ Cloud native
- ✔ Secure
- ✔ Observable
- ✔ Built with clean engineering discipline


If you want to discuss systems, automation, agentic workflows, or backend engineering — feel free to reach out!
