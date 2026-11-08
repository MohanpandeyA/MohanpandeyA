<!-- Visitor Counter -->
<p align="right">
  <img src="https://komarev.com/ghpvc/?username=MohanpandeyA&label=Profile%20views&color=blueviolet&style=flat" alt="MohanpandeyA" />
</p>

<!-- Animated Typing Headline -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=A855F7&center=true&vCenter=true&width=750&lines=Hey+there%2C+I'm+Mohan+Pandey+%F0%9F%91%8B;Full-Stack+%26+AI+Developer+%F0%9F%9A%80;LangGraph+%7C+RAG+%7C+FastAPI+%7C+MERN;" alt="Typing SVG" />
  </a>
</p>

---

## 🧑‍💻 About Me

```python
mohan = {
    "name":        "Mohan Pandey",
    "education":   "B.Tech ECE @ MNIT Jaipur (2022–2026)",
    "role":        "Product Development Engineering Intern @ Phenom People",
    "previously":  "Software Development Engineer Intern (AI) @ Piramal Finance",
    "location":    "India 🇮🇳",
    "focus":       ["LLM Agents", "RAG Systems", "MERN Stack", "Systems Programming"],
    "currently":   "Building backend and AI systems",
    "stack":       ["Python", "FastAPI", "LangGraph", "React", "MongoDB", "Kafka"],
    "achievements": [
        "LeetCode rating: 1777",
        "Solved 650+ DSA problems"
    ],
    "fun_fact":    "I built a Mini RTOS Scheduler in C just for fun 🤓"
}
```

---

## 💼 Experience

### 🧩 Phenom People — *Product Development Engineering Intern*
**Nov 2026 – Present**

### 🏦 Piramal Finance Limited — *Software Development Engineer Intern (AI)*
**Mar 2026 – Oct 2026 | India**

- 🤖 Contributed to **Sud Boss Agent** — a production **LangGraph** service for automated NBFC loan disbursement nudging; a **stateful 11-node directed graph** over a `SudWorkflowState` TypedDict routing leads through data fetch, sanction validation, **LLM-based next-best-actor selection** (Azure OpenAI), escalation decision, and multi-channel communication dispatch — **deployed to production** processing real loan leads daily
- 🔀 Built the **Subsequent Disbursal node**: implemented a **channel decision tree** (WhatsApp on first contact, voice call on repeat, hard-stop at max VC attempts) based on outbound WA/VC counts and inbound response state; added **team-aware Exotel template selection** (SALES vs. OPERATIONS)
- 🛠️ **Stack**: Python, FastAPI, LangGraph, LangChain, Azure OpenAI, MongoDB, Pydantic, Kafka, MCP (Model Context Protocol), AWS Parameter Store

---

## 🚀 Featured Project:

### 🧠 [QuantMind — AI-Powered Algorithmic Trading Strategy Advisor](https://github.com/MohanpandeyA/quantmind)
*Full-stack AI application with multi-agent orchestration, vector search pipeline, quantitative backtesting, and real-time data streaming*

- 📐 Designed a **7-node LangGraph state machine** with shared `TypedDict` state and **conditional retry edges** — `RiskAgent` routes back to `StrategyAgent` (max 3 retries) when Sharpe/VaR/drawdown thresholds are breached
- 🔍 Built a **RAG pipeline** over SEC EDGAR filings and news feeds using `sentence-transformers` (384-dim embeddings), **ChromaDB** vector store with metadata filtering, and **MMR reranking** (λ=0.5) for semantically diverse document retrieval
- ⚡ Implemented **O(1) online algorithms** — Welford's running mean/variance with circular buffer and incremental EMA — and **Segment Tree** range queries (O(log n)) for support/resistance detection
- 🌐 Developed **WebSocket server** with `ConnectionManager` for concurrent real-time price alert broadcasting; thread-safe singleton model loading via double-checked locking
- 🏷️ **Stack**: React.js, Vite, TailwindCSS, FastAPI, Python, LangGraph, ChromaDB, sentence-transformers, FinBERT, Groq LLM, MongoDB, WebSocket, Recharts

---

### 🎨 [Collaborative Whiteboard — Real-time Drawing | MERN Stack](https://github.com/MohanpandeyA/whiteboard)
*Real-time multi-user drawing platform with saved canvases and live sync*

- 🔐 Built **JWT login** with canvases saved to **MongoDB Atlas** and auto-saved as people draw
- ⚡ Used **Socket.IO rooms** to broadcast strokes live, throttled to **30fps**
- 🛡️ Hardened the server with **Helmet**, **rate limiting** and **input validation**
- 🏷️ **Stack**: React.js, Socket.IO, Node.js, Express.js, MongoDB Atlas, JWT, RoughJS
---
## 🛠️ Tech Stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,js,ts,c,cpp,html,css&theme=dark" />
</p>

### AI / ML
<p>
  <img src="https://skillicons.dev/icons?i=pytorch&theme=dark" />
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img alt="Azure OpenAI" src="https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img alt="ChromaDB" src="https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white"/>
  <img alt="FinBERT" src="https://img.shields.io/badge/FinBERT-FF9900?style=for-the-badge&logoColor=white"/>
  <img alt="Groq" src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white"/>
  <img alt="MCP" src="https://img.shields.io/badge/MCP-Model%20Context%20Protocol-6366F1?style=for-the-badge&logoColor=white"/>
</p>

### Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite&theme=dark" />
  <img alt="Ant Design" src="https://img.shields.io/badge/Ant%20Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white"/>
  <img alt="Recharts" src="https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logoColor=white"/>
  <img alt="WebSocket" src="https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logoColor=white"/>
</p>

### Backend & Databases
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,mongodb,redis,docker&theme=dark" />
  <img alt="Kafka" src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logoColor=white"/>
  <img alt="AWS" src="https://img.shields.io/badge/AWS%20Parameter%20Store-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

### Tools
<p>
  <img src="https://skillicons.dev/icons?i=git,github,postman,linux,vscode&theme=dark" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MohanpandeyA&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohanpandeyA&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="180" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MohanpandeyA&theme=tokyonight&hide_border=true" height="180" />
</p>

---

## 🎯 Achievements & Competitive Programming

<table>
  <tr>
    <td>🏅</td>
    <td><strong>LeetCode</strong> contest rating: <strong>1,777</strong></td>
    <td>2026</td>
  </tr>
  <tr>
    <td>💡</td>
    <td>Solved <strong>650+</strong> Data Structures & Algorithms problems across platforms</td>
    <td>2026</td>
  </tr>
</table>

---

## 🎓 Education

**Malaviya National Institute of Technology (MNIT), Jaipur**
*B.Tech — Electronics and Communication Engineering | 2022 – 2026*

**Positions of Responsibility:**
- 🎪 **Technical Executive**, Sphinx 2023, MNIT — *Rajasthan's largest techno-management fest*
- 📡 **Technical Executive**, The Mavericks, MNIT — *Official Mass and Media Body of MNIT*

---

## 📫 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/mohan-shyam-pandey-45713025a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:mohanspandey2003@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://leetcode.com/pandeymohan1239" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</p>

---

<p align="center">
  <i>"First, solve the problem. Then, write the code." – John Johnson</i>
</p>
