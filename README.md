<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:7c3aed&height=200&section=header&text=Sravya%20K&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=AI/ML%20Engineer%20%7C%20MLOps%20%7C%20GenAI/RAG&descAlignY=60&descSize=18" width="100%"/>

<a href="https://www.linkedin.com/in/sravya-k85/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Production+ML+pipelines+%7C+not+just+notebooks;GenAI+%2B+RAG+explainability+layers;Docker+%E2%86%92+Kubernetes+%E2%86%92+CI%2FCD+%E2%86%92+Monitoring;Data+Engineering+%E2%80%A2+MLOps+%E2%80%A2+ML" alt="Typing SVG" />
</a>

<br>

<a href="https://sravya-k0330.github.io/portfolio/" target="_blank">
  <img src="https://img.shields.io/badge/🌐_Live_3D_Portfolio-View_Site-00D9C0?style=for-the-badge" alt="Portfolio" />
</a>

</div>

---

## 🧠 What I Do

| Area | Where it shows up |
|---|---|
| **Data Engineering** | Batch + streaming pipeline over ~38M+ records, Airflow orchestration, Bronze→Silver→Gold architecture |
| **Data Science** | Feature engineering, honest metric reporting on imbalanced data (PR-AUC over accuracy), model cards |
| **Machine Learning** | scikit-learn pipelines (RandomForest, GradientBoosting, Logistic Regression), from-scratch SMOTE |
| **GenAI / LLM / RAG** | Multi-provider LLM gateway (LiteLLM) + TF-IDF RAG retrieval, with graceful fallback |
| **MLOps** | CI/CD gates, Docker, Kubernetes (HPA, canary), Prometheus/Grafana, drift monitoring |

---

## 🚀 Featured Projects

### [Travel Insurance Claim Intelligence Platform](https://github.com/Sravya-k0330/Travel_Insurance_Prediction-AI-ML)
Predicts travel-insurance claim risk **and explains predictions in plain language** via an LLM + RAG layer.
- scikit-learn `ColumnTransformer` pipeline, 3 models compared on a hard 1.68%-positive-rate dataset (63k records), evaluated on **PR-AUC** with a full model card
- From-scratch SMOTE + from-scratch Population Stability Index (PSI) drift detector
- `/v1/explain`: TF-IDF RAG retrieval over a markdown knowledge base → **LiteLLM** gateway (OpenAI/Anthropic/Bedrock/Ollama, swap via env var) → deterministic fallback if the LLM errors
- FastAPI + Pydantic v2, full CI (ruff/black/mypy/pytest+coverage/Docker smoke test), CD to GHCR on tags, Kubernetes + Prometheus/Grafana

### [Telco Churn MLOps Pipeline](https://github.com/Sravya-k0330/AI_MLOps-LLM-MCP-RAG)
End-to-end path from `train.py` to a live, monitored production endpoint.
- FastAPI serving + MLflow experiment tracking and model registry
- Docker → Kubernetes on EKS with autoscaling and canary rollouts (K8s + Seldon)
- CI/CD: test → build → push to ECR → deploy → automated smoke test → **auto-rollback**
- Prometheus metrics for latency, volume, and prediction drift

### [NYC Taxi End-to-End Data Pipeline](https://github.com/Sravya-k0330/nyc-taxi-data-engineering-platform)
Production-grade data platform on real NYC TLC trip data (~38M rows).
- Apache Spark (batch) + Kafka (streaming), orchestrated with Airflow
- dbt (staging → intermediate → mart) into Snowflake, Great Expectations validation
- Full year of data processed end-to-end in ~22 minutes, dashboards via Metabase

---

## 🛠️ Tools & Technologies

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Sravya-k0330&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sravya-k0330&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sravya-k0330&theme=tokyonight&hide_border=true" />

</div>

---

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/Sravya-k0330/Sravya-k0330/output/github-contribution-grid-snake.svg" alt="snake animation" />
</div>

> ⚙️ The snake animation needs a one-time setup — a small GitHub Action that regenerates it daily. Instructions are below.

---

<div align="center">

🌐 [Live 3D Portfolio](https://sravya-k0330.github.io/portfolio/) &nbsp;•&nbsp; 📫 [LinkedIn](https://www.linkedin.com/in/sravya-k85/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:1e3a8a&height=100&section=footer" width="100%"/>

</div>
