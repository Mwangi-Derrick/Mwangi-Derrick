<div align="center">
  
# 👋 Derrick Mwangi

### Full-Stack Engineer | Distributed Systems | Cloud Architecture

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/derrick-mwangi-bab062276/)
[![Email](https://img.shields.io/badge/Email-mwangiderrick334%40gmail.com-red?style=flat&logo=gmail)](mailto:mwangiderrick334@gmail.com)
[![GitHub](https://img.shields.io/github/followers/Mwangi-Derrick?label=Follow&style=social)](https://github.com/Mwangi-Derrick)

</div>

---

## 🚀 About Me

Software Engineer specializing in **production-grade distributed systems**, **event-driven architectures**, and **IoT infrastructure**. I build scalable platforms that solve real-world problems—from AI-powered education tools serving students across Africa to industrial-grade data reliability systems.

- 🎓 **EEE Student** at JKUAT, Kenya
- 💼 **Open to opportunities** in backend, cloud, distributed systems, and IoT roles
- 🏗️ Building systems that combine **microservices**, **message queues**, **Kubernetes**, and **edge computing**
- 🌍 Passionate about leveraging technology to solve infrastructure challenges in emerging markets

---

## 💻 Technical Skills

### Languages
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

### Frontend & UI
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![shadcn/ui](https://img.shields.io/badge/-shadcn%2Fui-000000?style=flat&logo=vercel&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### Backend & APIs
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=flat&logo=rust&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=grpc&logoColor=white)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/-MinIO-C72E49?style=flat&logo=minio&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![GCP](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Caddy](https://img.shields.io/badge/-Caddy-00ADD8?style=flat&logo=caddy&logoColor=white)

### Message Brokers & IoT
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![EMQX](https://img.shields.io/badge/-EMQX-3478F6?style=flat&logo=eclipse-mosquitto&logoColor=white)
![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat&logo=mqtt&logoColor=white)
![Temporal](https://img.shields.io/badge/-Temporal-2CCCE4?style=flat&logo=temporal&logoColor=white)

---

## 🏆 Featured Projects

### 🔐 Resplix - Industrial Data Reliability Infrastructure

<div align="center">
  
[![Live Site](https://img.shields.io/badge/🌐_Live-resplix.com-4285F4?style=for-the-badge)](https://resplix.com)
[![In Development](https://img.shields.io/badge/Status-Active_Development-green?style=for-the-badge)]()

</div>

**The unyielding nucleus for global data transit** — A zero-knowledge, customer-owned infrastructure platform for industrial-grade backup and data movement.

#### 🎯 Core Innovation

Resplix reimagines data reliability by putting customers in control of their infrastructure while providing enterprise-grade orchestration:

- 🏗️ **Customer-Owned Architecture**: Customers maintain their own S3/GCS buckets and encryption keys — zero vendor lock-in
- 🦀 **Rust-Powered Performance**: High-performance async streaming with <1.2% CPU overhead and 14MB memory footprint
- 🔐 **Zero-Knowledge Security**: End-to-end encryption with keys never leaving customer infrastructure
- ⚡ **Content-Addressable Storage**: Deduplication via BLAKE3 hashing and Gear Hash chunking for 90%+ efficiency
- 🌍 **Polyglot Service Mesh**: Microservices in Rust, Go, and TypeScript communicating via gRPC and message queues

#### 🛠️ Technical Architecture

```
┌──────────────────────────────────────────────────┐
│      Web Console (Next.js + shadcn/ui)          │
└────────────────────┬─────────────────────────────┘
                     │ REST/gRPC
┌────────────────────▼─────────────────────────────┐
│     API Gateway (Kong/Caddy + Auth Layer)        │
└────────────────────┬─────────────────────────────┘
                     │
        ┌────────────┼────────────┐
        │            │            │
┌───────▼──────┐ ┌──▼─────┐ ┌───▼────────┐
│ Orchestration│ │Identity│ │  Storage   │
│Service (Rust)│ │& Auth  │ │ Connector  │
└───────┬──────┘ └────────┘ └────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│    Event-Driven Bus (EMQX/RabbitMQ/Temporal)     │
└───────┬──────────────────────────────────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│  Backup Agents (Rust) in Customer VPCs           │
│  • BLAKE3 Hashing • Zstd Compression             │
│  • AES-256-GCM Encryption • Atomic Resumability  │
└───────┬──────────────────────────────────────────┘
        │
┌───────▼──────────────────────────────────────────┐
│   Customer's Cloud (S3/GCS/Azure/MinIO)          │
│   (Encrypted chunks stored in customer bucket)   │
└──────────────────────────────────────────────────┘
```

#### 💡 Key Features

- **Zero-Knowledge Encryption**: AES-256-GCM encryption with customer-held keys
- **Atomic Resumability**: Failed transfers resume from exact byte position via content-defined chunking
- **95%+ Gross Margins**: Customer-owned storage model eliminates infrastructure costs
- **Multi-Cloud Support**: S3, GCS, Azure Blob, MinIO, DigitalOcean Spaces
- **SIMD-Accelerated Hashing**: 10GB/s+ per core with BLAKE3
- **Real-Time Telemetry**: Live backup status via WebSocket streams
- **CLI-First Design**: Production-grade CLI tool for developers (`pit` command)

#### 📊 Business Model Innovation

```
Traditional Backup SaaS:
Revenue: $500/mo → COGS: $320/mo (storage+bandwidth) → Margin: 36%

Resplix Model:
Revenue: $500/mo → COGS: $25/mo (compute only) → Margin: 95% 🚀
```

By letting customers own their storage buckets, Resplix achieves infinite scalability with near-zero marginal costs.

#### 🔬 Technical Deep Dives

The platform is built on three pillars:

1. **Content-Addressable Storage (CAS)**: Immutable chunks identified by cryptographic hashes
2. **Probabilistic Indexing**: Bloom filters for zero-latency duplicate detection
3. **Durable Orchestration**: Temporal workflows for fault-tolerant task coordination

*Read more*: [The Engineering Rosetta Stone](https://resplix.com/docs/rosetta-stone)

---

### 💡 Smart Street Lighting System - IoT Infrastructure

<div align="center">

[![In Development](https://img.shields.io/badge/Status-Active_Development-green?style=for-the-badge)]()

</div>

**Industrial IoT platform for remote street light management** with OTA updates and real-time telemetry.

#### 🎯 System Overview

A comprehensive end-to-end solution combining embedded firmware, cloud backend, and real-time monitoring for municipal infrastructure.

#### 🛠️ Architecture

```
┌──────────────────────────────────────────────────┐
│  Street Light Nodes (Embedded C/ESP32)           │
│  • Voltage/Current Monitoring • Remote Control   │
│  • OTA Firmware Update Support • MQTT Client     │
└────────────────────┬─────────────────────────────┘
                     │ MQTT over cellular/WiFi
┌────────────────────▼─────────────────────────────┐
│         EMQX MQTT Broker (Containerized)         │
│     • Topic-based routing • ACL management       │
└────────────────────┬─────────────────────────────┘
                     │
┌────────────────────▼─────────────────────────────┐
│       Backend API (Go + Gin Framework)           │
│  • Device Management • Telemetry Aggregation     │
│  • SIM Card Monitoring • OTA Update Distribution │
└────────────────────┬─────────────────────────────┘
                     │
        ┌────────────┼────────────┐
        │            │            │
┌───────▼──────┐ ┌──▼─────┐ ┌───▼────────┐
│   MongoDB    │ │MongoDB │ │   MinIO    │
│  (Metadata)  │ │(Metrics)│ │ (Firmware) │
└──────────────┘ └────────┘ └────────────┘
```

#### 💡 Key Features

**Device Management**:
- Remote on/off control via MQTT commands
- Real-time status monitoring (online/offline)
- Bulk operations for street segments

**Telemetry & Analytics**:
- Time-series storage for voltage, current, power consumption
- Anomaly detection for electrical faults
- Historical data visualization

**OTA Firmware Updates**:
- Binary firmware storage in MinIO (S3-compatible)
- Secure firmware distribution via MQTT
- Rollback support for failed updates
- Version control and staged rollouts

**SIM Management**:
- Data usage tracking per device
- Automated top-up integration
- Cost monitoring and alerting

#### 🔧 Tech Stack

| Component | Technology |
|-----------|-----------|
| **Backend** | Go (Gin), MongoDB, MinIO |
| **Messaging** | EMQX (MQTT Broker) |
| **Embedded** | C/C++ (ESP32/STM32) |
| **Infrastructure** | Docker Compose |
| **Protocols** | MQTT, REST API |

#### 📦 Quick Start



#### 🚀 Future Roadmap

- [ ] Solar panel integration for off-grid deployment
- [ ] OTA updates for firmware binaries
- [ ] ML-based predictive maintenance
- [ ] Mobile app for field technicians
- [ ] Integration with GIS mapping systems
- [ ] Multi-tenant architecture for multiple municipalities

---

### 🎓 Summafy.io - AI Study Platform

[![Live Demo](https://img.shields.io/badge/🌐_Live-summafy.io-4285F4?style=for-the-badge)](https://summafy.io)

An AI-powered study platform serving students across Africa with intelligent document summarization, quiz generation, and learning tools.

**Tech Highlights**:
- 5+ production microservices (Rust, TypeScript, Python, Go)
- Event-driven architecture with RabbitMQ and Celery
- Durable workflow management with Temporal
- AI processing pipeline with document OCR and summarization
- Payment integration with African providers (M-Pesa, Lemon-squeezy)
- Real-time content streaming to frontend clients

---

## 📈 GitHub Stats

<div align="center">
  
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mwangi-Derrick&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/Mwangi-Derrick)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mwangi-Derrick&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)](https://github.com/Mwangi-Derrick)

</div>

---

## 🎯 Current Focus

- 🚀 **Scaling Resplix**: Building customer onboarding flows and multi-cloud storage connectors
- 🛟 **Migrating Summafy.io**: Migrating Summafy.io Ai document processing from python celery to rust and temporal
- 🦀 **Rust Mastery**: Deep-diving into async/await, SIMD optimizations, and zero-copy networking
- 🏗️ **Kubernetes Migration**: Moving from Docker Compose to GKE for production deployment
- 💡 **IoT Expansion**: Adding solar integration and predictive maintenance to street lighting system
- 📚 **Building in Public**: Documenting distributed systems patterns and architectural decisions

---

## 💼 What I'm Looking For

I'm actively seeking **full-time opportunities** where I can:

- Build scalable backend systems and microservices architectures
- Work on distributed systems, cloud infrastructure, and data-intensive applications
- Contribute to IoT platforms and edge computing solutions
- Solve real-world problems in emerging markets
- Learn from experienced engineers and grow my craft

**Open to**: Backend Engineer, Full-Stack Engineer, Cloud Engineer, Distributed Systems Engineer, IoT Engineer

---

## 📫 Get In Touch

- 📧 Email: [mwangiderrick334@gmail.com](mailto:mwangiderrick334@gmail.com)
- 💼 LinkedIn: [Derrick Mwangi](https://www.linkedin.com/in/derrick-mwangi-bab062276/)
- 🌐 Projects: [resplix.com](https://resplix.com) • [summafy.io](https://summafy.io)
- 💬 Open to collaboration on **distributed systems**, **IoT platforms**, and **infrastructure tools**

---

<div align="center">

### ⚡ "Building resilient systems that scale — from bits to infrastructure"

*Crafting the future of data reliability and intelligent infrastructure, one commit at a time.*

</div>
