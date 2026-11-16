## Hi, I'm Karthick 👋

**AI / ML engineer** building reliable, well-evaluated systems end to end: computer vision, LLM agents, MLOps and edge deployment.
Former Research Engineer at **Singapore Management University**, now doing a Master of IT in Business (AI track) at SMU.

- 🏆 **Best Poster Runner-Up**, ACM UbiComp/ISWC 2026, for 3D object-retrieval guidance for blind and low-vision users
- 🔭 Open to AI / ML engineering roles in Singapore

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=sqlite&logoColor=white)

**ML & Computer Vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1A73E8?style=flat&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat&logo=ultralytics&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat&logo=google&logoColor=white)

**LLMs & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=claude&logoColor=white)
![Hugging Face](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Data & MLOps**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Edge Deployment**

![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white)

---

### 📌 Featured Projects

| Project | What it does | Tech |
|---|---|---|
| **[Citi Bike Demand Forecasting](https://github.com/mg-minsan/mle-citibike-demand-forecasting)** | Forecasts next-day trip starts for 824 NYC stations so planners can rebalance bikes before stations run empty. A Bronze/Silver/Gold pipeline turns 30.2M trips into 424K station-day features. Airflow runs forecasts at 06:00 daily and retrains every month, with an MLflow champion registry and daily drift monitoring (PSI, SHAP). **MAE cut 38% vs a lag-7 baseline** (22.9 → 14.2 trips per station-day). | PySpark · XGBoost · Airflow · MLflow · Docker · Streamlit |
| **[AI Career Planning Agent](https://github.com/mg-minsan/cs-621-career-progress-guide)** | LangGraph + Claude agent (an orchestrator and two sub-agents) that turns a career goal into a costed SkillsFuture course plan. It draws on 2,030 job roles and 26,099 courses, uses hybrid search with re-ranking, and has 3 human checkpoints. **Scored 83% vs 46% for a plain LLM**. **0 of 50 prompt-injection attacks succeeded**, with code-level guardrails and a $0.50 cap per plan. | LangGraph · Claude API · BM25 · sentence-transformers · Streamlit |
| **Loan Default Pipeline** <br> [Part 1: data](https://github.com/A-karthick/cs611-assignment1) · [Part 2: ML](https://github.com/A-karthick/cs611-assignment2) | Medallion pipeline that builds 92 point-in-time features from 4 sources and fixes a clickstream leakage bug. On top of it, a 17-task monthly Airflow DAG trains XGBoost vs logistic regression as champion and challenger, scores new applicants and monitors PSI and AUC. **Test AUC 0.854**. Monitoring caught a data-source drop (score PSI 0.01 → 0.44) and triggered an investigation. | PySpark · Airflow · XGBoost · scikit-learn · Docker |
| **Medicare Fraud Detection** | End-to-end ETL and ML pipeline that detects fraudulent Medicare providers across **558K+ claims and 5,410 providers** (~9.4% fraud rate). Engineered provider- and claim-level features and benchmarked 5 models, optimising for PR-AUC and Precision@Top-K to handle class imbalance and help investigators prioritise cases. | PyTorch · CatBoost · XGBoost · pandas |
| **Travelling Salesman Solver** | Three-phase heuristic that builds a nearest-neighbour tour, refines it with 2-opt, then escapes local minima with simulated annealing using a self-calibrating cooling schedule. **Solved 1,000 / 1,300 / 2,000-city instances within the 30 s / 60 s / 3 min limits**, on clustered "island" datasets we generated to trap greedy and 2-opt methods. | Python · Algorithms |
| **US Airline Delay Analysis** | 23 years of BTS on-time data (383K carrier-airport-months). Uses ANOVA, chi-square and paired t-tests to measure carrier, seasonal and post-COVID effects on delays. I combined the four analyses into a final airline ranking and the recommendations for travellers. | Python · SciPy · statsmodels |

---

### 🔬 Research

**Enhancing Object Retrieval via Phase-Aware 3D Spatial Guidance for Blind and Low-Vision Users**
K. Kusakabe, Y. Abe, **K. Anandan**, D. Sakamoto, K. Hara · *ACM UbiComp/ISWC 2026 Adjunct, Shanghai* · 🏆 Best Poster Runner-Up

---

### 💼 Experience

- **Research Engineer**, Singapore Management University · *2025 – 2026*
- **AI Development Technologist**, Nanyang Polytechnic · *2020 – 2021*

---

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://sg.linkedin.com/in/karthick-anandan-a9659a129)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:spykarthick@gmail.com)
