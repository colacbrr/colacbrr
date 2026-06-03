<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                        C O L A C B R R                       ║
║           · Digital alchemist / bug exorcist ·               ║
║   Python · FastAPI · AI/ML · Full-Stack · MLOps · GCP        ║
╚══════════════════════════════════════════════════════════════╝
```

[![GitHub followers](https://img.shields.io/github/followers/colacbrr?style=flat&label=followers)](https://github.com/colacbrr)
[![GitHub stars](https://img.shields.io/github/stars/colacbrr?affiliations=OWNER&style=flat&label=stars)](https://github.com/colacbrr?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-cristiancolacel-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristiancolacel)
[![Location](https://img.shields.io/badge/location-Bucharest%2C%20Romania-555?style=flat&logo=googlemaps&logoColor=white)](https://github.com/colacbrr)
[![Status](https://img.shields.io/badge/status-open%20to%20opportunities-2ea043?style=flat)](https://www.linkedin.com/in/cristiancolacel)

</div>

---

## 🧙 About

I'm **Cristian-Adrian Colăcel** — a junior software engineer from Bucharest, currently finishing a **Master's in Information Systems at POLITEHNICA Bucharest**.

I build backend-heavy, product-shaped things that actually work end-to-end. My focus sits at the intersection of **Python/FastAPI systems**, **applied AI and retrieval**, and **full-stack product prototypes** — the kind of stack where a well-designed API, a vector index, and a React dashboard all need to trust each other under the same Docker Compose file.

My strongest near-term direction is **systems and integration engineering**: understanding how components connect, learning tools fast, and debugging across backend, frontend, data, and infrastructure boundaries without getting lost. I also lean hard into **applied AI/ML engineering** — not research, but retrieval pipelines, model serving, MLOps workflows, and AI-backed products that run locally and behave predictably.

Lately: RAG pipelines, MLflow model lifecycle, cloud/data engineering on GCP, and "this should be a script before it becomes a life sentence" automation.

```javascript
const wiz = {
  handle:    "colacbrr",
  class:     ["Junior Software Engineer", "Python Backend", "AI/ML Projects"],
  location:  "Bucharest, Romania",
  status:    "open to opportunities",
  languages: ["Romanian (native)", "English (C1/C2)", "German (A2)"],

  currentlyCasting: [
    "local-first AI retrieval, vector search, and RAG pipelines",
    "FastAPI systems with production-shaped architecture",
    "MLOps: experiment tracking, model registry, model serving with MLflow",
    "Google Cloud → GCP Associate Cloud Engineer + Professional Data Engineer",
    "full-stack product prototypes that go end-to-end",
  ],

  primaryDirection:  "Systems & Integration Engineering",
  secondaryDirections: ["AI/ML Engineering", "Python Backend", "Cloud/Data"],

  creed: [
    "clarity over cleverness",
    "reliability over heroics",
    "ship small spells, iterate fast",
    "leave fewer cursed TODOs than you found",
  ],
};
```

---

## 📜 Spellbook

**Backend / APIs**
`Python` · `FastAPI` · `Django` · `Django REST Framework` · `Flask` · `REST APIs` · `Pydantic` · `SQLAlchemy` · `Alembic` · `WebSockets` · `Makefile automation`

**Other Languages**
`Go` · `C/C++` · `C#` · `Assembly` · `R`

**Frontend / Product UI**
`React` · `TypeScript` · `JavaScript` · `Next.js` · `Vite` · `SvelteKit` · `Tailwind CSS` · `Recharts` · `Radix UI` · `D3.js` · `Flutter / Dart`

**AI / ML / Data**
`PyTorch` · `TensorFlow` · `scikit-learn` · `FAISS` · `CLIP` · `RAG` · `MLflow` · `Ollama` · `NLP` · `Computer Vision` · `LSTM` · `Pandas` · `NumPy` · `SciPy` · `OpenCV` · `Numba` · `FFT`

**Databases / Storage**
`PostgreSQL` · `SQL` · `YugabyteDB` · `SQLite` · `MySQL` · `Supabase` · `MinIO` · `Object Storage` · `Row Level Security`

**Infra / DevOps**
`Docker` · `Docker Compose` · `Nginx` · `Git` · `GitHub` · `Linux` · `systemd` · `Bash scripting` · `CI/CD pipelines`

**Cloud / GCP**
`Vertex AI` · `Vertex AI Studio` · `BigQuery` · `Compute Engine` · `GCP Fundamentals` · `APIs Explorer`

**Hardware / Embedded / Real-Time**
`ESP32` · `Raspberry Pi 5` · `IoT telemetry` · `Sensor pipelines` · `Servo motors` · `Signal processing`

---

## 🧪 Projects

> Full source, docs, and setup instructions are in each repo. Benchmark numbers are real and reproducible.

---

### 🔍 [Multimedia Information Retrieval (RAG)](https://github.com/colacbrr/Multimedia-Information-Retrieval-RAG)

**Local-first semantic search over images and video — no cloud API dependencies.**

Combines CLIP text/image/frame embeddings with FAISS nearest-neighbour indexing (flat and HNSW), caption-aware reranking, and Ollama-generated grounded explanations for each result. Extended from image retrieval into full video retrieval: OpenCV ingestion, frame sampling, pooled video-level embeddings, timestamped best-frame metadata, and separate indexes per modality.

- **Why it's interesting:** this is a full retrieval pipeline, not a notebook. Multimodal inputs, reranking that separates semantic similarity from final ranking, prompt versioning, explanation caching, and Recall@K benchmarking all wired together and exposed through APIs.
- **Benchmark results:** ~6.9 ms average retrieval latency, Recall@10 ≈ 0.88 on 1k-image run, Recall@10 ≈ 0.57 on 5k-image run.
- **Stack:** `FastAPI` · `React` · `PyTorch` · `FAISS` · `CLIP` · `Ollama` · `OpenCV`

---

### 🏗️ [StartStack Platform](https://github.com/colacbrr/Startstack-Platform)

**Full-stack e-startup and template marketplace with real production-shaped architecture.**

Separate public, client, and staff user flows with RBAC, cookie-based sessions, login audit events, and optional 2FA model support. YugabyteDB (YSQL) for distributed SQL with ACID-aware transaction design; MinIO for S3-compatible object storage with signed URL delivery. Checkout flow wires together client profile, order, invoice, project, template assignment, site version, and template license in one transactional sequence.

- **Why it's interesting:** not a CRUD demo. A normalized multi-entity relational schema, multi-role auth, object storage, reverse-proxy config, distributed DB demo design, and a full Makefile automation layer for startup, reset, smoke testing, health checks, and report generation.
- **Stack:** `FastAPI` · `React` · `TypeScript` · `YugabyteDB` · `MinIO` · `Docker Compose` · `Nginx` · `SQLAlchemy` · `Alembic`

---

### 🎭 [Real-Time Emotion Recognition Platform](https://github.com/colacbrr/Real-Time-Emotion-Recognition-Platform)

**Applied ML demo for facial emotion recognition with multi-model comparison.**

Implements both classical baselines (HOG/LBP features + SVM) and deep learning approaches (ResNet, EfficientNet families) in the same product. Training, validation, model comparison, submission generation, and live inference all exposed through FastAPI endpoints and a React dashboard — not just notebooks.

- **Why it's interesting:** multi-model comparison is built into the product itself, not just the training scripts. The inference backend feeds directly into a usable frontend interaction layer.
- **Stack:** `FastAPI` · `React` · `PyTorch` · `ResNet` · `EfficientNet` · `SVM` · `OpenCV`

---

### ⚗️ [Reaction-Diffusion Benchmark](https://github.com/colacbrr/Reaction-Diffusion-Benchmark)

**Scientific Python CPU benchmark: vectorized NumPy vs parallel Numba.**

Implements a 2D FitzHugh-Nagumo reaction-diffusion simulation and benchmarks both backends with the same equations, same initial state, and same iteration counts. Outputs timing, ms/iteration, ns/cell/iteration, mean/max absolute error, speedup ratios, and paired t-test results across configurable grid sizes via CLI.

- **Why it's interesting:** demonstrates practical Python performance engineering — when vectorisation is enough and when JIT + parallelism is worth the warm-up cost. All numbers are real and reproducible from the CLI.
- **Stack:** `NumPy` · `Numba` · `SciPy` · `Matplotlib` · `CLI`

---

### 📊 [Mall Customer Segmentation](https://github.com/colacbrr/Mall-Customer-Segmentation)

**Python + R segmentation project with reproducible automation and interactive dashboard.**

Two parallel analytical pipelines (Python and R) with aligned PCA + K-Means workflows, HTML report generation via nbconvert/RMarkdown, and a FastAPI + React automation layer that executes notebooks, stores outputs, and exposes execution metrics per pipeline stage.

- **Benchmark results:** silhouette score ≈ 0.3904 (Python) / 0.3878 (R); first two PCA components explain ≈ 59.9% of variance.
- **Stack:** `Python` · `R` · `scikit-learn` · `FastAPI` · `React` · `nbconvert` · `RMarkdown`

---

### 🔁 MLflow Model Lifecycle *(local MLOps practice)*

**Full MLflow workflow from training to experiment tracking, registry, aliasing, and model serving.**

Built to practice MLOps concepts that shallow tutorials skip: a running `mlflow server` with SQLite backend store, artifact logging (parameters, metrics, confusion matrix, model signatures), registered model versions, production/staging aliases, local inference from registry, and REST-style served prediction requests. Random Forest on Iris as the controlled experiment vehicle.

- **Why it matters:** demonstrates practical MLOps process understanding — not just calling `mlflow.log_metric()`, but the full lifecycle from run comparison to production promotion to serving.
- **Stack:** `Python` · `MLflow` · `scikit-learn` · `SQLite`

---

### 🗣️ YouTube Transcript Pipeline *(NLP + data engineering)*

**End-to-end CLI pipeline: scraping → corpus engineering → NLP classification experiments.**

Playwright-based scraping with headless mode, ETag caching, retry/resume logic, and polite pacing. Staged CLI subcommands for scraping, normalization, deduplication, dataset assembly, TF-IDF + Logistic Regression baseline, and BiLSTM training. Outputs accuracy, macro F1, classification reports, confusion matrices, and timestamped JSON/CSV artifacts.

- **Stack:** `Python` · `Playwright` · `scikit-learn` · `TF-IDF` · `TensorFlow/Keras` · `LSTM` · `pandas`

---

### 💰 [InvestSim](https://github.com/colacbrr/InvestSim)

**Browser-based personal-finance simulator for investment planning and scenario comparison.**

Monthly/annual/daily compounding, contribution step-up, inflation-adjusted real value, withdrawal-tax handling, cumulative gains, and annualized IRR — all client-side. Multiple Recharts visualization modes, scenario saving/comparison, and CSV export. No backend; no accounts.

- **Stack:** `Next.js` · `TypeScript` · `Tailwind` · `Recharts`

---

### 📄 [CV & Cover Letter Generator](https://github.com/colacbrr/CV-CoverLetter-Generator)

**Profile-driven CLI tool that generates ATS-optimised CV and cover letter packages from raw job offers.**

Reads a Markdown profile knowledge base, raw job offer files, domain direction notes, and LaTeX template manifests. Outputs per-application folders containing tailored `.tex` sources, compiled PDFs, tailoring notes, follow-up questions, and generation summaries. Heuristic parsing handles English and Romanian offers; project ranking and stack ordering are driven by role/domain scoring against the profile.

- **Why it's interesting:** this README was partially generated by it. All claims stay grounded to profile facts — no hallucinated experience.
- **Stack:** `Python` · `LaTeX` · `pdflatex` · `Markdown parsing` · `CLI`

---

### 🔌 [Remote-Terminal](https://github.com/colacbrr/Remote-Terminal)

**Runbook and automation toolkit for phone-to-Linux remote access through Tailscale + SSH + tmux.**

Documents and automates a reproducible setup including a reversible server-mode workflow that records current service state, ensures Tailscale and SSH are running, applies suspend-prevention policy, and restores previous state on exit. Operator interfaces via whiptail menu, terminal dashboard, Python web control panel, and Tailscale Serve helpers.

- **Stack:** `Linux` · `Bash` · `Tailscale` · `SSH` · `tmux` · `systemd` · `Python`

---

### 📱 Consumer Product Experiments

A collection of smaller product-oriented builds — not research demos, actual usable software:

| Project | What it does | Stack |
|---|---|---|
| **WardrobeApp** | Wardrobe management with authenticated collection CRUD, private image storage, signed URLs, and outfit scaffolding | Next.js · Supabase · RLS · TypeScript |
| **LeafPad** | Windows-first offline PDF reader with progress persistence, bookmarks, rotation, zoom, and touch-friendly nav | Electron · React · PDF.js · TypeScript |
| **VocabMaster** | Vocabulary learning mobile app with flashcard review, retention tracking, and study feedback | Flutter · Dart |
| **Simple Daily Quotes** | Flutter app with backend-connected quote fetching, ETag caching, offline fallback, daily notifications, and Provider state | Flutter · Dart · SharedPreferences |
| **Admitere Academia de Politie** | Romanian Police Academy admission-prep platform with study content, quizzes, PDF viewing, and gamification | FastAPI · SvelteKit |
| **Audio Analysis Platform** | Real-time audio capture, FFT analysis, filtering, and live dashboard | ESP32 · FastAPI · WebSockets · React |

---

### ☀️ Smart Solar Tracking System *(Bachelor Thesis — Flagship Project)*

**Autonomous solar tracking + adaptive energy management + forecasting. End-to-end, physical world to web dashboard.**

Full vertical slice: dual-axis servo tracking driven by LDR arrays on an ESP32, sensor telemetry pipeline (voltage, current, battery state, temperature, humidity, rain, vibration) streamed to a Raspberry Pi 5 running a Django backend and PostgreSQL, visualised with D3.js dashboards, and LSTM-based solar irradiance forecasting for next-day production estimation. Weather-protection logic auto-retracts the panel on rain/vibration events.

- **Why it matters:** this is the hardest project in the portfolio to fake. Each layer — embedded firmware, IoT pipeline, time-series storage, ML forecasting, live dashboard — had to actually work for the others to mean anything. Real hardware, real sensors, real outdoor operation.
- **Stack:** `ESP32` · `Raspberry Pi 5` · `Django` · `PostgreSQL` · `D3.js` · `WebSockets` · `LSTM` · `INA3221` · `DHT22` · `SG90 servos`

---

## 🧰 Experience

**Web Development Intern · ImpexRegio** *(June – September 2024, Bucharest)*

Built Django backend features and SQL integrations for production website workflows. Delivered responsive frontend components connecting user-facing pages with backend functionality. Supported database design, query updates, debugging, and testing for full-stack web features. Managed GitHub branches, assisted with merges, and followed version-control workflows with the team.

→ Helped accelerate recurring website deliverables by approximately 5 days through coordinated task tracking, Git collaboration, and focused debugging support.

---

**QA Game Tester · EA Games** *(June – December 2022, Bucharest)*
*Dragon Age: The Veilguard — PC, PlayStation, Xbox*

Executed functional, regression, and compatibility testing across three platforms. Identified, reproduced, documented, and tracked defects with clear reproduction steps and severity context in Jira. Supported build implementation, version tracking, and release workflows through Azure DevOps. Collaborated with development and production teams on issue resolution and release quality.

---

## 🎓 Education

**M.Sc. Information Systems** · POLITEHNICA Bucharest · *2025 – present*
Focus: retrieval systems, MLOps, cloud-native architecture, applied AI.

**B.Eng. Computers and Information Technology** · POLITEHNICA Bucharest · *2020 – 2025*
Bachelor thesis: Smart Solar Tracking System with Adaptive Energy Management (ESP32 + Raspberry Pi + Django + LSTM).

---

## ☁️ Learning Arc

Currently grinding **Google Cloud Skills Boost** without pretending that watching one video made me a cloud architect.

**Completed (100% assessment scores)**
- Google Cloud Hands-on Labs Tour · APIs Explorer · Vertex AI Studio · Vertex AI Prompt Design · Navigate BigQuery
- Introduction to Generative AI · Introduction to Large Language Models · Introduction to Responsible AI
- Introduction to Data Analytics in Google Cloud

**In progress**
- `Preparing for your Professional Data Engineer Journey`
- `Preparing for your Associate Cloud Engineer Journey`
- `Create Embeddings, Vector Search, and RAG with BigQuery`
- `Implementing Cloud Load Balancing for Compute Engine`
- `Prompt Design in Vertex AI` · `Data Management and Storage in the Cloud`

**Target runes**
- `Google Cloud Professional Data Engineer` certification
- `Google Cloud Associate Cloud Engineer` certification
- Stronger `GitHub Actions`, cloud-native deployment, and observability evidence

No fake certificate flex. The forge is still hot.

---

## 🌐 Languages

| Language | Level |
|---|---|
| Romanian | Native |
| English | C1 / C2 (professional working proficiency) |
| German | A2 (elementary) |

---

## 🔮 Crystal Ball

```
[ORACLE FOG RISES]
Oracle glass cracks // ERROR
Third-party status cards replied:
"This user is blacklisted because the numbers offended the calibration altar."
```

So here are the boring badges instead. They usually behave.

<div align="center">

![Followers](https://img.shields.io/github/followers/colacbrr?style=flat)
![Stars](https://img.shields.io/github/stars/colacbrr?affiliations=OWNER&style=flat)
![Repos](https://img.shields.io/badge/repos-check%20the%20spellbook-black?style=flat&logo=github)

</div>

---

## 🧭 Find Me

- **GitHub:** [github.com/colacbrr](https://github.com/colacbrr)
- **LinkedIn:** [linkedin.com/in/cristiancolacel](https://www.linkedin.com/in/cristiancolacel)
- **Email:** ccolacel14@gmail.com
- **Location:** Bucharest, Romania
- **Status:** Open to junior / graduate / internship roles — backend, AI/ML, systems integration, full-stack, data engineering

```
Commit small.
Document the ritual.
Never trust a green build you didn't actually read.
```
