<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                        C O L A C B R R                       ║
║           · Digital alchemist / bug exorcist ·               ║
║   Python · FastAPI · AI/ML · Full-Stack · MLOps · GCP        ║
╚══════════════════════════════════════════════════════════════╝
```

**Backend-leaning software engineer building applied AI/RAG systems, full-stack prototypes, and integration-heavy products.**

`Python` · `FastAPI` · `React` · `Docker` · `RAG` · `MLOps` · `GCP`

[![GitHub followers](https://img.shields.io/github/followers/colacbrr?style=flat&label=followers)](https://github.com/colacbrr)
[![GitHub stars](https://img.shields.io/github/stars/colacbrr?affiliations=OWNER&style=flat&label=stars)](https://github.com/colacbrr?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-cristiancolacel-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristiancolacel)
[![Location](https://img.shields.io/badge/location-Bucharest%2C%20Romania-555?style=flat&logo=googlemaps&logoColor=white)](https://github.com/colacbrr)
[![Status](https://img.shields.io/badge/status-open%20to%20opportunities-2ea043?style=flat)](https://www.linkedin.com/in/cristiancolacel)

</div>

---

## About

Hey. I'm **Cristian-Adrian Colăcel**, a software engineer from Bucharest currently finishing a **Master's in Information Systems at POLITEHNICA Bucharest**.

I build backend-heavy, product-shaped systems that work end-to-end: **Python/FastAPI APIs**, **applied AI and retrieval pipelines**, **full-stack dashboards**, and infrastructure that can actually run, be tested, and be debugged locally. My strongest direction is **systems and integration engineering**, with a growing focus on **applied AI/ML engineering**, retrieval systems, model serving, MLOps workflows, and cloud-native architecture.

---

## Proof Points

- Built 4 public end-to-end systems spanning RAG, full-stack platforms, ML inference, and scientific benchmarking.
- Measured retrieval benchmarks: ~6.9 ms average search latency, Recall@10 0.88 on 1k images.
- Delivered production-adjacent experience in Django web development and cross-platform QA.

---

## Role Fit

I am best matched with backend, AI/ML engineering, data engineering, and internal-tool roles where the work involves APIs, retrieval pipelines, model-serving workflows, automation, or service integration.

---

## Experience

<br>

**Web Development Intern · ImpexRegio** &nbsp;|&nbsp; *June – September 2024, Bucharest*

Built Django backend features and SQL integrations for production website workflows. Delivered responsive frontend components connecting user-facing pages with backend functionality. Supported database design, query updates, debugging, and testing for full-stack web features. Managed GitHub branches and followed version-control workflows with the team.

Helped accelerate recurring website deliverables by approximately 5 days through coordinated task tracking, Git collaboration, and focused debugging support.

<br>

**QA Game Tester · EA Games** &nbsp;|&nbsp; *June – December 2022, Bucharest*  
*Dragon Age: The Veilguard (pre-release) · PC · PlayStation · Xbox*

Executed functional, regression, and compatibility testing across three platforms during the production cycle. Identified, reproduced, documented, and tracked defects with clear reproduction steps and severity context in Jira. Supported build implementation, version tracking, and release workflows through Azure DevOps.

---

## Education

| Degree | Institution | Period | Focus |
|---|---|---|---|
| M.Sc. Information Systems | POLITEHNICA Bucharest | 2025 – present | Retrieval systems, MLOps, cloud-native architecture, applied AI |
| B.Eng. Computers and Information Technology | POLITEHNICA Bucharest | 2020 – 2025 | Software engineering, embedded systems, databases, AI/ML |

---

## Tech Stack

<br>

**Backend / APIs**  
`Python` `FastAPI` `Django` `Django REST Framework` `Flask` `Pydantic` `SQLAlchemy` `Alembic` `REST APIs` `WebSockets`

**Frontend / Product**  
`React` `TypeScript` `JavaScript` `Next.js` `Vite` `SvelteKit` `Tailwind CSS` `Recharts` `D3.js` `Flutter / Dart`

**AI / ML / Data**  
`PyTorch` `TensorFlow` `scikit-learn` `FAISS` `CLIP` `RAG` `MLflow` `Ollama` `Pandas` `NumPy` `SciPy` `OpenCV` `Numba`

**Databases / Storage**  
`PostgreSQL` `SQL` `YugabyteDB` `SQLite` `Supabase` `MinIO` `Row Level Security`

**Infra / DevOps**  
`Docker` `Docker Compose` `Nginx` `Linux` `Git` `GitHub` `systemd` `Bash`

**Cloud / GCP**  
`Vertex AI` `Vertex AI Studio` `BigQuery` `Compute Engine` `APIs Explorer`

**Hardware / Embedded**  
`ESP32` `Raspberry Pi 5` `IoT telemetry` `Sensor pipelines` `Servo motors` `Signal processing`

**Familiar / Academic**  
`Go` `C/C++` `C#` `Assembly` `R`

---

## Bachelor Thesis

<br>

### Smart Solar Tracking System with Adaptive Energy Management

**What it is:** Full-stack IoT and ML system for adaptive solar tracking, telemetry, forecasting, and dashboard monitoring.

**Why it matters:** It connects real hardware, embedded control, backend storage, live visualization, and ML forecasting into one working vertical slice.

**Highlights**
- Built dual-axis servo tracking with LDR arrays on ESP32, plus weather-protection logic for rain and vibration events.
- Streamed voltage, current, battery state, temperature, humidity, rain, and vibration telemetry to a Raspberry Pi 5 backend.
- Used Django, PostgreSQL, WebSockets, D3.js dashboards, and LSTM-based solar irradiance forecasting for next-day production estimation.

**Stack:** `ESP32` `Raspberry Pi 5` `Django` `PostgreSQL` `D3.js` `WebSockets` `LSTM` `INA3221` `DHT22` `SG90 servos`

---

## Featured Projects

<br>

### [Multimedia Information Retrieval (RAG)](https://github.com/colacbrr/Multimedia-Information-Retrieval-RAG)

**What it is:** Local-first semantic search over images and video using CLIP embeddings, FAISS indexes, FastAPI APIs, and a React interface.

**Why it matters:** It demonstrates a complete applied retrieval pipeline with multimodal indexing, reranking, explainability, and measurable retrieval quality.

**Highlights**
- Combined text, image, frame, and video retrieval with separate modality indexes and timestamped best-frame metadata.
- Added caption-aware reranking, Ollama-generated grounded explanations, prompt versioning, explanation caching, and Recall@K benchmarking.
- Measured ~6.9 ms average retrieval latency, Recall@10 of 0.88 on a 1k-image run, and Recall@10 of 0.57 on a 5k-image run.

**Stack:** `FastAPI` `React` `PyTorch` `FAISS` `CLIP` `Ollama` `OpenCV`

<br>

### [StartStack Platform](https://github.com/colacbrr/Startstack-Platform)

**What it is:** Full-stack e-startup and template marketplace with separate public, client, and staff workflows.

**Why it matters:** It models a realistic product backend with authentication, RBAC, transactional business flows, object storage, and operational automation.

**Highlights**
- Built cookie-based sessions, RBAC, login audit events, and optional 2FA model support across separate user flows.
- Wired checkout into a transactional sequence covering client profile, order, invoice, project, template assignment, site version, and template license.
- Used YugabyteDB for distributed SQL, MinIO for signed URL delivery, and Makefile automation for startup, reset, smoke testing, health checks, and reports.

**Stack:** `FastAPI` `React` `TypeScript` `YugabyteDB` `MinIO` `Docker Compose` `Nginx` `SQLAlchemy` `Alembic`

<br>

### [Real-Time Emotion Recognition Platform](https://github.com/colacbrr/Real-Time-Emotion-Recognition-Platform)

**What it is:** Applied ML platform for facial emotion recognition with training, comparison, and live inference workflows.

**Why it matters:** It turns model experimentation into a product-shaped system where multiple approaches can be compared through APIs and a dashboard.

**Highlights**
- Implemented classical baselines with HOG/LBP + SVM alongside deep learning models such as ResNet and EfficientNet.
- Exposed training, validation, model comparison, submission generation, and live inference through FastAPI endpoints.
- Built a React dashboard where model comparison is part of the product, not just a set of offline scripts.

**Stack:** `FastAPI` `React` `PyTorch` `ResNet` `EfficientNet` `SVM` `OpenCV`

<br>

### [Reaction-Diffusion Benchmark](https://github.com/colacbrr/Reaction-Diffusion-Benchmark)

**What it is:** Scientific Python CPU benchmark comparing vectorized NumPy and parallel Numba backends for a 2D FitzHugh-Nagumo simulation.

**Why it matters:** It shows practical Python performance engineering: measuring when vectorization is enough and when JIT parallelism is worth the warm-up cost.

**Highlights**
- Benchmarked both backends with identical equations, initial state, grid sizes, and iteration counts.
- Reported timing, ms/iteration, ns/cell/iteration, mean/max absolute error, speedup ratios, and paired t-test results.
- Packaged the workflow as a configurable CLI for reproducible simulation and benchmark runs.

**Stack:** `NumPy` `Numba` `SciPy` `Matplotlib` `CLI`

---

## Other Builds

Product-oriented experiments and supporting projects. Actual usable software.

| Project | What it does | Stack |
|---|---|---|
| [Mall Customer Segmentation](https://github.com/colacbrr/Mall-Customer-Segmentation) | Python + R segmentation project with aligned PCA + K-Means workflows, report generation, and a FastAPI + React automation layer | Python · R · scikit-learn · FastAPI · React · nbconvert · RMarkdown |
| MLflow Model Lifecycle *(private)* | End-to-end MLflow workflow covering experiment tracking, model registry, aliases, local inference, and served prediction requests | Python · MLflow · scikit-learn · SQLite |
| YouTube Transcript Pipeline *(private)* | CLI pipeline for scraping, normalization, deduplication, dataset assembly, TF-IDF baseline, and BiLSTM training | Python · Playwright · scikit-learn · TensorFlow/Keras · LSTM · Pandas |
| [InvestSim](https://github.com/colacbrr/InvestSim) | Browser-based personal finance simulator for compounding, contributions, inflation-adjusted value, withdrawals, IRR, scenarios, charts, and CSV export | Next.js · TypeScript · Tailwind · Recharts |
| [CV & Cover Letter Generator](https://github.com/colacbrr/CV-CoverLetter-Generator) | Profile-driven CLI that generates ATS-optimized CV and cover letter packages from raw job offers and grounded profile facts | Python · LaTeX · pdflatex · Markdown parsing · CLI |
| [Remote-Terminal](https://github.com/colacbrr/Remote-Terminal) | Phone-to-Linux remote access workflow using Tailscale, SSH, tmux, service-state restoration, and operator dashboards | Linux · Bash · Tailscale · SSH · tmux · systemd · Python |
| Audio Analysis Platform | Real-time audio capture, streaming, FFT analysis, filtering, and live dashboard across hardware and browser | ESP32 · FastAPI · WebSockets · React |
| WardrobeApp | Wardrobe management with authenticated collection CRUD, private image storage, signed URLs, and outfit scaffolding | Next.js · Supabase · RLS · TypeScript |
| LeafPad | Windows-first offline PDF reader with progress persistence, bookmarks, rotation, zoom, and touch-friendly navigation | Electron · React · PDF.js · TypeScript |
| VocabMaster | Vocabulary learning mobile app with flashcard review, retention tracking, and study feedback | Flutter · Dart |
| Simple Daily Quotes | Flutter app with backend-connected quote fetching, ETag caching, offline fallback, and daily notifications | Flutter · Dart · SharedPreferences |
| Admitere Academia de Politie | Romanian Police Academy admission-prep platform with study content, quizzes, PDF viewing, and gamification | FastAPI · SvelteKit |

---

## Cloud / GCP

Currently working through **Google Cloud Skills Boost**, focused on certification preparation and hands-on labs around data engineering, cloud infrastructure, BigQuery, Vertex AI, load balancing, and RAG workflows. I am using these labs to build evidence toward deployable cloud projects, not presenting them as production cloud experience.

**Completed · 100% assessment scores**

| Lab / Course | Status |
|---|---|
| A Tour of Google Cloud Hands-on Labs | ✓ |
| APIs Explorer: Qwik Start | ✓ |
| Get Started with Vertex AI Studio | ✓ |
| Generative AI with Vertex AI: Prompt Design | ✓ |
| Navigate BigQuery | ✓ |
| Introduction to Generative AI | ✓ |
| Introduction to Large Language Models | ✓ |
| Introduction to Responsible AI | ✓ |
| Introduction to Data Analytics in Google Cloud | ✓ |

**In progress**

| Course / Path | Status |
|---|---|
| Preparing for your Professional Data Engineer Journey | In progress |
| Preparing for your Associate Cloud Engineer Journey | In progress |
| Create Embeddings, Vector Search, and RAG with BigQuery | In progress |
| Implementing Cloud Load Balancing for Compute Engine | In progress |
| Prompt Design in Vertex AI | In progress |
| Data Management and Storage in the Cloud | In progress |

**Targets:** `Google Cloud Professional Data Engineer` · `Google Cloud Associate Cloud Engineer`

---

## Languages

<br>

![Romanian](https://img.shields.io/badge/Romanian-Native-2ea043?style=flat)
![English](https://img.shields.io/badge/English-C1%2FC2-0A66C2?style=flat)
![German](https://img.shields.io/badge/German-A1%2FA2-555?style=flat)

---

## Notes

I prefer real projects, readable code, measured benchmarks, and boring infrastructure that works.

```
Commit small.
Document the ritual.
Never trust a green build you didn't actually read.
```

## Find Me

- **LinkedIn:** [linkedin.com/in/cristiancolacel](https://www.linkedin.com/in/cristiancolacel)
- **For role-specific CVs or project details:** reach me on LinkedIn
- **Location:** Bucharest, Romania
- **Open to:** early-career / graduate / internship roles in backend, AI/ML, systems integration, full-stack, or data engineering
