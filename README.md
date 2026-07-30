<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=E8E8E8&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Vedula+Abhishek+%F0%9F%91%8B;AI+Engineer+in+Progress;Building+Production+ML+Systems;Data+Scientist+%7C+PyTorch+%7C+FastAPI">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=0A0A0A&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Vedula+Abhishek+%F0%9F%91%8B;AI+Engineer+in+Progress;Building+Production+ML+Systems;Data+Scientist+%7C+PyTorch+%7C+FastAPI" alt="Typing SVG" />
</picture>

</div>

---

### About Me

I'm a **Data Scientist at IPHIPI Technologies** (Google Client Project), based in Hyderabad. Mechanical Engineering graduate who pivoted hard into ML — I build production AI systems, real-time inference pipelines, and data-driven products.

- 🔭 Currently: Data Scientist @ IPHIPI Technologies (Google Client)
- 🛠️ Building: Real-time ML systems with PyTorch, FastAPI, and WebSockets
- 🎯 Goal: Shipping production AI that actually works at scale
- 📍 Based in: Hyderabad, India

---

### Skills

**AI / ML Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-8B0000?style=flat-square&logoColor=white)
![Machine Unlearning](https://img.shields.io/badge/Machine%20Unlearning-6A0DAD?style=flat-square&logoColor=white)
![Time Series](https://img.shields.io/badge/Time%20Series-2E8B57?style=flat-square&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-FF6F00?style=flat-square&logoColor=white)
![Model Calibration](https://img.shields.io/badge/Model%20Calibration-0077B6?style=flat-square&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6B6B?style=flat-square&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & Infrastructure**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### Featured Projects

#### 🏀 [NBA Live Win Probability](https://github.com/VedulaAbhishek10/nba-live-win-probability)
> Real-time NBA win probability — PyTorch MLP + isotonic calibration served over a FastAPI WebSocket, visualized in a live Streamlit dashboard. ~1,100 inferences/sec on CPU. ECE ≈ 0 after calibration.

**Stack:** `PyTorch` `FastAPI` `WebSockets` `Streamlit` `Docker` `scikit-learn` `nba_api`

- Trained 3 model families (LR, MLP, LSTM) with group-aware train/test splits to prevent data leakage
- Same `GameState` class drives both training and inference — zero training-serving skew by design
- Dockerized as a two-service compose stack (API + Dashboard) with health-checked startup ordering
- 19 unit tests, ~6s runtime, no external dependencies

---

#### 🧠 [Machine Unlearning on CIFAR-10](https://github.com/VedulaAbhishek10/machine-unlearning-cifar10)
> Benchmarks machine unlearning approaches on CIFAR-10 using a ResNet18 backbone. Compares Gradient Ascent Unlearning vs. Full Retraining baseline across Accuracy, RetainAcc, and ForgetAcc metrics.

**Stack:** `PyTorch` `ResNet18` `CIFAR-10` `Python`

- Implemented Gradient Ascent Unlearning — a selective forgetting method that doesn't require full retraining
- Benchmarked unlearning effectiveness with retain/forget accuracy splits

---

#### 💰 [Financial Research Assistant](https://github.com/VedulaAbhishek10/My-first-Rag-Fin-research-assistant-)
> RAG-based assistant that lets analysts query SEC filings and earnings reports in natural language, returning grounded answers with citations. Runs fully locally via Ollama — no API keys required.

**Stack:** `FastAPI` `Python` `Ollama` `ChromaDB` `sentence-transformers` `React` `TypeScript` `Docker`

- Hybrid search combining vector embeddings with BM25 keyword matching via Reciprocal Rank Fusion
- Auto-infers company, year, quarter, and document type from natural language queries
- Every answer cites source documents, page numbers, and relevance scores
- Token-by-token streaming responses over Server-Sent Events

---

### GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=VedulaAbhishek10&theme=github-dark-blue&hide_border=true">
  <img src="https://streak-stats.demolab.com?user=VedulaAbhishek10&theme=default&hide_border=true" alt="GitHub Streak" />
</picture>

</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=VedulaAbhishek10&theme=github-compact&hide_border=true">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VedulaAbhishek10&theme=minimal&hide_border=true" alt="Activity Graph" />
</picture>

</div>
