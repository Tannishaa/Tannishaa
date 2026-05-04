<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=100&color=A855F7&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Tanisha+%F0%9F%91%8B;BCA+Graduate+%7C+Class+of+2026;AWS+Certified+Cloud+Practitioner;Serverless+%7C+Event-Driven+%7C+Distributed+Systems;Available+Immediately" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="https://www.linkedin.com/in/tanishas-profile/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://tanisha-cloud-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white"/></a>&nbsp;
  <a href="mailto:Tanisha17016@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</div>

<br/>

I'm a **BCA graduate (Class of 2026)** and **AWS Certified Cloud Practitioner** with hands-on experience designing and deploying serverless, event-driven systems on AWS. I've independently built three production-grade cloud applications — including a high-concurrency ticketing engine and a fully serverless audit pipeline provisioned with Terraform.

My engineering philosophy is **build-first**: I ship functional systems, then go deep on the theory. I'm drawn to the hard problems in distributed systems — race conditions, idempotency, fault tolerance, and what actually happens when 1,000 users click "buy" at the same time.

- 🏗️ **Currently:** Sharpening Python and SQL fundamentals (indexes are genuinely underrated)
- ✅ **Availability:** Graduated and ready to join **immediately**
- 📍 **Location:** Alwar, Rajasthan | Open to relocation

---

## Projects

### 🧾 Bill-E — Serverless Audit Pipeline
> `AWS Lambda` · `SQS` · `S3` · `DynamoDB` · `Terraform` · `Python` · `Next.js`

**The problem:** Manual bill auditing is slow, expensive, and fraud-prone.

**What I built:** A zero-idle-cost, event-driven ingestion pipeline (`S3 → SQS → Lambda`) provisioned entirely with Terraform. An OCR heuristic risk-scoring engine parses unstructured receipt data, tracks pipeline state in DynamoDB, and surfaces results on a real-time Next.js dashboard. Automated SNS alerts fire for any event scoring above threshold, reducing manual review overhead significantly.

- Elastic scalability with zero dedicated server costs via serverless architecture
- Fault-tolerant Lambda retry logic for external API rate limits
- End-to-end infrastructure as code with Terraform

🔗 [**Live Demo**](https://bill-e-audit.vercel.app/) · [**Source Code**](https://github.com/Tannishaa/bill-e-audit)

---

### 🎟️ Flux-Order — High-Concurrency Ticketing Engine
> `Python` · `Redis` · `AWS SQS` · `DynamoDB` · `Next.js`

**The problem:** Flash-sale double-bookings when hundreds of users hit the same inventory simultaneously.

**What I built:** A decoupled, asynchronous ticketing backend that separates the Next.js frontend from Python processing workers via SQS. Redis Distributed Locks (Mutex) eliminate race conditions during concurrent transactions, achieving **100% transactional consistency** under load. An idempotent SQS consumer with DynamoDB deduplication guarantees exactly-once order processing across retry cycles.

- Absorbs flash-sale traffic spikes with async, queue-driven architecture
- Zero double-bookings via Redis Mutex — verified under concurrent load tests
- Exactly-once delivery guarantee via idempotency keys

🔗 [**Live Demo**](https://flux-cinema-frontend.vercel.app/) · [**Source Code**](https://github.com/Tannishaa/flux-order)

---

### 🛡️ Sentinel — AI-Driven Network Intrusion Detection (NIDS)
> `Python` · `FastAPI` · `Scapy` · `Machine Learning`

**The problem:** Real-time network threat detection requires high-throughput packet analysis.

**What I built:** A real-time NIDS backend using Scapy to capture and analyze high-throughput network packets, flagging anomalous traffic patterns for downstream ML classification models. A low-latency FastAPI REST interface exposes live threat metrics and alerts to a centralized security dashboard for continuous monitoring.

🔗 [**Source Code**](https://github.com/Tannishaa)

---

## Tech Stack

| **Cloud (AWS)** | **Backend** | **Infrastructure** | **Tools** |
| :--- | :--- | :--- | :--- |
| ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| ![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazon-sqs&logoColor=white) | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white) | ![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white) | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |
| ![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white) | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) | | ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white) |

**Core Competencies:** Event-Driven Architecture · Serverless Computing · REST API Design · Concurrency Control · Distributed Systems · Infrastructure as Code

---

## Certifications

| Certification | Issuer | Year |
| :--- | :--- | :--- |
| ☁️ AWS Certified Cloud Practitioner (CLF-C02) | Amazon Web Services | 2025 |
| 🤖 Introduction to Generative AI- Microlearning Course | Google Cloud | 2026 |

---

## Education

**Bachelor of Computer Applications (BCA)** — CGPA: 8.15/10.0
Banasthali Vidyapith, Rajasthan · *May 2026*

---

## Leadership

**Workshop Lead, Core Organizing Team** — Mayukh Tech Fest, Banasthali Vidyapith *(Jan 2025 – Mar 2026)*

Directed end-to-end logistics, scheduling, and resource allocation for technical workshops across two annual cycles serving 500+ attendees per edition. Managed a sub-team of volunteers and coordinated speaker and vendor relations.

---

## GitHub Insights

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tannishaa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tannishaa&theme=tokyonight&hide_border=true&background=0D1117" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tannishaa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" width="48%" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Tannishaa&theme=tokyonight" width="48%" />
</div>

---

<div align="center">

📬 **Open to cloud, backend, and DevOps engineering roles — available immediately.**

[**LinkedIn**](https://www.linkedin.com/in/tanishas-profile/) · [**Portfolio**](https://tanisha-cloud-portfolio.vercel.app/) · [**Email**](mailto:Tanisha17016@gmail.com)

<br/>

*When I'm not building serverless pipelines, I'm watching F1 or discovering new music.*

</div>
