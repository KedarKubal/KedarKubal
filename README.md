<div align="center">

# Hi there, I'm Kedar Kubal! 👋

[![Kedar Kubal LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kedarkubal1/)
[![Kedar Kubal Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kedarkubal@yahoo.com)

**Master of Data Science Student | Software Engineer | Data Analyst**
Currently studying at RMIT University in Melbourne, Australia, with a background spanning enterprise software engineering, GPU-accelerated audio/ML pipelines, and applied statistics. Seeking opportunities to leverage Python, SQL, ETL engineering, and machine learning in production systems.

</div>

## 🚀 About Me

- 🔭 **Currently working on:** Data analysis and pipeline-engineering projects in machine learning and statistical modeling as part of my Master's program.
- 🌱 **Learning:** Advanced NLP techniques, database management, and deploying ML models in production.
- 👯 **Open to collaborate on:** Open-source data science tools, RAG systems, and data pipeline / feature-flag infrastructure.
- 💬 **Ask me about:** Hypothesis testing, Bayesian inference, ETL pipeline design, RAG systems, or Agile methodologies.
- 📫 **How to reach me:** Email at kedarkubal@yahoo.com or connect on LinkedIn.
- ⚡ **Fun fact:** Attended SciPy India 2019 and Techfest IIT Bombay workshops to fuel my tech curiosity.

<div align="center">

![Kedar Kubal's GitHub Stats](https://github-readme-stats.vercel.app/api?username=KedarKubal&show_icons=true&theme=radical&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=KedarKubal&layout=compact&theme=radical&hide_border=true)

</div>

## 👨‍💻 Featured Projects

Two monorepos wiring the same four services together in different shapes, plus each of the four underlying services as its own standalone project.

### 🔀 Pipeline Monorepo — Linear Four-Stage Data Pipeline
- Four independent services chained into one real, one-directional data flow: demo site → ETL → feature-flag service → live dashboard.
- Applied a **fail-open reads, fail-loud writes** philosophy — flag reads never crash a migration run, but a failed flag write is never silently swallowed.
- **Technologies:** Python, Node.js, Flutter, PostgreSQL, Docker Compose, ETL
- **[Repo Link](https://github.com/KedarKubal/pipeline-monorepo)** *(replace with actual repo if named differently)*

### 🕸️ Platform Monorepo — Control-Plane Architecture
- The same four services reframed around one seam: the feature-flag service as control plane, with its audit trail promoted to a first-class ETL data source.
- Split failure philosophy by path — runtime reads fail open, the audit ETL path fails loud so a lost audit batch is never silently reported as success.
- **Technologies:** Node.js, Express, Python, Flutter, Melos, PostgreSQL, Docker Compose
- **[Repo Link](https://github.com/KedarKubal/platform-monorepo)** *(replace with actual repo if named differently)*

### 🧪 Migration Platform — Python ETL Pipeline
- Legacy CSV/relational-DB data → normalized schema, with **quarantine-don't-crash** row validation and idempotent, dependency-ordered upserts.
- Pure-function transform layer enables a 19-test unit suite that runs in under a second with no database required.
- **Technologies:** Python, SQLAlchemy, Alembic, Pandas, PostgreSQL, Pytest
- **[Repo Link](https://github.com/KedarKubal/migration-platform)** *(replace with actual repo if named differently)*

### 🚦 Config Toggle Service — Feature Flag & Config Microservice
- Production-shaped Node.js/Express feature-flag service with a concurrency-safe write queue and write-to-temp-then-rename file persistence.
- 17 unit + integration tests (Jest + Supertest); multi-stage Dockerfile with non-root user and healthcheck.
- **Technologies:** Node.js, Express, Jest, Supertest, Docker
- **[Repo Link](https://github.com/KedarKubal/config-toggle-service)** *(replace with actual repo if named differently)*

### 📊 Adobe Analytics Implementation — E-commerce Tracking & Reporting
- Full measurement lifecycle for a fictional e-commerce site: tracking plan → data layer → Launch rules → processing rules/SAINT classifications → funnel reporting.
- Python Adobe Analytics 2.0 Reporting API client with a schema-accurate mock-mode fallback for running without live credentials.
- **Technologies:** JavaScript, Python, Adobe Analytics, Adobe Launch
- **[Repo Link](https://github.com/KedarKubal/adobe-analytics-demo)** *(replace with actual repo if named differently)*

### 🎨 Flutter DSM — Design System Component Library
- Tokens, components, golden-tested visual regression, and a Widgetbook catalog structured as an independently-publishable Melos monorepo.
- Live Widgetbook use case polls a feature-flag service to hot-switch component variants without a rebuild.
- **Technologies:** Flutter, Dart, Melos, Widgetbook, flutter_hooks
- **[Repo Link](https://github.com/KedarKubal/flutter-dsm)** *(replace with actual repo if named differently)*

## 🛠️ Skills & Tools

### Data Science & Analysis
- **Core Skills:** Statistical Modelling, Bayesian Inference, Time Series Analysis, Hypothesis Testing, Data Visualization
- **Tools:** Tableau, Power BI, Matplotlib, Seaborn, Google Analytics, Adobe Analytics

### Data & Backend Engineering
- **ETL & Pipelines:** Extract/Transform/Load Architecture, Data Validation & Quarantine Patterns, Idempotent Upserts, Event-Driven Data Flow
- **APIs & Services:** FastAPI, Node.js/Express, REST API Design, JWT Auth, Row-Level Security, SQLAlchemy, Alembic
- **AI/LLM:** RAG Pipelines, Text-to-SQL, pgvector Semantic Search, Speaker Diarisation, Emotion Classification

### Programming & Development
- **Languages:** Python, SQL, JavaScript/TypeScript, Dart, COBOL, CICS
- **Databases:** PostgreSQL, DB2, SQLite
- **Methodologies:** Agile/SAFe, Test-Driven Development, Code Review, Incident Management

### Product & Business
- **Management:** Product Discovery, Strategy, Jira, Financial Analysis, Stakeholder Communication
- **Other:** Ethical Hacking, Microsoft Office Suite

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

</div>

## 📊 Work Experience

- **Audio Pipeline Lead**
  Heya AI, Melbourne, Australia (Mar 2026 - Jun 2026)
  Engineered a GPU-accelerated audio intelligence pipeline (speaker diarisation, emotion classification) and a zero-hallucination RAG conversational interface grounded in verified SQL statistics; delivered a multi-tenant SaaS platform with row-level security, validated by a 647-test suite.

- **Data Analytics Trainee**
  MedTourEasy, Delhi (Remote) (Jan 2025)
  Applied Bayes' theorem and Bayesian probability modeling to test a well-known epidemiological claim against historical reporting-bias data.

- **Independent Travel Consultant**
  Dreamport, Dubai (Remote) (Feb 2024 - Mar 2024)
  Provided tailored travel recommendations and managed the end-to-end client lead pipeline.

- **Software Engineer**
  LTIMindtree (LTIM), Airoli, India (Dec 2021 - Jan 2024)
  Developed features for enterprise banking systems in COBOL/CICS/DB2 within a SAFe Agile framework; applied TDD and peer code review; provided incident monitoring and hotfix support for live insurance systems.

## 📚 Education

- **Master of Data Science**
  RMIT University, Melbourne, Australia (Mar 2025 - Present)
  *Coursework: Data Mining, Machine Learning, Statistical Modelling, Database Management*

- **Graduate Certificate in Business**
  La Trobe University, Bendigo, Australia (Jul 2024 - Nov 2024)

- **Management Consulting Nano Degree**
  Jobaaj, India (Apr 2024 - May 2024)

- **B.E. in Mechanical Engineering**
  University of Mumbai, India (Aug 2016 - Nov 2020)

## 🏆 Workshops & Conferences

- **SciPy India 2019** - IIT Bombay, Mumbai: Explored scientific Python applications.
- **Ethical Hacking Workshop** - Techfest, IIT Bombay (Dec 2018)
- **Data Science & Big Data Workshops** - Techfest IIT Bombay / Aegis (2017-2018)
- **Power BI Workshop** (Apr 2024)
- **Data Analytics with Tableau Specialisation** (Apr 2024)

## 🌍 Languages

- **Marathi** - Native
- **English** - C1 (Listening/Reading/Writing), B2 (Spoken)
- **Hindi** - B2 (All Skills)

---

<div align="center">

**Connect with me:**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kedarkubal1/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kedarkubal@yahoo.com)
📍 Melbourne, Australia

*Open to data science and data/backend engineering roles applying ML, analytics, and pipeline-engineering skills.*

</div>

![Footer](https://img.shields.io/badge/Built%20with-%F0%9F%8C%90%20%F0%9F%93%9A-brightgreen)
