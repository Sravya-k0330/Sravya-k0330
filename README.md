<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:7c3aed&height=180&section=header&text=Sravya%20K&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=45" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&pause=1200&color=00D9C0&center=true&vCenter=true&width=560&height=40&lines=AI%2FML+Engineer;GenAI+%26+RAG+Systems;MLOps+%2F+Kubernetes+%2F+CI-CD;Data+Engineering+at+Scale" alt="Typing SVG" />

<br><br>

<a href="https://sravya-k0330.github.io/portfolio/" target="_blank">
  <img src="https://img.shields.io/badge/🌐_Portfolio-View_Site-00D9C0?style=for-the-badge&labelColor=0B0E14" alt="Portfolio" />
</a>
<a href="https://www.linkedin.com/in/sravya-k85/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B0E14" alt="LinkedIn" />
</a>

</div>

<br>

<div align="center">
<img src="./assets/tech-orbit.gif" width="380" alt="tech stack orbit animation"/>
</div>

---

## 🧠 What I Do

<table>
<tr>
<td width="20%"><b>🔧 Data Engineering</b></td>
<td>

`Spark` `Kafka` `Airflow` — batch + streaming over **38M+ records**, Bronze→Silver→Gold architecture

</td>
</tr>
<tr>
<td><b>📊 Data Science</b></td>
<td>

Feature engineering, **PR-AUC over accuracy** on imbalanced data, documented model cards

</td>
</tr>
<tr>
<td><b>🤖 Machine Learning</b></td>
<td>

`scikit-learn` pipelines (RandomForest, GradientBoosting, LogReg), from-scratch **SMOTE**

</td>
</tr>
<tr>
<td><b>🧬 GenAI / LLM / RAG</b></td>
<td>

`LiteLLM` multi-provider gateway + **TF-IDF RAG retrieval**, graceful fallback on LLM failure

</td>
</tr>
<tr>
<td><b>🚢 MLOps</b></td>
<td>

`Docker` → `Kubernetes` (HPA, canary) → CI/CD with **auto-rollback**, Prometheus/Grafana drift monitoring

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="100%">

### 🧬 [Travel Insurance Claim Intelligence Platform](https://github.com/Sravya-k0330/Travel_Insurance_Prediction-AI-ML)

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![LiteLLM](https://img.shields.io/badge/-LiteLLM-8B7FFF?style=flat-square) ![RAG](https://img.shields.io/badge/-RAG-8B7FFF?style=flat-square) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Claim-risk prediction **+ plain-language LLM/RAG explainability layer**

- 🎯 3 models compared · **63K records** · **1.68%** positive rate · evaluated on **PR-AUC**
- ⚙️ From-scratch **SMOTE** + from-scratch **PSI drift detector**
- 🧬 `/v1/explain` → TF-IDF retrieval → **LiteLLM** (OpenAI / Anthropic / Bedrock / Ollama) → deterministic fallback
- ✅ Full CI (ruff · black · mypy · pytest · Docker smoke test) → CD to GHCR → K8s + Prometheus/Grafana

</td>
</tr>
<tr>
<td>

### 🚢 [Telco Churn MLOps Pipeline](https://github.com/Sravya-k0330/AI_MLOps-LLM-MCP-RAG)

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-EKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**train.py → live, monitored production endpoint**

- 📦 FastAPI serving + **MLflow** registry & experiment tracking
- ☸️ Kubernetes (EKS): autoscaling, canary rollouts (K8s + Seldon)
- 🔁 CI/CD: test → build → ECR → deploy → smoke test → **auto-rollback**
- 📈 Prometheus: latency, volume, prediction-drift metrics

</td>
</tr>
<tr>
<td>

### 📊 [NYC Taxi Data Platform](https://github.com/Sravya-k0330/nyc-taxi-data-engineering-platform)

![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**38M+ real NYC TLC trip records, end-to-end**

- ⚡ Spark (batch) + Kafka (streaming), orchestrated with Airflow
- 🏗️ Bronze → Silver → Gold via dbt into Snowflake
- ✅ Great Expectations + **14/14 dbt tests passing**
- ⏱️ Full year processed end-to-end in **~22 minutes**

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**🧬 GenAI / LLM / RAG**

![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/-Anthropic-191919?style=for-the-badge) ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![LiteLLM](https://img.shields.io/badge/-LiteLLM-8B7FFF?style=for-the-badge) ![RAG](https://img.shields.io/badge/-RAG-8B7FFF?style=for-the-badge) ![LLM](https://img.shields.io/badge/-LLM_APIs-8B7FFF?style=for-the-badge) ![Prompt Engineering](https://img.shields.io/badge/-Prompt_Engineering-8B7FFF?style=for-the-badge)

**🤖 Machine Learning / Data Science**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**🚢 MLOps / Infra**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**📊 Data Engineering**

![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Sravya-k0330&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sravya-k0330&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=86400" />

<img src="https://streak-stats.demolab.com/?user=Sravya-k0330&theme=tokyonight&hide_border=true" />

</div>

> If any stat card shows "Error fetching resource," it's a temporary outage on the free public stats service, not a broken link — it resolves on its own within a day. Refresh or revisit later.

---

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/Sravya-k0330/Sravya-k0330/output/github-contribution-grid-snake.svg" alt="snake animation" />
</div>

---

<div align="center">

📫 [LinkedIn](https://www.linkedin.com/in/sravya-k85/) &nbsp;•&nbsp; 🌐 [Portfolio](https://sravya-k0330.github.io/portfolio/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:1e3a8a&height=100&section=footer" width="100%"/>

</div>
