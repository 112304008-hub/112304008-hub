# Yi Lun Fang (Ellen)

Undergraduate in Statistics, National Chengchi University (NCCU)  
Interested in quantitative investing, machine learning for financial markets, and building production-ready ML systems.

---

## Profile

- Background in **Finance** with solid training in **statistics and probability**
- Hands-on experience in **end-to-end ML projects**: data pipelines, model training, API serving, and Docker deployment
- Strong interest in **AI-themed equity investing**, especially the **AI server hardware and supply-chain ecosystem**
- Comfortable working across the stack: from **Python & data engineering** to **backend APIs** and **basic DevOps**
- Active in **campus life**: teaching member of the **NCCU Street Dance Club (熱舞社)**, responsible for choreography classes and mentoring junior members

---

## Current Focus

- Short-term stock return prediction models (classification, probability calibration, threshold design)
- Turning research code into **reliable services** (FastAPI, Docker, monitoring & auto-updates)
- Connecting **investment research** (AI server cycle, NVDA/TSMC/ODMs, cooling, etc.) with **systematic signals**

---

## Featured Project

### Fortune Ticker – AI-driven Short-Term Stock Prediction

> A production-style project that combines ML-based stock prediction with an interactive “fortune drawing” (籤筒) frontend.

- **Repository**: [new_project](https://github.com/112304008-hub/new_project)
- **Core ideas**:
  - Predicts next-day direction for selected equities using **technical and lagged features**
  - Wraps ML models in a **FastAPI** backend with clear, documented endpoints
  - Provides both **raw prediction APIs** and a **fortune-style experience** for users

- **Key components**:
  - Data layer: automatic creation of `{symbol}_short_term_with_lag3.csv` using `yfinance` and custom feature engineering  
  - ML layer: Random Forest / Logistic Regression models on short-horizon returns  
  - API layer: `/api/build_symbol`, `/api/predict`, `/api/draw` for different use cases  
  - Frontend: interactive “籤筒” UI consuming `/api/draw` and presenting model outputs as fortune slips  
  - Infra: Docker + Docker Compose, Caddy reverse proxy, basic production deployment on a remote host

This project is my main sandbox for experimenting with **research → model → productization**.

---

## Technical Skills

**Languages**  
- Python (data/ML/backend), R (statistics coursework), basic JavaScript/TypeScript for frontend integration

**Data & ML**  
- pandas, NumPy, scikit-learn  
- Time series / tabular ML, train–test splitting, cross-validation, evaluation metrics (accuracy, precision, recall, F1, ROC-AUC)

**Backend & APIs**  
- FastAPI, Pydantic, Uvicorn  
- RESTful API design, request/response models, basic auth and routing

**DevOps & Tooling**  
- Docker & Docker Compose  
- Linux (WSL), Bash/PowerShell scripting  
- Basic reverse proxy / HTTPS setup with Caddy  
- Git & GitHub for version control and project management

---

## Activities & Interests

- Equity research with a focus on **AI infrastructure** (GPUs, server racks, networking, power & cooling, ODMs, foundries)
- University finance & investment clubs (equity research, mutual funds, valuation, derivative products)
- **NCCU Dancing Club (熱舞社) – Teaching Member**  
  - Teaching basic to intermediate choreography  
  - Designing class content and practice schedules  
  - Coaching junior members for performances and competitions  
- Building **small but complete systems** that move beyond notebooks to running services

---

## Contact

- GitHub: [@112304008-hub](https://github.com/112304008-hub)
- Email: 112304008@g.nccu.edu.tw/runyusheng@gmail.com   
