<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:2ac3de,100:7dcfff&height=300&section=header&text=PARIDHI%20SHARMA&fontSize=100&fontAlignY=40&desc=Backend%20Architect%20%7C%20Distributed%20Systems%20%7C%20Kafka%20Whisperer&descAlignY=55&descSize=20&animation=fadeIn&fontColor=ffffff" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2000&pause=1000&color=7dcfff&center=true&vCenter=true&multiline=true&width=800&height=100&lines=Building+distributed+systems+that+scale+effortlessly;Kafka+%E2%80%A2+Microservices+%E2%80%A2+Event-Driven+Architecture;From+database+schema+to+production+deployment;Where+backend+magic+happens" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/theparidhisharma/"><img src="https://img.shields.io/badge/-LINKEDIN-7dcfff?style=for-the-badge&logo=linkedin&logoColor=1a1b26"/></a>
  <a href="mailto:paridhi0203sharma@gmail.com"><img src="https://img.shields.io/badge/-EMAIL-bb9af7?style=for-the-badge&logo=gmail&logoColor=1a1b26"/></a>
  <a href="https://cresia.in"><img src="https://img.shields.io/badge/-CRESIA-2ac3de?style=for-the-badge&logo=google-chrome&logoColor=1a1b26"/></a>
  <a href="https://justmywritesblog.wordpress.com/"><img src="https://img.shields.io/badge/-BLOG-9d7cd8?style=for-the-badge&logo=hashnode&logoColor=1a1b26"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=theparidhisharma&label=Profile%20Views&color=7dcfff&style=for-the-badge&labelColor=1a1b26" />
  <img src="https://img.shields.io/github/followers/theparidhisharma?label=Followers&style=for-the-badge&color=bb9af7&labelColor=1a1b26" />
  <img src="https://img.shields.io/github/stars/theparidhisharma?label=Stars&style=for-the-badge&color=2ac3de&labelColor=1a1b26" />
</p>

<br/>

<img align="right" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"/>

## 🌟 About Me

**Backend Engineer** who architects systems that don't break under pressure  
**Full-Stack Developer** with end-to-end product ownership  
**System Designer** turning complex problems into elegant solutions

```yaml
current_role: "Co-Founder & Lead Engineer @ Cresia"
education: "B.Tech CSE @ IGDTUW"
previous: "Backend Intern @ Deutsche Telekom Digital Labs"

expertise:
  backend: ["Kafka", "Microservices", "Event-Driven Architecture", "Spring Boot"]
  frontend: ["React", "TypeScript", "Modern UI/UX"]
  systems: ["Distributed Systems", "Production Scale", "Clean Architecture"]

philosophy: "Build systems, not demos. Design for failure. Ship and iterate."
```

<br clear="right"/>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=1500&pause=500&color=7dcfff&center=true&vCenter=true&width=600&lines=✨+FEATURED+PROJECTS+✨" alt="Featured Projects" />
</h1>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<br/>

## <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="30" /> RetargetIQ — Event-Driven Powerhouse

<div align="center">
  <a href="https://github.com/theparidhisharma/RetargetIQ">
    <img src="https://img.shields.io/badge/VIEW%20ON%20GITHUB-7dcfff?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=java,spring,kafka,docker&theme=dark" />
</div>

<br/>

**A production-scale distributed system with 10+ microservices orchestrated through Apache Kafka**

Built to simulate real-world retargeting architectures used by companies like LinkedIn, Uber, and Netflix. This isn't a portfolio project—it's a distributed systems masterclass.

### 🔥 Architecture Flow

```mermaid
graph LR
    A[User Activity] -->|Kafka| B[Event Processor]
    C[Orders] -->|Kafka| B
    B --> D[Feature Store]
    B --> E[Analytics]
    D --> F[Retrieval Service]
    F --> G[Ranking Engine]
    G --> H[Recommendation API]
    H --> I[Frontend UI]
    B --> J[RL Offer Service]
    
    style A fill:#7dcfff,stroke:#2ac3de,stroke-width:3px,color:#1a1b26
    style B fill:#7dcfff,stroke:#2ac3de,stroke-width:3px,color:#1a1b26
    style C fill:#7dcfff,stroke:#2ac3de,stroke-width:3px,color:#1a1b26
    style D fill:#bb9af7,stroke:#9d7cd8,stroke-width:3px,color:#1a1b26
    style E fill:#bb9af7,stroke:#9d7cd8,stroke-width:3px,color:#1a1b26
    style F fill:#2ac3de,stroke:#7dcfff,stroke-width:3px,color:#1a1b26
    style G fill:#2ac3de,stroke:#7dcfff,stroke-width:3px,color:#1a1b26
    style H fill:#9d7cd8,stroke:#bb9af7,stroke-width:3px,color:#1a1b26
    style I fill:#9d7cd8,stroke:#bb9af7,stroke-width:3px,color:#1a1b26
    style J fill:#7dcfff,stroke:#2ac3de,stroke-width:3px,color:#1a1b26
```

### ✨ What Makes It Special

- **Event-Driven Architecture**: Services communicate asynchronously through Kafka topics
- **Complete Decoupling**: Microservices don't know each other exist—pure pub-sub model
- **Production-Ready**: Docker Compose orchestration, proper logging, error handling
- **Real-World Pipeline**: Feature extraction → Retrieval → Ranking → Recommendations
- **Scalable Design**: Built to handle thousands of events per second

> *This is what happens when you combine backend expertise with systems thinking.*

**Tech Stack**: Java • Spring Boot • Apache Kafka • Docker • Microservices • Event Streaming

<br/>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<br/>

## <img src="https://user-images.githubusercontent.com/74038190/216122003-15d1a4b9-0f5d-40d1-b9a8-7f47f2e9c88b.png" width="30" /> SehatAI — AI Health Intelligence Platform

<div align="center">
  <a href="https://github.com/TheNandinee/SehatAI">
    <img src="https://img.shields.io/badge/VIEW%20ON%20GITHUB-bb9af7?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
  <img src="https://img.shields.io/github/stars/TheNandinee/SehatAI?style=social" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=typescript,react,nodejs&theme=dark" />
</div>

<br/>

**Full-stack AI-powered healthcare platform where I owned the entire product engineering**

### 🎯 My Role — Complete Ownership

<table>
<tr>
<td width="50%">

**Frontend Engineering**
- Designed & built entire UI from scratch
- Component-driven React architecture
- Modern, accessible healthcare interface
- Responsive across all devices

</td>
<td width="50%">

**Backend Architecture**
- REST API design & implementation
- Service orchestration layer
- Clean LLM/RAG integration
- Production-ready deployment

</td>
</tr>
</table>

### 💫 Engineering Excellence

**Clean Architecture**: Proper service boundaries where ML layer integrates without creating a monolith  
**Separation of Concerns**: Frontend ↔ Backend ↔ AI layers are completely decoupled  
**Production Focus**: Built for real users, not demo days

> *Proof that AI integration doesn't have to be messy.*

**Tech Stack**: TypeScript • React • Node.js • AI/ML Integration • Clean Architecture

<br/>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<br/>

## <img src="https://user-images.githubusercontent.com/74038190/216120974-24a76b31-7f39-41f1-a38f-b3c1377cc612.png" width="30" /> RAVEN — Constraint Reasoning Engine

<div align="center">
  <a href="https://github.com/theparidhisharma/RAVEN-KDSH-2026">
    <img src="https://img.shields.io/badge/VIEW%20ON%20GITHUB-2ac3de?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
  <img src="https://img.shields.io/badge/Hackathon-Kharagpur%20DSH%202026-9d7cd8?style=for-the-badge&labelColor=1a1b26" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=python&theme=dark" />
</div>

<br/>

**AI system that reads narratives and solves logical constraint problems**

Can machines understand stories well enough to solve logic puzzles? RAVEN says yes.

### 🧠 How It Works

```
Narrative Text → Parse Structure → Extract Constraints → Solve Logic → Output Solution
```

**Capabilities**:
- Converts natural language narratives into logical constraints
- Solves multi-variable constraint satisfaction problems
- Makes deductions based on implicit information
- Handles complex reasoning chains

> *When you need Sherlock Holmes but in code form.*

**Tech Stack**: Python • NLP • Constraint Solving • Logic Programming

<br/>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<br/>

## <img src="https://user-images.githubusercontent.com/74038190/216122065-2f028bae-25d6-4a3c-bc9f-175394ed5011.png" width="30" /> More Cool Projects

<details>
<summary><b>📊 Trader Sentiment Analysis — Fear vs Greed Study</b></summary>
<br/>

<div align="center">
  <a href="https://github.com/theparidhisharma/trader-sentiment-analysis">
    <img src="https://img.shields.io/badge/VIEW%20PROJECT-7dcfff?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
</div>

<br/>

Research exploring how emotional sentiment impacts trader profitability.

**The Question**: Does fear make you poor? Does greed make you rich?  
**The Approach**: Real market data + sentiment analysis + statistical correlation  
**The Answer**: Markets don't care about feelings, but traders do

**Tech**: Python • Data Science • Behavioral Finance
</details>

<details>
<summary><b>🎓 Student Portal — Modern Dashboard</b></summary>
<br/>

<div align="center">
  <a href="https://student-portal-navy-six.vercel.app/">
    <img src="https://img.shields.io/badge/LIVE%20DEMO-bb9af7?style=for-the-badge&logo=vercel&logoColor=1a1b26" />
  </a>
  <a href="https://github.com/theparidhisharma/Student-Portal">
    <img src="https://img.shields.io/badge/VIEW%20CODE-1a1b26?style=for-the-badge&logo=github&logoColor=7dcfff" />
  </a>
</div>

<br/>

Clean, responsive student dashboard with dark/light themes and modern UI patterns.

**Features**: Theme switching • Responsive design • Component reusability • Production deployment

**Tech**: React • Tailwind CSS • JavaScript
</details>

<details>
<summary><b>📄 ATS GradeIT — Resume Intelligence</b></summary>
<br/>

<div align="center">
  <a href="https://github.com/theparidhisharma/ATS-GradeIT">
    <img src="https://img.shields.io/badge/VIEW%20PROJECT-2ac3de?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
</div>

<br/>

NLP-powered resume parser and job-fit scoring system.

**What It Does**: Parse resumes • Extract structured data • Match to job descriptions • Score candidates

**Tech**: Python • NLP • Machine Learning
</details>

<details>
<summary><b>👗 Vibe Matcher — Fashion AI</b></summary>
<br/>

<div align="center">
  <a href="https://github.com/theparidhisharma/Vibe_Matcher_Recommender">
    <img src="https://img.shields.io/badge/VIEW%20PROJECT-9d7cd8?style=for-the-badge&logo=github&logoColor=1a1b26" />
  </a>
</div>

<br/>

Tell me your vibe, I'll find your outfit. Lightweight AI using text embeddings and semantic similarity.

**Tech**: Python • Text Embeddings • Cosine Similarity
</details>

<br/>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h2 align="center">⚡ Tech Arsenal</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,python,typescript,javascript,spring,kafka,docker,react,tailwind,nodejs,mysql,git,github,figma&perline=7&theme=dark" />
</p>

<table align="center">
<tr>
<td align="center" width="33%">

### 🔧 Backend
**Languages**: Java, Python, TypeScript  
**Frameworks**: Spring Boot, Node.js  
**Systems**: Kafka, Microservices  
**Tools**: Docker, REST APIs

</td>
<td align="center" width="33%">

### 🎨 Frontend
**Frameworks**: React, TypeScript  
**Styling**: Tailwind CSS  
**Patterns**: Component Architecture  
**Focus**: Clean, Responsive UI

</td>
<td align="center" width="33%">

### 🧠 Systems
**Architecture**: Event-Driven Design  
**Scale**: Distributed Systems  
**Quality**: Clean Code Principles  
**Deployment**: Production-Ready

</td>
</tr>
</table>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h2 align="center">📊 GitHub Analytics</h2>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=theparidhisharma&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b26&title_color=7dcfff&icon_color=bb9af7&text_color=a9b1d6&rank_icon=github&include_all_commits=true" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=theparidhisharma&theme=tokyonight&hide_border=true&background=1a1b26&stroke=7dcfff&ring=bb9af7&fire=7dcfff&currStreakLabel=7dcfff&sideLabels=7dcfff" />
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=theparidhisharma&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b26&title_color=7dcfff&text_color=a9b1d6&langs_count=10" />
  <img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=theparidhisharma&theme=tokyo-night&hide_border=true&bg_color=1a1b26&color=7dcfff&line=bb9af7&point=7dcfff&area=true&custom_title=Contribution%20Activity" />
</p>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h2 align="center">💼 Professional Journey</h2>

<div align="center">

### ✨ Cresia — Co-Founder & Lead Engineer

**Building production systems that power real businesses**

</div>

```
Role: Architect complete systems from database to deployment
Scope: End-to-end ownership of engineering stack
Impact: Real users, real constraints, real solutions
Learning: Production ≠ tutorials. Constraints breed creativity.
```

<div align="center">

**What I Do**: System architecture • Backend APIs • Frontend implementation • Production deployment  
**What I've Built**: Multiple full-stack products for startups • Scalable infrastructure • Clean codebases

[**Visit Cresia →**](https://cresia.in)

</div>

<br/>

<div align="center">

### ✨ Deutsche Telekom Digital Labs — Backend Intern

**Where distributed systems became second nature**

</div>

```
Experience: Enterprise-scale backend systems
Tech: Apache Kafka, Microservices, Event-driven architecture
Impact: Real production code, real debugging, real scale
Learning: Why logs matter, why simple > clever, why testing saves lives
```

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h2 align="center">💭 Engineering Philosophy</h2>

<table align="center">
<tr>
<td align="center">

### 🎯 Simple > Clever
Code that's too clever  
is code nobody maintains

</td>
<td align="center">

### 📝 Logs > Guesses
If it's not logged,  
it didn't happen

</td>
<td align="center">

### 🚀 Ship → Learn → Iterate
Perfect code never ships.  
Good code improves.

</td>
</tr>
<tr>
<td align="center">

### 💥 Design for Failure
Everything breaks.  
Plan for it.

</td>
<td align="center">

### ✨ Production is Truth
All other environments  
are fantasy

</td>
<td align="center">

### 🧩 Build Systems
Not demos.  
Not features. Systems.

</td>
</tr>
</table>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<div align="center">

## 🐍 Contribution Graph

![Snake animation](https://raw.githubusercontent.com/theparidhisharma/theparidhisharma/output/github-contribution-grid-snake-dark.svg)

</div>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<h2 align="center">📬 Let's Connect</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/theparidhisharma/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-7dcfff?style=for-the-badge&logo=linkedin&logoColor=1a1b26" />
  </a>
  <a href="mailto:paridhi0203sharma@gmail.com">
    <img src="https://img.shields.io/badge/Email-Drop%20a%20Line-bb9af7?style=for-the-badge&logo=gmail&logoColor=1a1b26" />
  </a>
  <a href="https://cresia.in">
    <img src="https://img.shields.io/badge/Cresia-Visit%20Studio-2ac3de?style=for-the-badge&logo=google-chrome&logoColor=1a1b26" />
  </a>
  <a href="https://justmywritesblog.wordpress.com/">
    <img src="https://img.shields.io/badge/Blog-Read%20Thoughts-9d7cd8?style=for-the-badge&logo=hashnode&logoColor=1a1b26" />
  </a>
</p>

<p align="center">
  <b>I'm down to talk about:</b><br/>
  System Architecture • Event-Driven Design • Microservices Patterns • Building for Scale
</p>

<p align="center">
  <b>Not interested in:</b><br/>
  "Build my app for exposure" • Tutorial projects • Ideas without technical depth
</p>

<div align="center">
  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

</div>

<div align="center">

### ✨ Building systems that scale, one Kafka topic at a time ✨

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:2ac3de,100:7dcfff&height=150&section=footer&fontColor=ffffff" />

</div>
