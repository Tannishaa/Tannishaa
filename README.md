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

I'm a **BCA graduate (Class of 2026)** and an **AWS Certified Cloud Practitioner** with a strong focus on designing and deploying serverless, event-driven architectures. I thrive on building production-grade systems from the ground up, having independently engineered solutions like a high-concurrency ticketing backend and a fully serverless, Terraform-provisioned audit pipeline.

My engineering philosophy is **build-first**: I ship functional, resilient systems, and then dive deep into the underlying theory. I am fascinated by the complex challenges of distributed systems—managing race conditions, ensuring idempotency, maintaining fault tolerance, and solving what *actually* happens when 1,000 users click "buy" at the exact same time.

- 🏗️ **Currently:** Deepening my Python and SQL expertise (because strategic indexing is incredibly underrated).
- ✅ **Availability:** Graduated and ready to join **immediately**.
- 📍 **Location:** Alwar, Rajasthan | Open to relocation.

---

## Projects

### 🧾 Bill-E — Serverless Audit Pipeline
> `AWS Lambda` · `SQS` · `S3` · `DynamoDB` · `Terraform` · `Python` · `Next.js`

**The Problem:** Manual bill auditing is slow, resource-heavy, and highly vulnerable to fraud.

**The Solution:** I architected a zero-idle-cost, event-driven ingestion pipeline (`S3 → SQS → Lambda`) provisioned entirely via Terraform. An OCR-based heuristic risk-scoring engine parses unstructured receipt data, tracks pipeline state in DynamoDB, and surfaces real-time results on a Next.js dashboard. Automated SNS alerts trigger for high-risk events, drastically reducing the need for manual review.

- **Elastic Scalability:** Achieved zero dedicated server costs utilizing a fully serverless architecture.
- **Fault Tolerance:** Implemented robust Lambda retry logic to safely handle external API rate limits.
- **Infrastructure as Code:** Managed end-to-end infrastructure deployment using Terraform.

🔗 [**Live Demo**](https://bill-e-audit.vercel.app/) · [**Source Code**](https://github.com/Tannishaa/bill-e-audit)

---

### 🎟️ Flux-Order — High-Concurrency Ticketing Engine
> `Python` · `Redis` · `AWS SQS` · `DynamoDB` · `Next.js`

**The Problem:** Flash sales frequently cause double-bookings when hundreds of users request the same inventory simultaneously.

**The Solution:** I built a decoupled, asynchronous ticketing backend that isolates the Next.js frontend from Python processing workers via AWS SQS. By leveraging Redis Distributed Locks (Mutex), I eliminated race conditions during concurrent transactions, achieving **100% transactional consistency** under heavy load. An idempotent SQS consumer with DynamoDB deduplication ensures exact-once order processing, even across retry cycles.

- **High Availability:** Absorbs massive flash-sale traffic spikes using a queue-driven, async architecture.
- **Concurrency Control:** Verified zero double-bookings under intense load testing using Redis Mutex.
- **Data Integrity:** Guaranteed exactly-once delivery via strict idempotency keys.

🔗 [**Live Demo**](https://flux-cinema-frontend.vercel.app/) · [**Source Code**](https://github.com/Tannishaa/flux-order)

---

### 🛡️ Sentinel — AI-Driven Network Intrusion Detection (NIDS)
> `Python` · `FastAPI` · `Scapy` · `Machine Learning`

**The Problem:** Effective real-time network threat detection requires robust, high-throughput packet analysis.

**The Solution:** Developed a real-time NIDS backend utilizing Scapy to capture and analyze high-throughput network packets, successfully flagging anomalous traffic patterns for downstream ML classification models. Exposed live threat metrics through a low-latency FastAPI REST interface to feed a centralized security monitoring dashboard.

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
| 🤖 Introduction to Generative AI - Microlearning Course | Google Cloud | 2026 |

---

## Education

**Bachelor of Computer Applications (BCA)** — CGPA: 8.15/10.0  
Banasthali Vidyapith, Rajasthan · *Class of 2026*

---

## Leadership

**Workshop Lead, Core Organizing Team** — Mayukh Tech Fest, Banasthali Vidyapith *(Jan 2025 – Mar 2026)*

Led end-to-end logistics, scheduling, and resource allocation for technical workshops across two annual tech fests, serving over 500 attendees per edition. Managed a dedicated sub-team of volunteers while coordinating directly with speakers and vendors to ensure seamless execution.

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

📬 **Open to Cloud, Backend, and DevOps engineering roles — available immediately.**

[**LinkedIn**](https://www.linkedin.com/in/tanishas-profile/) · [**Portfolio**](https://tanisha-cloud-portfolio.vercel.app/) · [**Email**](mailto:Tanisha17016@gmail.com)

<br/>

*When I'm not building serverless pipelines, I'm watching F1 or discovering new music.*

</div>
