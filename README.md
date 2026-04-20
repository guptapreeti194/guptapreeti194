<div align="center">

<!-- HEADER -->
<img src="assets/me.gif" width="120" alt="Hi there 👋?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Preeti%20Gupta&fontSize=52&fontColor=58a6ff&fontAlignY=38&desc=Software%20Engineer%20%7C%20Systems%20%26%20Full%20Stack&descColor=8b949e&descAlignY=58&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+databases+from+scratch+%F0%9F%97%84%EF%B8%8F;Full+Stack+%7C+Systems+%7C+ML+Engineering;B-Trees+%2C+MVCC+%2C+WAL+%E2%80%94+done+by+hand;KIIT+CSE+%E2%80%A2+CGPA+8.26+%E2%80%A2+Bhubaneswar)](https://github.com/guptapreeti194)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/preeti-gupta-7a5317301/)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/guptapreeti194)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:preeti.gt2004@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS_ML_Certified-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](#)

</div>

---

## 🧠 About Me

> *I don't just use databases — I build them.*

I'm a **3rd-year CSE undergrad at KIIT Bhubaneswar** obsessed with how systems work at their core. I've built a custom database engine with B-Tree indexing, MVCC, and Write-Ahead Logging from scratch — the kind of project that leads FAANG interviews. Alongside systems work, I ship full-stack products with real ML pipelines (99.78% ROC-AUC fraud detection) and have contributed to open source at scale.

- 🔬 **Systems depth:** Custom DB engine, buffer pool management, OS-level concurrency
- 🚀 **Full stack breadth:** MERN, FastAPI, React dashboards, REST APIs in production
- 🤖 **ML engineering:** XGBoost pipelines, LLM integration (LLaMA via Ollama), NLP
- 📦 **DevOps aware:** Docker, CI/CD, AWS (S3, EC2), Kubernetes basics

---

## 🏗️ Featured Projects

### 🗄️ [ChronoDB — Custom Temporal Database Engine](https://github.com/guptapreeti194)
> *"What was in the DB at 3AM?" — I built the answer.*

A **production-grade database engine built from scratch** that solves the hardest problem in production debugging: time-travel queries.

```sql
-- Time-travel query: retrieve past DB state at any timestamp
SELECT * FROM orders AS OF TIMESTAMP '2025-01-15 03:00:00';
```

| Component | Implementation |
|-----------|---------------|
| **Storage Engine** | B-Tree indexing, page-aligned binary storage (Python/C) |
| **Crash Recovery** | Write-Ahead Logging (WAL) with OS-level `fsync` |
| **Concurrency** | MVCC — readers never block writers, version chains |
| **Memory Mgmt** | Buffer pool with LRU page eviction |
| **Process Scheduling** | Query workers via `multiprocessing` with priority queues |
| **Query Interface** | Custom SQL-like parser: `SELECT`, `INSERT`, `UPDATE`, `AS OF` |

**OS Concepts Demonstrated:** Memory management · File I/O · Process scheduling · Concurrency control

`Python` `C` `B-Trees` `WAL` `MVCC` `OS Internals` `Multiprocessing`

---

### 🛡️ [Online Payment Fraud Detection System](https://github.com/guptapreeti194)
> Full-stack ML system with **99.78% ROC-AUC** on 500K transactions

- 🧬 **ML Pipeline:** XGBoost + SMOTE oversampling on PaySim dataset; 26 engineered features
- ⚡ **Backend:** FastAPI service with RESTful APIs, request validation, production error handling
- 📊 **Frontend:** React dashboard with real-time fraud predictions and interactive charts
- 🗃️ **Database:** MongoDB schema design → Atlas migration with query optimization

`Python` `XGBoost` `scikit-learn` `FastAPI` `React.js` `MongoDB` `Postman`

---

### 🤖 [ClauseEase-AI — Offline Document Intelligence](https://github.com/guptapreeti194)
> Privacy-first AI that runs **entirely on your machine** — no cloud, no data leaks

- 🦙 Locally hosted **LLaMA 2 via Ollama** for Q&A, summarization & multi-language translation
- 📄 Supports PDF, DOCX, TXT — intelligent chunking + real-time chat interface
- 🔒 Zero network calls — built for sensitive legal/enterprise document workflows

`Python` `Streamlit` `Ollama` `LLaMA 2` `LangChain` `PyPDF2` `NLP`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GoLang](https://img.shields.io/badge/Go_(Foundation)-00ADD8?style=flat-square&logo=go&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(Basics)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</div>

---

## 📜 Certifications

| Certification | Issuer | Year |
|--------------|--------|------|
| 🏅 AWS Academy Graduate – ML Foundations | Amazon Web Services | 2026 |
| 🤖 Artificial Intelligence Training | Infosys Springboard | 2025 |
| 🌐 Full Stack Web Development Bootcamp | Udemy | 2025 |
| 📊 Data Structures & Algorithms | GeeksforGeeks | 2025 |

---

## 💼 Experience & Programs

**🏢 EY GDS × AICTE — Software Developer Intern** *(Dec 2024 – Feb 2025)*
- Built custom MERN e-commerce platform with user auth, cart, and order processing
- Designed responsive frontend and secure backend from scratch

**☁️ Amazon ML Summer School — Selected Participant** *(Jul – Aug 2025)*
- Industry-led sessions on system design, scalability, and real-world architecture
- Direct engagement with Amazon engineers on production-grade decision making

**🤖 Infosys Springboard — AI Training Program** *(Oct – Dec 2025)*
- Built production-grade Python modules with focus on testing, documentation, code quality
- Completed structured training in SDLC best practices and modular software design

**🌍 GirlScript Summer of Code (GSSoC) — Open Source Contributor** *(May – Aug 2025)*
- Merged features and bug fixes across multiple repos via Git workflows and code reviews

---

## 🏆 Achievements & Leadership

- 🏅 **Amazon HackOn 2025** — Advanced round with AI Trust & Safety Platform
- 🌐 **IEEE Volunteer Webmaster** @ KIIT Branch (2026–27) — responsive UI, event publishing
- 🎯 **Campus Ambassador @ GSSoC 2025** — mentored students on Git & open-source contribution
- 🌍 **Global AI Hackathons** — consistent participant solving real-world AI challenges

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=guptapreeti194&theme=github-dark-blue&hide_border=true&border_radius=8" height="180"/>
  <br/><br/>
  <img src="https://github-readme-stats.vercel.app/api?username=guptapreeti194&show_icons=true&theme=github_dark&hide_border=true&border_radius=8&include_all_commits=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=guptapreeti194&layout=compact&theme=github_dark&hide_border=true&border_radius=8&langs_count=6" height="160"/>
</div>

---

## 🎓 Education

**B.Tech in Computer Science** — KIIT Bhubaneswar *(2023 – 2027)*
CGPA: **8.26 / 10.0**
Coursework: OS · DBMS · Data Structures · Algorithms · AI · ML · Networking

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer&animation=fadeIn" width="100%"/>

*"I read the source code of databases so you don't have to — then I build one anyway."*

**Open to SDE internships & full-time roles | Available from April 2026**

</div>
