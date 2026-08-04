# Jiany Samara

**Computer Science @ AUB · Machine Learning Research · Probabilistic Modeling · Systems**

I am a Computer Science student at the American University of Beirut, ranked **1st out of 152** and selected as a **President’s Merit Scholar**.

My work spans machine learning research, probabilistic forecasting, and systems engineering. I am particularly interested in building reproducible, end-to-end systems—from data processing and model evaluation to APIs, storage, testing, and deployment.

## Research

* **Human–robot collaboration:** Research assistant at AUB working on physiological modeling, cognitive digital twins, and adaptive human–robot systems.
* **EC3 2026:** Co-authored a conference paper on role-aware human–robot collaboration in 3D concrete printing, proposing a Human–Robot–Site taxonomy and predictive digital twin framework.
* **Current FYP:** Developing a cost-aware decision policy for biomedical question answering that learns when an LLM should answer directly, retrieve evidence, verify its response, or abstain.

## Selected Projects

### [Personalized Human-State Forecasting for Human–Robot Collaboration](https://github.com/Jiany-S/twin-psych-risk-model)

Physiological modeling and multi-rate supervisory replay for human–robot collaboration research.

* Built held-out-subject stress modeling pipelines on WESAD, reaching **AUROC 0.768 across 11,988 evaluation windows**
* Implemented personalized calibration using subject-specific baseline segments
* Developed fast current-state detection and multi-horizon forecasting pipelines
* Designed a timestamp-driven replay architecture separating physiological recommendations from deterministic physical-safety rules

**Technologies:** Python, PyTorch, XGBoost, Temporal Fusion Transformers, physiological signal processing

---

### [FIFA World Cup 2026 Forecasting](https://github.com/Jiany-S/WorldCup_ML)

A leakage-safe probabilistic forecasting toolkit for the official 48-team tournament format.

* Built regularized Poisson goal models with team attack and defense effects
* Engineered temporal-form, team-strength, squad-quality, rating, and optional event/xG features
* Processed **460K+ raw football rows**, including match, lineup, pressure, and player-level records
* Added chronological backtests, calibration diagnostics, stage probabilities, and **100K Monte Carlo tournament simulations**

**Technologies:** Python, pandas, scikit-learn, XGBoost, probabilistic modeling, Monte Carlo simulation

---

### [Inflation Nowcasting with Machine Learning](https://github.com/Jiany-S/Inflation-Nowcast)

Next-month U.S. CPI inflation forecasting using leakage-safe macroeconomic features.

* Built a reproducible pipeline using monthly FRED economic data
* Benchmarked naive models, ARIMA, Ridge, Lasso, XGBoost, and LSTM architectures
* Achieved the best held-out performance with XGBoost: **MAE 0.158, sMAPE 5.73, MASE 0.547**
* Added rolling backtests, uncertainty intervals, feature importance, ablations, and automated reports

**Technologies:** Python, TensorFlow, XGBoost, scikit-learn, FRED, time-series modeling

---

### [Willing — AI Volunteer Matching Platform](https://github.com/Jiany-S/willing)

A civic-technology platform connecting volunteers with NGOs and community opportunities.

* Founded and developed a searchable volunteer-opportunity platform
* Built semantic recommendation pipelines using OpenAI embeddings
* Represented users and opportunities as vectors for similarity-based matching
* Developed a full-stack application with typed APIs, authentication, validation, and PostgreSQL storage

**Technologies:** TypeScript, React, Node.js, Express, PostgreSQL, pgvector, OpenAI embeddings, Docker

---

### [Java Blockchain Node](https://github.com/Jiany-S/java-blockchain)

An account-based Proof-of-Work blockchain node built around deterministic state management and persistent storage.

* Implemented transactions, mining, wallet management, Merkle-root validation, and cumulative-work fork choice
* Added RocksDB-backed persistence and deterministic chain replay
* Built Netty-based peer-to-peer networking with heartbeats and peer eviction
* Exposed authenticated REST/RPC APIs and Prometheus-compatible metrics
* Automated testing, release artifacts, and Docker publishing with GitHub Actions

**Technologies:** Java, Netty, RocksDB, Gradle, Docker, REST/RPC, Prometheus

## Technical Toolkit

**Languages:** Python, Java, TypeScript, JavaScript, C, SQL
**Machine Learning:** PyTorch, TensorFlow, scikit-learn, XGBoost, Hugging Face Transformers
**Data and Infrastructure:** PostgreSQL, pgvector, Redis, RocksDB, Docker, Linux
**Engineering:** REST/RPC APIs, GitHub Actions, CI/CD, testing, reproducible experimentation

## Connect

[LinkedIn](https://www.linkedin.com/in/jianysamara) · [Email](mailto:jianysamara@gmail.com)
