# Mohammed Arhaan Ali

**AI & Software Engineer** · Mumbai, India · [Portfolio](#) · [LinkedIn](#) · [Email](mailto:arhaan.ali2004@gmail.com)

Final-year AI & Data Science engineer (Rank 1 / 134 · CGPA 9.53). Published researcher at ICSCDS 2025. I build and ship production AI systems — RAG pipelines, multi-agent backends, and full-stack applications with live deployments.

---

## Featured Projects

### [AI Travel Copilot](#) · [Live Demo](https://ai-travel-copilot.vercel.app/) · [GitHub](https://github.com/ArhaanAli04/ai-travel-copilot)
Full-stack AI assistant with three intelligent modules: multi-destination trip planning, automated flight disruption resolution, and local experience discovery.

- Architected a flight disruption pipeline that resolves ambiguous airport queries via NLP, enriches cases with live AviationStack and weather data, generates regulatory-compliant compensation options, and drafts passenger emails using Gemini — reducing manual resolution to zero human steps
- Built a local experience discovery module ingesting OSM, Reddit, and blog data into MongoDB with a Qdrant-backed RAG pipeline, returning context-aware POI recommendations filtered by live GPS location, time-of-day, and user preference embeddings
- Multi-destination planning with dynamic re-planning, real-time flight and hotel search, and multi-user collaboration

**Stack:** FastAPI · Gemini · LangChain · Qdrant · MongoDB · Redis · React

---

### [RAG Study Assistant](#) · [Live Demo](#) · [GitHub](#)
Production-ready RAG application for document-based learning — chat, quizzes, and concept maps over uploaded documents.

- Engineered hybrid retrieval combining FAISS dense vector search and BM25 sparse keyword matching, with a 3-tier grounding system (strict / loose / none) that measurably reduces hallucination rate
- FastAPI backend with JWT + OAuth authentication, multi-format document ingestion (PDF, PPTX, DOCX), and isolated vector stores per user for concurrent multi-user sessions
- Semantic caching via Redis to reduce redundant LLM calls; CI-based GitHub deployments

**Stack:** FastAPI · Gemini · FAISS · BM25 · Redis · PostgreSQL · React

---

### [F1 Real-Time Strategy Engine](#) · [GitHub](#) · `In Progress`
End-to-end race strategy and telemetry platform — 8 microservices, live telemetry via WebSockets, ML race predictions, and cross-platform frontends.

- Temporal validation pipeline training on 2023–2024 seasons to predict 2025 races, achieving **86.18% ROC AUC** with 57 engineered features and incremental retraining as new results arrive
- Full observability stack: Prometheus metrics, Grafana dashboards, structured logging with correlation IDs, and k6 load testing
- CI/CD via GitHub Actions, Docker multi-stage builds, Kubernetes deployment with HPA and liveness probes
- Frontends: React (web) · Tauri (desktop) · React Native (mobile)

**Stack:** FastAPI · PostgreSQL · Redis · Docker · Kubernetes · React · Tauri · React Native · GitHub Actions

---

### [F1 Race Predictor](#) · [GitHub](#)
Predecessor ML model for F1 race outcome prediction — the foundation the Strategy Engine is built on.

- 86.18% ROC AUC across multi-season temporal validation
- 57 features from 1,177 race records including qualifying delta, constructor momentum, driver win rate, and circuit-specific historical performance
- Automated data ingestion via OpenF1 API with incremental retraining

**Stack:** Python · Scikit-learn · XGBoost · OpenF1 API

---

## Research

**"A Novel Parallel Recurrent Fusion Network for Stock Market Forecasting"**
*International Conference on Sustainable Computing and Data Science (ICSCDS), 2025*
Proposed a parallel recurrent fusion architecture combining multiple RNN variants for improved time-series forecasting accuracy on financial data.

---

## Tech Stack

| Layer | Technologies |
|---|---|
| Languages | Python · TypeScript · JavaScript · SQL · C++ |
| AI / ML | LangChain · LangGraph · CrewAI · AgnoAI · FAISS · Qdrant · Gemini |
| Backend | FastAPI · Node.js · REST APIs · WebSockets |
| Frontend | React · React Native · Tauri |
| Databases | PostgreSQL · MongoDB · Redis · SQLite |
| Infrastructure | Docker · Kubernetes · GitHub Actions · Prometheus · Grafana |
| Platforms | Vercel · Render · AWS |

---

## Achievements

- 🥇 Rank 1 / 134 — AI & Data Science Department, Semester VI (10/10 GPA)
- 📄 Published researcher — ICSCDS 2025
- 💻 500+ DSA problems solved on LeetCode
