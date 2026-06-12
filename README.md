<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=700&lines=Mohammed+Arhaan+Ali;AI+%26+Software+Engineer;RAG+Systems+%7C+Multi-Agent+AI;Learning+What+AI+Cannot+Replace" alt="Typing SVG" />
</div>

<div align="center">


![CGPA](https://img.shields.io/badge/CGPA-9.53%2F10-brightgreen?style=for-the-badge)
![Research](https://img.shields.io/badge/Published-ICSCDS%202025-blue?style=for-the-badge&logo=googlescholar&logoColor=white)
![LeetCode](https://img.shields.io/badge/LeetCode-500%2B%20Solved-orange?style=for-the-badge&logo=leetcode&logoColor=white)
![Location](https://img.shields.io/badge/Mumbai-India-red?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

<div align="center">

**AI & Software Engineer** · Mumbai, India · [Portfolio](https://mohammed-arhaan-ali-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/mohammed-arhaan-ali-5632462b0/) · [Email](mailto:arhaan.ali2004@gmail.com)

Final-year AI & Data Science engineer (CGPA 9.53). Published researcher at ICSCDS 2025. I build and ship production AI systems — RAG pipelines, multi-agent backends, and full-stack applications with live deployments.

<img src="https://komarev.com/ghpvc/?username=ArhaanAli04&label=Profile+Views&color=6E40C9&style=flat" alt="profile views"/>

</div>

---

## 🚀 Featured Projects

### [AI Travel Copilot](https://github.com/ArhaanAli04/ai-travel-copilot) · [Live Demo](https://ai-travel-copilot.vercel.app/) · [GitHub](https://github.com/ArhaanAli04/ai-travel-copilot)
Full-stack AI assistant with three intelligent modules: multi-destination trip planning, automated flight disruption resolution, and local experience discovery.

- Architected a flight disruption pipeline that resolves ambiguous airport queries via NLP, enriches cases with live AviationStack and weather data, generates regulatory-compliant compensation options, and drafts passenger emails using Gemini — **reducing manual resolution to zero human steps**
- Built a local experience discovery module ingesting OSM, Reddit, and blog data into MongoDB with a Qdrant-backed RAG pipeline, returning context-aware POI recommendations filtered by live GPS location, time-of-day, and user preference embeddings
- Multi-destination planning with dynamic re-planning, real-time flight and hotel search, and multi-user collaboration

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4B4B?style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

---

### [RAG Study Assistant](https://github.com/ArhaanAli04/rag-study-assistant) · [Live Demo](https://rag-study-assistant-chi.vercel.app/) · [GitHub](https://github.com/ArhaanAli04/rag-study-assistant)
Production-ready RAG application for document-based learning — chat, quizzes, and concept maps over uploaded documents.

- Engineered hybrid retrieval combining FAISS dense vector search and BM25 sparse keyword matching, with a **3-tier grounding system (strict / loose / none)** that measurably reduces hallucination rate
- FastAPI backend with JWT + OAuth authentication, multi-format document ingestion (PDF, PPTX, DOCX), and isolated vector stores per user for concurrent multi-user sessions
- Semantic caching via Redis to reduce redundant LLM calls; CI-based GitHub deployments

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

---

### F1 Real-Time Strategy Engine · [GitHub](#) · `In Progress`
End-to-end race strategy and telemetry platform — 8 microservices, live telemetry via WebSockets, ML race predictions, and cross-platform frontends.

- Temporal validation pipeline training on 2023–2024 seasons to predict 2025 races, achieving **86.18% ROC AUC** with 57 engineered features and incremental retraining as new results arrive
- Full observability stack: Prometheus metrics, Grafana dashboards, structured logging with correlation IDs, and k6 load testing
- CI/CD via GitHub Actions, Docker multi-stage builds, Kubernetes deployment with HPA and liveness probes
- Frontends: React (web) · Tauri (desktop) · React Native (mobile)

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)

---

### [F1 Race Predictor](https://github.com/ArhaanAli04/f1-race-predictor) · [GitHub](https://github.com/ArhaanAli04/f1-race-predictor)
Predecessor ML model for F1 race outcome prediction — the foundation the Strategy Engine is built on.

- **86.18% ROC AUC** across multi-season temporal validation
- 57 features from 1,177 race records including qualifying delta, constructor momentum, driver win rate, and circuit-specific historical performance
- Automated data ingestion via OpenF1 API with incremental retraining

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)

---

## 📄 Research

**"A Novel Parallel Recurrent Fusion Network for Stock Market Forecasting"**
*International Conference on Sustainable Computing and Data Science (ICSCDS), 2025*
Proposed a parallel recurrent fusion architecture combining multiple RNN variants for improved time-series forecasting accuracy on financial data.

---

## 🛠️ Tech Stack

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4B4B?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=for-the-badge)

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)

---

## Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ArhaanAli04&theme=tokyo-night&hide_border=true&area=true" alt="Activity Graph"/>
</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats-azure-seven-55.vercel.app/api?username=ArhaanAli04&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&cache_seconds=1800"/>
  <img height="180em" src="https://github-readme-stats-azure-seven-55.vercel.app/api/top-langs/?username=ArhaanAli04&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=1800"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ArhaanAli04&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 💻 LeetCode Stats

<div align="center">
  <img src="https://leetcard.jacoblin.cool/ArhaanAli04?theme=dark&font=Fira%20Code&ext=contest&hide_border=true" alt="LeetCode Stats"/>
</div>

---

## 🏆 Achievements

- 🥇 **Rank 1 / 134** — AI & Data Science Department, Semester VI (10/10 GPA)
- 📄 **Published researcher** — ICSCDS 2025
- 💻 **500+ DSA problems** solved on LeetCode

---

<div align="center">

**Snake eating my contributions 🐍**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ArhaanAli04/ArhaanAli04/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ArhaanAli04/ArhaanAli04/output/github-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/ArhaanAli04/ArhaanAli04/output/github-snake.svg">
</picture>

</div>
