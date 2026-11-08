<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,50:4169E1,100:00F7FF&height=200&section=header&text=Saruhasan%20Thavachelvan&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Full%20Stack%20%E2%80%A2%20System%20Design%20%E2%80%A2%20AI%20Engineering&descAlignY=58&descSize=17&animation=fadeIn" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=00F7FF&center=true&vCenter=true&width=780&lines=Full+Stack+Developer;Designing+Highly+Scalable+Systems;AI+Engineering+%26+RAG+Pipelines;Distributed+Systems+%7C+Cloud+%7C+DevOps;Build.+Break.+Learn.+Improve." alt="Typing SVG" />

<br/>

<a href="https://github.com/Saru-Work"><img src="https://img.shields.io/badge/GitHub-Saru--Work-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://linkedin.com/in/saruhasan-thavachelvan"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:saruatwork@email.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=Saru-Work&style=for-the-badge&color=00F7FF&label=PROFILE+VIEWS" />

</div>

<br/>

## `01 / ABOUT ME`

<img align="right" width="340" src="https://github-readme-streak-stats.demolab.com?user=Saru-Work&theme=tokyonight&hide_border=true&background=0D1117" alt="streak" />

I'm a **Full Stack Developer** from Sri Lanka 🇱🇰 who loves going beyond "it works" to **"it scales."**
I enjoy designing systems that stay fast and reliable under load — and lately I've been
pairing that with **AI engineering**, building **Retrieval-Augmented Generation (RAG)** pipelines
that ground LLMs in real data.

- 🏗️ Designing **highly scalable, distributed systems** — caching, queues, sharding, fault tolerance
- 🤖 Exploring **AI Engineering** — LLM apps, embeddings, vector search & **RAG pipelines**
- 💻 Shipping full-stack products with **Next.js, React, Node.js, FastAPI & TypeScript**
- ☁️ Learning **Docker, CI/CD & cloud infrastructure** to take projects to production
- 🎓 Undergraduate at **Sabaragamuwa University of Sri Lanka**

<br clear="right"/>

```typescript
const saruhasan = {
  role: "Full Stack Developer",
  university: "Sabaragamuwa University of Sri Lanka",
  interests: [
    "System Design",
    "Highly Scalable Distributed Systems",
    "AI Engineering",
    "RAG (Retrieval-Augmented Generation)",
  ],
  currentlyBuilding: ["RAG pipelines", "Scalable backend services"],
  currentlyLearning: ["LLM orchestration", "Vector databases", "Docker & CI/CD", "Cloud infra"],
  motto: "Build. Break. Learn. Improve.",
};
```

---

## `02 / WHAT I'M INTO`

<table>
<tr>
<td width="33%" valign="top">

### 🏗️ System Design
Load balancing, caching layers, message queues, database sharding & replication, rate limiting, and designing for failure.

</td>
<td width="33%" valign="top">

### 🤖 AI Engineering
LLM-powered applications, prompt design, embeddings, evaluation, and integrating models into real products.

</td>
<td width="33%" valign="top">

### 🔎 RAG Systems
Document ingestion, chunking, vector search, hybrid retrieval, re-ranking and grounded generation — built to scale.

</td>
</tr>
</table>

### 🧠 How I think about a scalable RAG system

```mermaid
flowchart LR
    A[📄 Documents] --> B[Chunking & Cleaning]
    B --> C[Embedding Model]
    C --> D[(Vector DB)]
    U[👤 User Query] --> GW[API Gateway / Load Balancer]
    GW --> Q[Query Embedding]
    Q --> D
    D --> R[Re-ranker]
    R --> L[LLM]
    L --> GW
    GW -.cache hits.-> K[(Redis Cache)]
    B -.async jobs.-> MQ[[Message Queue]]
```

---

## `03 / TECH STACK`

<div align="center">

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,bootstrap&perline=8" />

**Backend**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,python,java,spring&perline=8" />

**Databases & Caching**<br/>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,redis,firebase,prisma&perline=8" />

**DevOps, Cloud & Tools**<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,aws,nginx,linux,git,postman,figma&perline=9" />

**AI / ML & RAG**<br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/Vector%20DBs-00B4D8?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />

</div>

---

## `04 / FEATURED PROJECTS`

<table>
<tr>
<td width="50%" valign="top">

### 🚀 HallSync
**Smart Lecture Hall Management**

Faculty-level lecture hall management and smart scheduling system.

- 📅 Lecture creation & scheduling
- 🔁 Timetable management & rescheduling
- 🔐 Role-based access (Admin / Lecturer / Student)
- 🔔 Department-specific notifications

<img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />

</td>
<td width="50%" valign="top">

### 💍 Viwahaa
**Matrimony Platform**

Full-stack matrimony platform with membership management and admin workflows.

- 💳 Membership & subscription management
- 🖼️ Profile & image management
- 📊 Admin dashboard
- ✅ Payment & verification workflows

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

</td>
</tr>
</table>

---

## `05 / GITHUB ANALYTICS`

<!-- These cards are generated inside this repo by .github/workflows/profile-summary-cards.yml,
     so they never depend on a rate-limited public server. -->

<div align="center">

<img src="./profile-summary-card-output/tokyonight/0-profile-details.svg" width="100%" />

<img src="./profile-summary-card-output/tokyonight/3-stats.svg" width="49%" />
<img src="./profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="49%" />

<img src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" width="49%" />
<img src="./profile-summary-card-output/tokyonight/4-productive-time.svg" width="49%" />

</div>

---

## `06 / CONTRIBUTION ACTIVITY`

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Saru-Work/Saru-Work/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Saru-Work/Saru-Work/output/github-contribution-grid-snake.svg" alt="Contribution Snake" width="100%" />
</picture>
</div>

---

## `07 / CURRENT FOCUS`

| Area | Focus |
|:---|:---|
| 🏗️ **System Design** | Highly scalable & distributed systems, microservices, fault tolerance |
| 🤖 **AI Engineering** | LLM-powered apps, embeddings, evaluation |
| 🔎 **RAG** | Retrieval pipelines, vector search, re-ranking, grounding at scale |
| ⚙️ **Backend Engineering** | API design, caching, queues, database performance |
| 💻 **Full Stack** | Production-ready apps with Next.js, React & Node.js |
| ☁️ **DevOps & Cloud** | Docker, CI/CD, AWS & automation |

---

## `08 / LET'S CONNECT`

<div align="center">

**Open to collaborating on scalable backends, AI/RAG systems, or anything ambitious. Let's build something!**

<a href="https://github.com/Saru-Work"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" /></a>
<a href="https://linkedin.com/in/saruhasan-thavachelvan"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" /></a>
<a href="mailto:saruatwork@email.com"><img src="https://img.shields.io/badge/Email-Let's_Talk-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:4169E1,100:7B2FF7&height=130&section=footer&text=Building%20the%20future,%20one%20commit%20at%20a%20time%20🚀&fontSize=18&fontColor=ffffff&fontAlignY=70" width="100%" />

</div>
