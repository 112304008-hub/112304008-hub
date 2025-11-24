# Yi Lun Fang (Ellen)

Undergraduate in Statistics at National Chengchi University (NCCU)  
Interested in quantitative investing, machine learning for financial markets, and building production-ready ML systems.

---

## Profile

- Background in **Statistics**, with strong foundations in probability, inference, and regression  
- Hands-on experience in **end-to-end ML projects**: data pipelines, model training, API serving, and Docker deployment  
- Strong interest in **AI-themed equity investing**, especially the **AI server hardware and supply-chain ecosystem**  
- Comfortable working across the stack: from **Python & data engineering** to **backend APIs** and **basic DevOps**  
- Part-time **IT assistant** at the NCCU Department of Statistics office, responsible for basic software/hardware maintenance and troubleshooting for faculty and staff  
- Active in **campus life**:  
  - Teaching member of the **NCCU Dancing Club**  
  - Design/marketing member of the **NCCU Mathematics & Information Technology Club (MITc)**  
  - Project member at the **NCCU Financial Investment and Industry Research Club**, working on equity research projects with my own deliverables  

---

## Current Focus

- Short-term stock return prediction models (classification, probability calibration, threshold design)  
- Turning research code into **reliable services** (FastAPI, Docker, monitoring & auto-updates)  
- Connecting **investment research** (AI server cycle, NVDA/TSMC/ODMs, cooling, etc.) with **systematic signals**  
- Building small tools that combine **data, code, and investment views** into something actually usable  

---

## Featured Project

### Fortune Ticker – AI-driven Short-Term Stock Prediction

> A production-style project that combines ML-based stock prediction with an interactive “fortune drawing” (籤筒) frontend.

- Repository: [fortune-ticker](https://github.com/112304008-hub/fortune-ticker)

**Core ideas**

- Predicts next-day direction for selected equities using **technical and lagged features**  
- Wraps ML models in a **FastAPI** backend with clear, documented endpoints  
- Provides both **raw prediction APIs** and a **fortune-style experience** for users  

**Key components**

- Data: automatic creation of `{symbol}_short_term_with_lag3.csv` with `yfinance`/Twelve Data and custom feature engineering  
- ML: Random Forest / Logistic Regression models on short-horizon returns  
- API: `/api/build_symbol`, `/api/predict`, `/api/draw` for different use cases  
- Frontend: interactive “籤筒” UI that turns predictions into fortune slips  
- Infra: Docker + Docker Compose, Caddy reverse proxy, basic production deployment on a remote host  

This project is my main sandbox for experimenting with **research → model → productization**.

---

## Technical Skills

**Languages**

- Python (data/ML/backend), R (statistics coursework), basic JavaScript/TypeScript for frontend integration  

**Data & ML**

- pandas, NumPy, scikit-learn  
- Time series / tabular ML, train–test splitting, cross-validation  
- Evaluation metrics: accuracy, precision, recall, F1, ROC-AUC  

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

- **NCCU Financial Investment and Industry Research Club – Project Member**  
  - Conduct fundamental and industry research, with a focus on AI-related names  
  - Build my own research deliverables (notes, simple models, and small tools) instead of only slides  

- **NCCU Department of Statistics – IT Student Assistant**  
  - Assist with basic software/hardware maintenance in the department office  
  - Help troubleshoot computers, printers, and classroom devices for faculty and staff  

- **NCCU Mathematics & Information Technology Club (MITc) – Design & Marketing**  
  - Responsible for visual design and promotional materials for club events  
  - Helped organize 2025 NCCU PyDay: “Python × LLM Hands-on Workshop”, a full-day offline event on LLM applications in Python  

- **NCCU Dancing Club – Teaching Member**  
  - Teach basic to intermediate choreography  
  - Design class content and practice schedules  
  - Coach junior members for performances and competitions  

- Enjoy building **small but complete systems** that move beyond notebooks to running services  

---

## More Work

- **Equity research & industry notes** – AI ASIC supply chain, CSP capex, and investment angles  
  → [equity-research-and-industry](https://github.com/112304008-hub/equity-research-and-industry)  

- **Research & writing samples** – Survey-based report on appearance anxiety, and an economic analysis of ticket scalping  
  → [research-and-writing-samples](https://github.com/112304008-hub/research-and-writing-samples)  

---

## Contact

- GitHub: [@112304008-hub](https://github.com/112304008-hub)  
- Email: 112304008@g.nccu.edu.tw / runyusheng@gmail.com
