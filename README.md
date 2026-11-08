<!--
  VIVEK NIGAM | GitHub Profile README
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:020617,40:172554,75:4c1d95,100:0891b2&height=280&section=header&text=VIVEK%20NIGAM&fontSize=70&fontColor=ffffff&fontAlignY=40&desc=AI%20ENGINEERING%20%C2%B7%20FULL-STACK%20SYSTEMS&descSize=18&descAlignY=62&animation=fadeIn" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=850&lines=Building+intelligent+systems+%26+real-time+products;RAG+%C2%B7+LLMs+%C2%B7+Machine+Learning;Full-stack+apps+that+actually+ship;Understand+deeply.+Build+intelligently.+Ship+consistently." alt="Animated introduction" />

<br/>

<a href="https://github.com/vivek28n"><img src="https://img.shields.io/badge/GitHub-vivek28n-0b1220?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/vivek-nigam-28n/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:nigamvivek2805@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-0891B2?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<img src="https://img.shields.io/badge/OPEN%20TO-SWE%20%2F%20AI%20INTERNSHIPS-10B981?style=flat-square" />
<img src="https://img.shields.io/badge/DOMAIN-ARTIFICIAL%20INTELLIGENCE-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/FOCUS-FULL--STACK%20ENGINEERING-06B6D4?style=flat-square" />
<img src="https://img.shields.io/badge/STATUS-ACTIVELY%20BUILDING-F59E0B?style=flat-square" />

<br/><br/>

<sub><a href="#about">ABOUT</a> &nbsp;·&nbsp; <a href="#projects">PROJECTS</a> &nbsp;·&nbsp; <a href="#tech-stack">STACK</a> &nbsp;·&nbsp; <a href="#now">NOW</a> &nbsp;·&nbsp; <a href="#contact">CONTACT</a></sub>

</div>

---

## About

```yaml
name: Vivek Nigam
role: B.Tech CSE (Artificial Intelligence) Student
building: [RAG systems, real-time apps, digital twins, ML-powered products]
languages: [Java, Python, JavaScript, TypeScript]
objective: Engineer reliable, production-ready software that solves real problems
philosophy: "Understand deeply. Build intelligently. Ship consistently."
```

I work across the stack, from interactive 3D interfaces and real-time backends to retrieval pipelines and ML models. I care less about collecting technologies and more about understanding how they fit together into a product people can actually use.

---

## Projects

<sub>FOUR SELECTED BUILDS · EACH ONE EXPANDS TO ITS SYSTEM ARCHITECTURE</sub>

<br/>

### <img src="https://img.shields.io/badge/01-REAL--TIME%20SYSTEMS-0891B2?style=for-the-badge" />&nbsp; QueueLess

> **Real-time queue management.** Contactless check-in and live position tracking, no app install.

<a href="https://queue-less-nine.vercel.app"><img src="https://img.shields.io/badge/▶_LIVE_DEMO-Visit%20App-10B981?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/vivek28n/QueueLess"><img src="https://img.shields.io/badge/SOURCE-Repository-334155?style=for-the-badge&logo=github&logoColor=white"/></a>

- ⚡ Live token position and status updates over **Socket.IO**
- 🔗 QR-based queue joining for guests
- 🏢 Multi-tenant business accounts with **JWT** auth and an admin dashboard
- 🔒 Atomic token generation to handle concurrent requests

`React 19` `Vite` `Tailwind` `Node.js` `Express` `MongoDB` `Socket.IO` `Three.js`

<details>
<summary><b>▸ View system architecture</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#172554','primaryTextColor':'#E2E8F0','primaryBorderColor':'#22D3EE','lineColor':'#A78BFA','secondaryColor':'#0f172a','tertiaryColor':'#020617'}}}%%
flowchart LR
    A["Customer<br/>QR scan"] --> B["React client"]
    B -->|REST| C["Express API<br/>JWT auth"]
    C --> D[("MongoDB<br/>multi-tenant")]
    C <-->|Socket.IO| B
    C <-->|Socket.IO| E["Admin dashboard"]
```

</details>

<br/>

### <img src="https://img.shields.io/badge/02-GENERATIVE%20AI-7C3AED?style=for-the-badge" />&nbsp; Medical RAG &nbsp;<img src="https://img.shields.io/badge/-IN%20PROGRESS-F59E0B?style=flat-square" />

> **Hallucination detection and reliable retrieval.** Making AI answers more grounded in medical document workflows. Research paper in progress.

<a href="https://github.com/vivek28n/Medical-RAG-Hallucination-Detection"><img src="https://img.shields.io/badge/SOURCE-Repository-334155?style=for-the-badge&logo=github&logoColor=white"/></a>

- 📄 PDF ingestion, chunking, and embedding generation
- 🔎 Semantic retrieval through vector databases
- 🎯 Hallucination detection with confidence scoring
- ⚙️ FastAPI backend + React frontend

`Python` `FastAPI` `LangChain` `FAISS / ChromaDB` `React`

<details>
<summary><b>▸ View system architecture</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#172554','primaryTextColor':'#E2E8F0','primaryBorderColor':'#22D3EE','lineColor':'#A78BFA','secondaryColor':'#0f172a','tertiaryColor':'#020617'}}}%%
flowchart LR
    A["PDF documents"] --> B["Chunking"] --> C["Embeddings"] --> D[("FAISS / ChromaDB")]
    Q["User question"] --> R["Semantic retrieval"]
    D --> R --> L["LLM answer"] --> H{"Hallucination check"} --> S["Answer + confidence score"]
```

</details>

<br/>

### <img src="https://img.shields.io/badge/03-DIGITAL%20TWINS-06B6D4?style=for-the-badge" />&nbsp; Ocean3D

> **Interactive ocean digital twin.** Explore ocean conditions across regions, depths, and time.

<a href="https://ocean3d.vercel.app"><img src="https://img.shields.io/badge/▶_LIVE_DEMO-Explore%20Ocean3D-10B981?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/vivek28n/Ocean3d"><img src="https://img.shields.io/badge/SOURCE-Repository-334155?style=for-the-badge&logo=github&logoColor=white"/></a>

- 🌐 WebGL 3D ocean visualization with multiple regions and depths
- 📊 Model vs. observation comparison, RMSE analysis, anomaly detection
- 🧭 Ocean current-flow visualization
- 🤖 Simulated research AUV and glider layer

`React` `TypeScript` `Three.js` `FastAPI` `Python` `NumPy` `Pandas`

<details>
<summary><b>▸ View system architecture</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#172554','primaryTextColor':'#E2E8F0','primaryBorderColor':'#22D3EE','lineColor':'#A78BFA','secondaryColor':'#0f172a','tertiaryColor':'#020617'}}}%%
flowchart LR
    A["Ocean models"] --> P
    B["Observations"] --> P
    S["Satellite-derived data"] --> P
    P["FastAPI + NumPy / Pandas<br/>RMSE · anomaly detection"] --> V["React + Three.js<br/>3D digital twin"]
```

</details>

<br/>

### <img src="https://img.shields.io/badge/04-INTELLIGENT%20MOBILITY-10B981?style=for-the-badge" />&nbsp; Smart EV Charging

> **Find the right charging station, not just the nearest one.** Stations ranked on multiple factors instead of distance alone.

<a href="https://github.com/vivek28n/Smart-EV-charging-managment-system"><img src="https://img.shields.io/badge/SOURCE-Repository-334155?style=for-the-badge&logo=github&logoColor=white"/></a>

- 🤖 AI-based waiting-time prediction
- ⚖️ Weighted multi-factor station ranking
- 📍 Haversine distance calculation
- 🗺️ Interactive Leaflet maps with lazy loading

`React` `TypeScript` `Tailwind` `Node.js` `Supabase` `PostgreSQL`

<details>
<summary><b>▸ View system architecture</b></summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#172554','primaryTextColor':'#E2E8F0','primaryBorderColor':'#22D3EE','lineColor':'#A78BFA','secondaryColor':'#0f172a','tertiaryColor':'#020617'}}}%%
flowchart LR
    U["User location"] --> F["Nearby stations"]
    F --> W["Wait-time prediction"]
    F --> H["Haversine distance"]
    W --> R["Weighted multi-factor score"]
    H --> R
    R --> M["Ranked stations on Leaflet map"]
```

</details>

---

## Tech Stack

<div align="center">

<sub>LANGUAGES</sub><br/>
<img src="https://skillicons.dev/icons?i=java,python,js,ts,php&theme=dark" />

<sub>AI / MACHINE LEARNING</sub><br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,pandas,numpy&theme=dark" />

<sub>FRONTEND</sub><br/>
<img src="https://skillicons.dev/icons?i=react,threejs,html,css,tailwind,bootstrap&theme=dark" />

<sub>BACKEND</sub><br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,spring&theme=dark" />

<sub>DATABASES & CLOUD</sub><br/>
<img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,supabase,firebase,aws&theme=dark" />

<sub>TOOLS</sub><br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,postman,vercel,vscode&theme=dark" />

</div>

---

## Problem Solving

<div align="center">

<a href="https://leetcode.com/u/vivek28n/">
  <img src="https://leetcard.jacoblin.cool/vivek28n?theme=dark&font=JetBrains%20Mono&ext=heatmap" alt="LeetCode stats" width="560" />
</a>

<br/><br/>

<a href="https://leetcode.com/u/vivek28n/"><img src="https://img.shields.io/badge/LeetCode-vivek28n-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
<a href="https://codolio.com/profile/Vivek28"><img src="https://img.shields.io/badge/Codolio-Vivek28-7C3AED?style=for-the-badge" /></a>

<sub>DSA · PROBLEM SOLVING IN JAVA</sub>

</div>

---

## GitHub Stats

<div align="center">

<a href="https://github.com/vivek28n">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vivek28n&theme=tokyonight" alt="GitHub profile details" />
</a>
<a href="https://github.com/vivek28n">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vivek28n&theme=tokyonight" alt="GitHub stats" />
</a>

<a href="https://github.com/vivek28n">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=vivek28n&theme=tokyonight" alt="Repos per language" />
</a>
<a href="https://github.com/vivek28n">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=vivek28n&theme=tokyonight" alt="Most commit language" />
</a>

<br/>

<img width="95%" src="https://streak-stats.demolab.com/?user=vivek28n&theme=tokyonight&hide_border=true&background=020617&ring=22D3EE&fire=A78BFA&currStreakLabel=22D3EE" alt="GitHub contribution streak" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=vivek28n&bg_color=020617&color=CBD5E1&line=22D3EE&point=A78BFA&area=true&hide_border=true&custom_title=Contribution%20Activity" alt="Contribution activity graph" />

</div>

---

## Now

<div align="center">

| | CURRENT FOCUS |
|:---:|:---|
| `01` | Java + Data Structures & Algorithms |
| `02` | RAG evaluation and hallucination reduction |
| `03` | Generative AI and LLM applications |
| `04` | Backend architecture and scalable systems |
| `05` | Production deployment and engineering practices |

</div>

> **Mindset:** move beyond tutorials, understand the underlying system, then build, test, evaluate, and improve.

---

## Contact

<div align="center">

**Got an interesting idea, an engineering problem, or a collaboration in mind?**
Open to conversations around AI/ML, GenAI, RAG systems, and full-stack engineering.

<br/>

<a href="https://www.linkedin.com/in/vivek-nigam-28n/"><img src="https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:nigamvivek2805@gmail.com"><img src="https://img.shields.io/badge/Email-Start%20a%20Conversation-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=vivek28n&style=for-the-badge&color=0891B2&label=VISITORS" alt="Profile visitors" />

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891b2,50:4c1d95,100:020617&height=140&section=footer" width="100%" />

<sub>ENGINEERED WITH CURIOSITY · POWERED BY CONSISTENCY</sub>

</div>
