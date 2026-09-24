<h1 align='center'>
  Hi there! 👋 I'm William 👨‍💻🤖
</h1>

<p align='center'>
  Machine Learning Engineer | Ranking & Recommendation | Production ML | Campinas-SP (Brazil)
</p>

<p align='center'>
  <a href="https://www.linkedin.com/in/williamsm01010101/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
  <a href="https://www.kaggle.com/laosdata">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" />
  </a>
</p>

## About Me

I build ML systems that run in production and move business metrics. My XGBoost ranking model scores ~4M items a day and lifted revenue by 26%. My LLM systems autonomously resolve 89% of ~60K monthly support tickets. I work across the full lifecycle: feature pipelines, training, champion/challenger A/B testing, and model serving.

## Featured Projects

- 🎯 **[Contextual bandit ranking service](https://github.com/JabuS2/datathon-7mlet-grupo-68)** (FIAP capstone, lead contributor)<br>
  Built the model service for an offer recommendation platform. LinUCB, Thompson sampling and a rule-based baseline are served through FastAPI (`/rank`, `/update`). Online learning state lives in Redis with per-policy distributed locks. Shadow and active policies support atomic promotion and rollback, with an MLflow registry and Datadog observability. In a paired multi-seed simulation, LinUCB reached **93.8% of oracle reward**, against 90.2% for the baseline.

- ☁️ **[Serverless data pipeline on AWS](https://github.com/WilliamSMendes/tech_challenge_2_mlet)**<br>
  Daily pipeline provisioned with Terraform: EventBridge, Lambda, S3 (Parquet with Hive partitions), Glue with Polars, and Athena. Deployed through GitHub Actions CI/CD.

- ✈️ **[Flight delay prediction](https://github.com/WilliamSMendes/tech_challenge_3_mlet)**<br>
  Classification (XGBoost, LightGBM, Random Forest) with SHAP interpretability, plus KMeans segmentation into operational personas.

## Tech Stack

<p align='center'>
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-316192?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</p>

## Professional Experience

- 💼 **Data Scientist, Machine Learning at Acerto (2024 to present)**
  - Designed an XGBoost ranking model (choice probability × projected revenue, with position bias correction) that scores ~4M debts daily. Validated through champion/challenger A/B testing, it **lifted revenue 26%**.
  - Built and own a multi-agent LLM negotiation system (LangGraph, GCP) on WhatsApp, responsible for **2% of total company revenue**.
  - Built an LLM support system on Zendesk that **autonomously resolves 89%** of ~60K monthly tickets.

- 📊 **Data Scientist at AB InBev (2023 to 2024)**
  - Built a PySpark/Databricks forecasting architecture for the European beer market at **92% accuracy**, validated by A/B test and generating multi-million savings.

- 📈 **Data Scientist and Consultant at Kumulus Cloud & Data (2021 to 2023)**
  - Deployed a computer vision system (YOLO/PyTorch, Azure) for energy tower inspection, **saving BRL 100K/month**.

## Education

- 🤖 **Postgraduate in Machine Learning Engineering**, FIAP
- ⚙️ **Technologist in Industrial Automation**, IFSP (Instituto Federal de São Paulo)

## Publication

- 📄 Co-author, *"An open-access WebApp for Inverse Laplace Transform analysis of TD-NMR signals,"* Magnetic Resonance, 2026. [DOI 10.5194/mr-7-39-2026](https://doi.org/10.5194/mr-7-39-2026)

## Certifications

- :heavy_check_mark: **Microsoft Certified: Azure AI Engineer Associate**
- :heavy_check_mark: **Microsoft Certified: Azure Fundamentals, Azure Data Fundamentals, Azure AI Fundamentals**

## Contact

<p align='center'>
  📫 <a href='mailto:william.qgdi@gmail.com'>william.qgdi@gmail.com</a>
</p>
