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

## About

Hey. I'm **Cristian-Adrian Colăcel**, a junior software engineer from Bucharest, currently finishing a **Master's in Information Systems at POLITEHNICA Bucharest**.

I build backend-heavy, product-shaped things that work end-to-end. My focus is **Python/FastAPI systems**, **applied AI and retrieval**, and **full-stack product prototypes**: the kind of stack where a well-designed API, a vector index, and a React dashboard all need to trust each other under the same Docker Compose file.

My strongest near-term direction is **systems and integration engineering**: understanding how components connect, learning tools fast, and debugging across backend, frontend, data, and infrastructure boundaries. I also lean into **applied AI/ML engineering**: retrieval pipelines, model serving, MLOps workflows, and AI-backed products that run locally and behave predictably.

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

<br>

**M.Sc. Information Systems** · POLITEHNICA Bucharest · *2025 – present*
Focus: retrieval systems, MLOps, cloud-native architecture, applied AI.

<br>

**B.Eng. Computers and Information Technology** · POLITEHNICA Bucharest · *2020 – 2025*
Bachelor thesis: Smart Solar Tracking System with Adaptive Energy Management (ESP32 + Raspberry Pi + Django + LSTM).

---

## Spellbook

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

Full vertical slice from physical hardware to web dashboard: dual-axis servo tracking driven by LDR arrays on an ESP32, sensor telemetry pipeline (voltage, current, battery state, temperature, humidity, rain, vibration) streamed to a Raspberry Pi 5 running a Django backend and PostgreSQL, visualised with D3.js dashboards, and LSTM-based solar irradiance forecasting for next-day production estimation. Weather-protection logic auto-retracts the panel on rain and vibration events.

Each layer (embedded firmware, IoT pipeline, time-series storage, ML forecasting, live dashboard) had to work for the others to mean anything. Real hardware, real sensors, real outdoor operation.

`ESP32` `Raspberry Pi 5` `Django` `PostgreSQL` `D3.js` `WebSockets` `LSTM` `INA3221` `DHT22` `SG90 servos`

---

## Projects

<br>

### [Multimedia Information Retrieval (RAG)](https://github.com/colacbrr/Multimedia-Information-Retrieval-RAG)

> Local-first semantic search over images and video. No cloud API dependencies.

Combines CLIP text/image/frame embeddings with FAISS nearest-neighbour indexing (flat and HNSW), caption-aware reranking, and Ollama-generated grounded explanations. Extended into full video retrieval: OpenCV ingestion, frame sampling, pooled video-level embeddings, timestamped best-frame metadata, and separate indexes per modality. A full retrieval pipeline with multimodal inputs, reranking that separates semantic similarity from final ranking, prompt versioning, explanation caching, and Recall@K benchmarking, all exposed through APIs.

**Benchmark:** ~6.9 ms average retrieval latency · Recall@10 of 0.88 on 1k-image run · Recall@10 of 0.57 on 5k-image run

`FastAPI` `React` `PyTorch` `FAISS` `CLIP` `Ollama` `OpenCV`

<br>

### [StartStack Platform](https://github.com/colacbrr/Startstack-Platform)

> Full-stack e-startup and template marketplace. Not a CRUD demo.

Separate public, client, and staff user flows with RBAC, cookie-based sessions, login audit events, and optional 2FA model support. YugabyteDB (YSQL) for distributed SQL with ACID-aware transaction design. MinIO for S3-compatible object storage with signed URL delivery. Checkout flow wires together client profile, order, invoice, project, template assignment, site version, and template license in one transactional sequence. Full Makefile automation layer for startup, reset, smoke testing, health checks, and report generation.

`FastAPI` `React` `TypeScript` `YugabyteDB` `MinIO` `Docker Compose` `Nginx` `SQLAlchemy` `Alembic`

<br>

### [Real-Time Emotion Recognition Platform](https://github.com/colacbrr/Real-Time-Emotion-Recognition-Platform)

> Applied ML demo for facial emotion recognition with multi-model comparison.

Implements classical baselines (HOG/LBP + SVM) and deep learning approaches (ResNet, EfficientNet) in the same product. Training, validation, model comparison, submission generation, and live inference exposed through FastAPI endpoints and a React dashboard. Multi-model comparison is built into the product itself, not just the training scripts.

`FastAPI` `React` `PyTorch` `ResNet` `EfficientNet` `SVM` `OpenCV`

<br>

### [Reaction-Diffusion Benchmark](https://github.com/colacbrr/Reaction-Diffusion-Benchmark)

> Scientific Python CPU benchmark: vectorized NumPy vs parallel Numba.

2D FitzHugh-Nagumo reaction-diffusion simulation benchmarked across both backends with identical equations, initial state, and iteration counts. Outputs timing, ms/iteration, ns/cell/iteration, mean/max absolute error, speedup ratios, and paired t-test results across configurable grid sizes via CLI. Demonstrates practical Python performance engineering: when vectorisation is enough and when JIT + parallelism is worth the warm-up cost.

`NumPy` `Numba` `SciPy` `Matplotlib` `CLI`

<br>

### [Mall Customer Segmentation](https://github.com/colacbrr/Mall-Customer-Segmentation)

> Python + R segmentation project with reproducible automation and interactive dashboard.

Two parallel analytical pipelines with aligned PCA + K-Means workflows, HTML report generation via nbconvert and RMarkdown, and a FastAPI + React automation layer that executes notebooks, stores outputs, and exposes execution metrics per pipeline stage.

**Benchmark:** silhouette score of 0.3904 (Python) / 0.3878 (R) · first two PCA components explain ~59.9% of variance

`Python` `R` `scikit-learn` `FastAPI` `React` `nbconvert` `RMarkdown`

<br>

### MLflow Model Lifecycle *(private)*

> Full MLflow workflow from training to experiment tracking, registry, aliasing, and serving.

Built to cover the MLOps concepts shallow tutorials skip: a running `mlflow server` with SQLite backend store, artifact logging (parameters, metrics, confusion matrix, model signatures), registered model versions, production/staging aliases, local inference from registry, and REST-style served prediction requests. Covers the full lifecycle from run comparison to production promotion to serving, not just `mlflow.log_metric()`.

`Python` `MLflow` `scikit-learn` `SQLite`

<br>

### YouTube Transcript Pipeline *(private)*

> End-to-end CLI pipeline: scraping to corpus engineering to NLP classification.

Playwright-based scraping with headless mode, ETag caching, retry/resume logic, and polite pacing. Staged CLI subcommands for scraping, normalization, deduplication, dataset assembly, TF-IDF + Logistic Regression baseline, and BiLSTM training. Outputs accuracy, macro F1, classification reports, confusion matrices, and timestamped JSON/CSV artifacts.

`Python` `Playwright` `scikit-learn` `TF-IDF` `TensorFlow/Keras` `LSTM` `Pandas`

<br>

### [InvestSim](https://github.com/colacbrr/InvestSim)

> Browser-based personal finance simulator for investment planning and scenario comparison.

Monthly/annual/daily compounding, contribution step-up, inflation-adjusted real value, withdrawal-tax handling, cumulative gains, and annualized IRR, all client-side. Multiple Recharts visualization modes, scenario saving and comparison, and CSV export.

`Next.js` `TypeScript` `Tailwind` `Recharts`

<br>

### [CV & Cover Letter Generator](https://github.com/colacbrr/CV-CoverLetter-Generator)

> Profile-driven CLI that generates ATS-optimised application packages from raw job offers.

Reads a Markdown profile knowledge base, job offer files, domain direction notes, and LaTeX template manifests. Outputs per-application folders with tailored `.tex` sources, compiled PDFs, tailoring notes, follow-up questions, and generation summaries. Heuristic parsing handles English and Romanian offers. Project ranking and stack ordering are driven by role/domain scoring against the profile. All generated claims stay grounded to source facts.

`Python` `LaTeX` `pdflatex` `Markdown parsing` `CLI`

<br>

### [Remote-Terminal](https://github.com/colacbrr/Remote-Terminal)

> Phone-to-Linux remote access through Tailscale, SSH, and tmux.

Reversible server-mode workflow that records current service state, ensures Tailscale and SSH are running, applies suspend-prevention policy, and restores previous state on exit. Operator interfaces via whiptail menu, terminal dashboard, Python web control panel, and Tailscale Serve helpers.

`Linux` `Bash` `Tailscale` `SSH` `tmux` `systemd` `Python`

<br>

### Smaller Builds

Product-oriented experiments. Actual usable software:

| Project | What it does | Stack |
|---|---|---|
| **Audio Analysis Platform** | Real-time audio capture, streaming, FFT analysis, filtering, and live dashboard across hardware and browser | ESP32 · FastAPI · WebSockets · React |
| **WardrobeApp** | Wardrobe management with authenticated collection CRUD, private image storage, signed URLs, and outfit scaffolding | Next.js · Supabase · RLS · TypeScript |
| **LeafPad** | Windows-first offline PDF reader with progress persistence, bookmarks, rotation, zoom, and touch-friendly nav | Electron · React · PDF.js · TypeScript |
| **VocabMaster** | Vocabulary learning mobile app with flashcard review, retention tracking, and study feedback | Flutter · Dart |
| **Simple Daily Quotes** | Flutter app with backend-connected quote fetching, ETag caching, offline fallback, and daily notifications | Flutter · Dart · SharedPreferences |
| **Admitere Academia de Politie** | Romanian Police Academy admission-prep platform with study content, quizzes, PDF viewing, and gamification | FastAPI · SvelteKit |

---

## Cloud / GCP

Currently working through **Google Cloud Skills Boost**, focused on certification preparation and hands-on labs.

<br>

**Completed · 100% assessment scores**

| Lab / Course | |
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

<br>

**In progress**

| Course / Path | Status |
|---|---|
| Preparing for your Professional Data Engineer Journey | In progress |
| Preparing for your Associate Cloud Engineer Journey | In progress |
| Create Embeddings, Vector Search, and RAG with BigQuery | In progress |
| Implementing Cloud Load Balancing for Compute Engine | In progress |
| Prompt Design in Vertex AI | In progress |
| Data Management and Storage in the Cloud | In progress |

<br>

**Targets:** `Google Cloud Professional Data Engineer` · `Google Cloud Associate Cloud Engineer`

No fake certificate flex. The forge is still hot.

---

## Languages

<br>

![Romanian](https://img.shields.io/badge/Romanian-Native-2ea043?style=flat)
![English](https://img.shields.io/badge/English-C1%2FC2-0A66C2?style=flat)
![German](https://img.shields.io/badge/German-A1%2FA2-555?style=flat)

---

## Crystal Ball

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

## Find Me

- **LinkedIn:** [linkedin.com/in/cristiancolacel](https://www.linkedin.com/in/cristiancolacel)
- **Location:** Bucharest, Romania
- **Open to:** junior / graduate / internship roles in backend, AI/ML, systems integration, full-stack, or data engineering

```
Commit small.
Document the ritual.
Never trust a green build you didn't actually read.
```
