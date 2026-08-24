<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,45:6d28d9,100:7c3aed&height=210&section=header&text=Shivam%20Kumar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=QA%20%2F%20SDET%20%E2%80%A2%20Full-Stack%20Engineer%20%E2%80%A2%20AI%20%26%20RAG%20Developer&descAlignY=58&descSize=18" alt="Shivam Kumar"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=24&pause=1200&color=A78BFA&center=true&vCenter=true&width=900&lines=Building+reliable+software+and+scalable+systems;Automating+quality+with+Selenium+%2B+API+testing;Building+RAG+systems+with+embeddings+and+vector+search;Full-stack+engineering+with+TypeScript+%2B+React+%2B+Node.js" alt="Typing SVG" />

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-shivam9473-181717?style=for-the-badge&logo=github)](https://github.com/shivam9473)
[![Email](https://img.shields.io/badge/Email-shivamk38812%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivamk38812@gmail.com)
![Location](https://img.shields.io/badge/India-Vaishali%2C%20Bihar-6D28D9?style=for-the-badge)
![Profile Views](https://komarev.com/ghpvc/?username=shivam9473&style=for-the-badge&color=7c3aed)

</div>

---

## About Me

I am **Shivam Kumar**, a Computer Science Engineering student and **QA Intern at Toba Tech Solution** with hands-on experience in manual testing, API testing, regression testing, bug reporting, test-case design, and Selenium-based UI automation.

Alongside QA, I build **full-stack TypeScript applications** and explore **AI-powered software systems** using Retrieval-Augmented Generation (RAG), vector embeddings, semantic search, LangChain/LangGraph concepts, and modern backend infrastructure.

I enjoy working at the intersection of **software quality, backend correctness, product engineering, and AI**.

### Open To

- QA / SDET opportunities
- Software Engineering internships and entry-level roles
- Full-Stack TypeScript projects
- AI / RAG engineering projects
- Open-source collaboration

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,java,js,ts,html,css" alt="Languages"/>
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind" alt="Frontend"/>
</p>

### Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,mysql,redis" alt="Backend and Databases"/>
</p>

### Cloud, DevOps & Tooling

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,vscode" alt="DevOps and Tools"/>
</p>

### Testing & Quality Engineering

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6F00?style=flat-square)
![REST Assured](https://img.shields.io/badge/REST%20Assured-6DB33F?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Allure](https://img.shields.io/badge/Allure-FF5A5F?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

## AI / RAG Expertise

| Domain | Level | What I Work With |
|---|---|---|
| Retrieval-Augmented Generation | Hands-on | Semantic retrieval, context injection, cited answers |
| Vector Embeddings | Hands-on | Embedding pipelines, similarity search, vector stores |
| Vector Databases | Hands-on | Pinecone-based semantic retrieval |
| Code Intelligence | Hands-on | AST-aware chunking, repository indexing, code citations |
| LangChain / LangGraph | Exploring & Building | Agentic workflows, retrieval chains, orchestration |
| MCP | Exploring | Model Context Protocol concepts and integrations |
| AI Application Engineering | Hands-on | Streaming responses, repository Q&A, AI-generated insights |

---

## Featured Projects

<details open>
<summary><b>CodeAtlas AI — Full-Stack RAG Code Intelligence Platform</b></summary>

<br/>

A full-stack AI platform for understanding large GitHub repositories using **RAG, AST-aware parsing, embeddings, semantic search, and cited answers**.

| Area | Implementation |
|---|---|
| Stack | React, TypeScript, Node.js, Express, PostgreSQL, Redis, BullMQ, Pinecone, Docker |
| Retrieval | AST-aware code chunking + vector embeddings + semantic search |
| AI | Streaming RAG Q&A with file/function-level citations |
| Infrastructure | Background indexing workers with BullMQ |
| Auth | GitHub OAuth + JWT |
| Developer Experience | Monorepo architecture + Docker Compose + GitHub Actions |
| Repository | [shivam9473/RepoIQ](https://github.com/shivam9473/RepoIQ) |

**Key engineering work**
- Built a repository indexing pipeline: clone → parse → chunk → embed → store vectors.
- Designed modular services for frontend, backend, workers, parser, embeddings, vector search, and AI.
- Added repository Q&A, architecture insights, code review assistance, duplicate detection, and dependency visualization.
- Implemented semantic retrieval with source-level citations instead of uncited model answers.

</details>

<details>
<summary><b>Fault-Tolerant Payment Ledger</b></summary>

<br/>

A correctness-focused money-transfer system designed to behave safely under **duplicate requests and concurrent transfers**.

| Area | Implementation |
|---|---|
| Stack | Node.js, Fastify, TypeScript, PostgreSQL, React 19, Vite, Docker |
| Reliability | Durable idempotency keys + SHA-256 request fingerprints |
| Concurrency | `SELECT ... FOR UPDATE` row locking |
| Transaction Safety | Atomic debit, credit, transfer audit, and idempotency writes |
| Error Handling | Structured `application/problem+json` responses |
| Repository | [shivam9473/Fault-toleant-payment](https://github.com/shivam9473/Fault-toleant-payment) |

**Key engineering work**
- Prevented duplicate money transfers through durable idempotency handling.
- Used deterministic account-lock ordering to reduce deadlock risk.
- Kept balance updates and audit writes inside one PostgreSQL transaction.
- Built a React-based ledger console for balances, transfers, accounts, and activity.

</details>

<details>
<summary><b>DemoQA & Restful Booker Test Automation Framework</b></summary>

<br/>

A reusable **SDET automation framework** covering UI and API testing with Java.

| Area | Implementation |
|---|---|
| Stack | Java, Selenium, TestNG, Rest Assured, Maven |
| UI Automation | DemoQA forms, dialogs, alerts, dynamic tables |
| API Automation | Restful Booker CRUD + authentication + schema validation |
| Architecture | Multi-module Maven + reusable framework core |
| Scale | Parallel TestNG runs + retry handling |
| Infrastructure | Docker Selenium Grid |
| Reporting | Allure |
| CI/CD | GitHub Actions |
| Repository | [shivam9473/test-DemoQA](https://github.com/shivam9473/test-DemoQA) |

**Key engineering work**
- Created Page Object Model-based Selenium tests.
- Built reusable driver factory, waits, JSON test-data handling, and listeners.
- Automated full REST API lifecycle testing with schema validation.
- Added parallel execution, flaky-test retry support, Docker Grid, and CI workflows.

</details>

<details>
<summary><b>HealthSync — MERN Hospital Management System</b></summary>

<br/>

A hospital-management application focused on patient, doctor, appointment, and administrative workflows.

| Area | Implementation |
|---|---|
| Frontend | React |
| Backend | Node.js + Express |
| Database | MongoDB |
| Auth | JWT |
| Core Features | Authentication, appointments, patient records, doctor-patient communication, admin workflows |
| Repository | [shivam9473/HealthSync](https://github.com/shivam9473/HealthSync) |

</details>

---

## Experience

### QA Intern — Toba Tech Solution
**May 2026 — Present**

- Perform manual testing of web application features for functionality, usability, UI flow, and expected behavior.
- Test REST APIs using request/response validation, status-code checks, payload verification, and negative scenarios.
- Prepare test cases and clear defect reports with reproducible steps.
- Support regression testing after fixes and feature updates.
- Use Jira for bug tracking, status updates, and QA collaboration.
- Explore Selenium WebDriver for end-to-end browser automation.

**Skills:** Manual Testing · API Testing · Regression Testing · Jira · Selenium · Test Case Design · Bug Reporting

---

## Education

**Bachelor of Technology — Computer Science and Engineering**  
Geetanjali Institute of Technical Studies, Udaipur  
**2023 — Present · CGPA: 9.3**

---

## Engineering Strengths

| Area | Focus |
|---|---|
| Quality Engineering | Functional testing, API validation, regression, automation |
| Backend Engineering | Reliable APIs, concurrency safety, transactions, error handling |
| Full-Stack Development | React + TypeScript + Node.js application development |
| AI Engineering | RAG, embeddings, semantic retrieval, vector search |
| Product Engineering | Building systems that are usable, testable, and maintainable |
| DevOps Fundamentals | Docker, GitHub Actions, reproducible local environments |

---

## GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=shivam9473&show_icons=true&theme=midnight-purple&hide_border=true&rank_icon=github" alt="GitHub Stats"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivam9473&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=shivam9473&theme=midnight-purple&hide_border=true" alt="GitHub Streak"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=shivam9473&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=7" alt="GitHub Trophies"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shivam9473&theme=react-dark&hide_border=true&area=true" width="100%" alt="Contribution Graph"/>

</div>

---

## Current Focus

```yaml
learning:
  - Advanced RAG architectures
  - Agentic AI systems
  - LangGraph
  - Production-grade test automation

building:
  - AI-powered developer tools
  - Reliable backend systems
  - Full-stack TypeScript applications
  - Scalable QA automation frameworks

exploring:
  - MCP integrations
  - Hybrid retrieval
  - RAG evaluation
  - AI-assisted software engineering

open_to:
  - QA / SDET roles
  - Software engineering roles
  - AI / RAG projects
  - Open-source collaboration
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-shivamk38812%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivamk38812@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-shivam9473-181717?style=for-the-badge&logo=github)](https://github.com/shivam9473)

</div>

---

<div align="center">

**Build it. Test it. Understand it. Improve it.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,45:6d28d9,100:7c3aed&height=120&section=footer" alt="Footer"/>

</div>
