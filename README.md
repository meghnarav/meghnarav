<div align="center">
  <h1>Meghna Ravikumar</h1>
  <br/>
  <b>Hello, World!</b><br/>
  <b>I build backend systems where things break under pressure and fix them.</b> 

  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=meghnarav&color=2eb398&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p>

## What I’m Building

### 1. High-Throughput Reservation Engine
**Repo:** [high-throughput-reservation](https://github.com/meghnarav/high-throughput-reservation) | **Stack:** Java 21, Redis, PostgreSQL, k6
* **The Problem:** Solving the "Thundering Herd" and race conditions in high-demand resource allocation (e.g., 10k+ TPS ticketing spikes).
* **Systems Approach:** Moving beyond DB-level locking by implementing a **Virtual Waiting Room** (Redis Sorted Sets) and **Atomic Decrement Orchestration** via Redis Lua scripts.
* **The Flex:** Comparative analysis of **Optimistic vs. Pessimistic vs. Distributed Locking (Redlock)** performance under simulated saturation.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=1&section=header" width="98%" />
</p>

### 2. Event-Sourced Financial Ledger
**Repo:** [event-sourced-ledger](https://github.com/meghnarav/event-sourced-ledger) | **Stack:** Java 21, PostgreSQL, Python (ML)
* **The Problem:** Ensuring 100% data integrity and auditability in high-stakes transaction environments where standard CRUD updates are insufficient.
* **Systems Approach:** Implementing a **strictly consistent append-only event store**. System state is treated as a projection of the immutable transaction log, allowing for "time-travel" debugging and state replay.
* **The Flex:** **Idempotency-as-a-First-Class-Citizen** using request hashing and an **AI Audit Sidecar** (Isolation Forest) to flag anomalous transaction patterns in the event stream.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=1&section=header" width="98%" />
</p>

### 3. Inference Token Gateway
**Repo:** [inference-token-gateway](https://github.com/meghnarav/inference-token-gateway) | **Stack:** Golang, gRPC, Redis, Milvus (Vector DB)
* **The Problem:** Managing the cost, latency, and rate-limit complexities of production LLM infrastructure.
* **Systems Approach:** A high-performance Go proxy that implements **Token-based Rate Limiting** (sliding window) and multi-provider request orchestration.
* **The Flex:** **Semantic Caching** using vector similarity search to intercept redundant prompts, reducing LLM API overhead by serving cached high-confidence matches.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p>

## Tech Stack

<div align="center">
  
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=grpc&logoColor=white)

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p>

## My Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=meghnarav&theme=tokyonight" width="75%" />
</div>
  
</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p>

## Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-2eb398?style=for-the-badge&logo=linkedin&logoColor=15141b)](https://www.linkedin.com/in/meghna-ravikumar)
[![GitHub](https://img.shields.io/badge/GitHub-2eb398?style=for-the-badge&logo=github&logoColor=15141b)](https://github.com/meghnarav)
[![Twitter/X](https://img.shields.io/badge/X-2eb398?style=for-the-badge&logo=x&logoColor=15141b)](https://x.com/meghnarav)
[![Discord](https://img.shields.io/badge/Discord-2eb398?style=for-the-badge&logo=discord&logoColor=15141b)](https://discord.com/users/meghna_ravikumar)
[![Email](https://img.shields.io/badge/Email-2eb398?style=for-the-badge&logo=gmail&logoColor=15141b)](mailto:meghnaravikumar06@gmail.com)

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p>

<div align="center">
    <br/>

  > <b>TAKE ACTION. DIVE IN. </b>
  
  <br/>

</div>

<!-- **meghnarav/meghnarav** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:

- ⚡My Skills
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...    

![Meghna's GitHub Stats](https://github-readme-stats.vercel.app/api?username=meghnarav&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=meghnarav&layout=compact&theme=tokyonight&hide_border=true)

 ## 🐍 Contribution Graph
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/meghnarav/meghnarav/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/meghnarav/meghnarav/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/meghnarav/meghnarav/output/github-contribution-grid-snake.svg">
</picture>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2eb398&height=2&section=header" width="100%" />
</p> 

-->
