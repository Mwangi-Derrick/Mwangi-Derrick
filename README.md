<div align="center">
  
# 👋 Derrick Mwangi

### Full-Stack Engineer | Distributed Systems | Cloud Architecture

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/derrick-mwangi-bab062276/)
[![Email](https://img.shields.io/badge/Email-mwangiderrick334%40gmail.com-red?style=flat&logo=gmail)](mailto:mwangiderrick334@gmail.com)
[![GitHub](https://img.shields.io/github/followers/Mwangi-Derrick?label=Follow&style=social)](https://github.com/Mwangi-Derrick)

</div>

---

## 🚀 About Me

Software Engineer with expertise in building **production-grade distributed systems** and **event-driven microservices**. Currently building [**Summafy.io**](https://summafy.io) - an AI-powered study platform serving students across Africa with intelligent document summarization, quiz generation, and learning tools.

- 🎓 **EEE Student** at JKUAT, Kenya
- 💼 **Open to opportunities** in backend, cloud, and distributed systems roles
- 🏗️ Architecting scalable systems with **microservices**, **message queues**, and **Kubernetes**
- 🌍 Passionate about solving real problems in emerging markets through technology

---

## 💻 Technical Skills

### Languages
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

### Frontend & UI
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![shadcn/ui](https://img.shields.io/badge/-shadcn%2Fui-000000?style=flat&logo=vercel&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### Backend & APIs
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)
![Gin](https://img.shields.io/badge/-Gin-000000?style=flat&logo=gin&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-4285F4?style=flat&logo=google&logoColor=white)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![GCP](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Kong](https://img.shields.io/badge/-Kong-003459?style=flat&logo=kong&logoColor=white)
![Caddy](https://img.shields.io/badge/-Caddy-00ADD8?style=flat&logo=caddy&logoColor=white)

### Message Brokers & Event Streaming
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat&logo=celery&logoColor=white)
![Temporal](https://img.shields.io/badge/-Temporal-2CCCE4?style=flat&logo=temporal&logoColor=white)
![EMQX](https://img.shields.io/badge/-EMQX-3478F6?style=flat&logo=emqx&logoColor=white)

---

## 🏆 Featured Project: Summafy.io

<div align="center">
  
### 🎓 AI-Powered Study Platform | Production-Grade Microservices Architecture

[![Live Demo](https://img.shields.io/badge/🌐_Live-summafy.io-4285F4?style=for-the-badge)](https://summafy.io)

</div>

A **full-stack AI study platform** built from scratch, helping students across Africa ace their studies through intelligent document analysis, summarization, flashcards, and quiz generation.

### 🎯 Key Achievements

- 🏗️ **Architected and built 8+ production microservices** across multiple programming languages
- ⚡ **Event-driven architecture** for async processing and reliable inter-service communication
- 🔐 **Production-grade authentication & authorization** with modern identity management patterns
- 💳 **Payment processing integration** with African and international payment providers
- 🤖 **AI processing pipeline** handling document analysis, summarization, and quiz generation at scale
- 🚢 **Cloud-native deployment** using containerization and orchestration platforms
- 🌐 **API Gateway layer** with intelligent routing, rate limiting, and quota management
- 📊 **Real-time data streaming** to frontend clients for live AI content generation
- 🔄 **Polyglot service mesh** with efficient cross-service communication protocols
- 🦀 **Performance-critical optimizations** using compiled languages for CPU-intensive operations

### 🛠️ High-Level Architecture

```
┌──────────────────────────────────────────────────┐
│           Web Frontend (Next.js/React)           │
└────────────────────┬─────────────────────────────┘
                     │ REST/gRPC
┌────────────────────▼─────────────────────────────┐
│          API Gateway & Request Router            │
│        (Authentication, Rate Limiting)           │
└────────────────────┬─────────────────────────────┘
                     │
        ┌────────────┼────────────┐
        │            │            │
┌───────▼──────┐ ┌──▼─────┐ ┌───▼────────┐
│ Microservices│ │Identity│ │  Payment   │
│   Cluster    │ │ & Auth │ │ Processing │
│ (Polyglot)   │ │Service │ │   Service  │
└───────┬──────┘ └────────┘ └────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│      Event-Driven Message Bus & Queue System     │
│        (Async Processing & Communication)        │
└───────┬──────────────────────────────────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│  AI Processing Pipeline & Background Workers     │
│     (Document Analysis, ML Inference, OCR)       │
└───────┬──────────────────────────────────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│   Data Layer: SQL, NoSQL, Cache, Object Store    │
└──────────────────────────────────────────────────┘
```

**Architecture Principles:**
- **Microservices**: Independent services in TypeScript, Python, and Go
- **Event-Driven**: Async communication via message queues for scalability
- **Polyglot Persistence**: Right database for each use case
- **Cloud-Native**: Containerized with Docker, orchestrated with Kubernetes


---

## 📈 GitHub Stats

<div align="center">
  
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mwangi-Derrick&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/Mwangi-Derrick)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mwangi-Derrick&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)](https://github.com/Mwangi-Derrick)

</div>

---

## 🎯 What I'm Working On

- 🚀 **Scaling Summafy.io** for growth across African universities
- 🦀 **Learning Rust** for high-performance systems programming
- 🏗️ **Migrating to Kubernetes** on GKE for production deployment
- 📚 **Building in public** and documenting my distributed systems journey
- 💡 Developing **IoT solutions** for smart infrastructure, including automated and telemetry systems

---

## 💼 Looking For

I'm actively seeking **full-time opportunities** where I can:

- Build scalable backend systems and microservices
- Work on distributed systems and cloud infrastructure
- Contribute to products that solve real-world problems
- Learn from experienced engineers and grow my craft

**Open to**: Backend Engineer, Full-Stack Engineer, Cloud Engineer, Distributed Systems roles

---

## 📫 Get In Touch

- 📧 Email: [mwangiderrick334@gmail.com](mailto:mwangiderrick334@gmail.com)
- 💼 LinkedIn: [Mwangi Derrick](https://www.linkedin.com/in/derrick-mwangi-bab062276/)
- 🌐 Project: [summafy.io](https://summafy.io)
- 🐦 Open to collaboration on **open source** and **web systems**

---

<div align="center">

### ⚡ "Building the future, one microservice at a time"

[![Profile Views](https://komarev.com/ghpvc/?username=Mwangi-Derrick&color=blue&style=flat)](https://github.com/Mwangi-Derrick)

</div>
