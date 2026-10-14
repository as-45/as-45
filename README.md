<p align="center">
  <img src="./header.svg" alt="Athreya Shashidhara — Backend & GenAI Developer" width="100%"/>
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/athreya-shashidhara-74402b334/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:athreyashashi11@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Internships%20(Jan%202027)-22C55E?style=for-the-badge" alt="Open to internships"/>
</p>
---
 
### 👋 About me
 
I build **AI agents that can be trusted with real actions**, and the backend systems that keep them safe.
 
- 🎓 Final-year **B.Tech CSE** at **PES University**, Bangalore (graduating 2027)
- 🤖 Focused on **Agentic AI, LLMs and RAG**, built on solid **backend fundamentals** (Java, Spring Boot, FastAPI, SQL)
- 🔬 **Summer Research Intern at CDSAML, PES University**: studied how image compression affects chest X-ray AI models (CNN vs Vision Transformer vs MLP)
- 🏆 **1st place, Fin-a-thon** (38 teams) · built for the **Razorpay AI Buildathon** and **Honeywell Eco-Loop**
- 🧩 **200+ LeetCode** problems solved in C++
- 🌱 Currently exploring: **voice AI** and real-time speech pipelines
---
 
### 🧠 How I build agents
 
My Razorpay Buildathon agent shops and pays for a user, so every step has a guardrail:
 
```mermaid
flowchart LR
    U([🧑 User request]) --> P[Parse intent]
    P --> S[Search catalog]
    S --> G{🛡️ Prompt-injection<br/>screen}
    G -- unsafe --> X([🚫 Blocked])
    G -- safe --> Q[Quote + 5-min hold]
    Q --> H{👤 Human<br/>approval}
    H -- approve --> PAY[💳 Pay<br/>idempotent API]
    PAY --> A[(📜 Audit log)]
    H -- reject --> X
```
 
---
 
### 🚀 Featured projects
 
| Project | What it does | Built with |
|---|---|---|
| 🛒 **[Agentic Commerce App](REPLACE_WITH_REPO_LINK)** | LangGraph agent that shops & pays with human approval, spend limits, prompt-injection screening, idempotent APIs and **190+ tests** | Python · LangGraph · FastAPI · SQL · pytest |
| 🎯 **[PrepAIred](REPLACE_WITH_REPO_LINK)** | Capstone: adaptive interview prep with a **PPO** difficulty policy and an SBERT + FAISS grader (**0.84** correlation with experts) | PyTorch · SBERT · FAISS · Docker |
| 💻 **[Real-Time Collaborative Coding Platform](https://github.com/as-45/CN-Project)** | Multi-user code editor where every keystroke syncs instantly across rooms | React · Node.js · Socket.io |
| 🔍 **[Repo Breaker](REPLACE_WITH_REPO_LINK)** | Paste a GitHub repo and ask questions about its code (RAG over source files) | FastAPI · SBERT · FAISS · React |
| 🗺️ **[Tourist Recommendation System](REPLACE_WITH_REPO_LINK)** | Personalised travel recommendations on a normalised MySQL schema | Flask · MySQL · REST |
 
---
 
### 🛠️ Tech stack
 
**AI & LLMs**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-SBERT%20%2B%20FAISS-6366F1?style=flat-square"/>
</p>
**Backend**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
</p>
**Tools & frontend**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
</p>
---
 
<p align="center">
  <i>Always happy to talk about agents, backend systems, or a good DSA problem. Say hi! 👋</i>
</p>
 
