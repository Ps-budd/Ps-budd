<!--
  PROFILE README for: Ps-budd
  Tips:
  1) Add a banner image at assets/banner.png (1200x300) and it will render below.
  2) Update links + repo names where marked.
-->

<p align="center">
  <img src="assets/banner.png" alt="Aditya Dubey — Data Engineer • AI Builder" width="100%" />
</p>

<h1 align="center">Hi, I'm Aditya — Data Engineer • AI Builder • Creator of mygol.ai</h1>

<p align="center">
  <a href="mailto:adi.dubey552@gmail.com"><img src="https://img.shields.io/badge/Email-adi.dubey552%40gmail.com-informational?style=flat&logo=gmail&logoColor=white"></a>
  <a href="https://mygol.ai" target="_blank"><img src="https://img.shields.io/badge/Website-mygol.ai-blue?style=flat&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/adityadubey09/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-adityadubey09-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/Ps-budd?tab=followers" target="_blank"><img src="https://img.shields.io/github/followers/Ps-budd?label=Follow&style=flat"></a>
  <img src="https://komarev.com/ghpvc/?username=Ps-budd&style=flat&label=Profile+Views" alt="profile views"/>
</p>

---

### 🚀 What I do
- Build **cloud-native data platforms** on **GCP/AWS/Snowflake** (BigQuery, Cloud Run, Dataflow, Pub/Sub, dbt, Airflow, Spark).
- Ship **privacy-first APIs** (GDPR/CCPA) and **LLM/RAG** features using OpenAI/Gemini/Claude with guardrails.
- Obsessed with **speed & cost**: saved **~$100K/month** BigQuery; cut delivery SLAs by **87%**.

> **Now building:** **mygol.ai** — job-apply engine powered by Playwright + n8n + Cloud Run microservices + Next.js/Vercel + Postgres.

---

### 🧩 Featured Builds 
- **First-Party Segment API (GCP)** — Cloud Run + API Gateway + Pub/Sub/Dataflow; OpenTelemetry tracing; opt-out & expiration endpoints.  
  `GCP` · `Cloud Run` · `API Gateway` · `BigQuery` · `OpenTelemetry`  
  **Repo:** `Ps-budd/first-party-segment-api` <!-- update if different -->

- **CRM Delivery Platform** — PII encryption/salting; SFTP/GCS/S3 **chunked delivery** with retries; **2 days → 6 hours**.  
  `Python/Go` · `S3/GCS/SFTP` · `Retries` · `Checksums`  
  **Repo:** `Ps-budd/crm-delivery-platform`

- **LLM Audience Segmenter** — NL → audience segments; **90%** manual effort ↓; **85%** launch time ↓; hallucination-mitigation guardrails + evals.  
  `FastAPI` · `OpenAI/Gemini` · `Guardrails` · `Evals`  
  **Repo:** `Ps-budd/llm-audience-segmentation`

- **BigQuery Cost Optimizer** — stored procedures + usage analyzer; partition/prune; **~$100K/month** saved.  
  `BigQuery` · `SQL` · `Scheduler`  
  **Repo:** `Ps-budd/bq-cost-optimizer`

- **DE Boilerplate (GCP)** — cookiecutter; Airflow/dbt/Spark flavors; CI, IaC, observability baked in.  
  `Cookiecutter` · `Terraform` · `GitHub Actions` · `OpenTelemetry`  
  **Repo:** `Ps-budd/de-boilerplate-gcp`

---

### 🔧 Toolbox (select)
<p>
  <img alt="BigQuery" src="https://img.shields.io/badge/BigQuery-4285F4?logo=googlebigquery&logoColor=white">
  <img alt="Snowflake" src="https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white">
  <img alt="Redshift" src="https://img.shields.io/badge/Redshift-8C4FFF?logo=amazonredshift&logoColor=white">
  <img alt="GCS" src="https://img.shields.io/badge/GCS-1a73e8?logo=googlecloud&logoColor=white">
  <img alt="S3" src="https://img.shields.io/badge/S3-569A31?logo=amazonaws&logoColor=white">
  <img alt="Cloud Run" src="https://img.shields.io/badge/Cloud%20Run-4285F4?logo=googlecloud&logoColor=white">
  <img alt="Dataflow" src="https://img.shields.io/badge/Dataflow-1a73e8?logo=googlecloud&logoColor=white">
  <img alt="Pub/Sub" src="https://img.shields.io/badge/Pub%2FSub-1a73e8?logo=googlecloud&logoColor=white">
  <img alt="Airflow" src="https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white">
  <img alt="dbt" src="https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white">
  <img alt="Spark" src="https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white">
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232a?logo=react&logoColor=61DAFB">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/Actions-2088FF?logo=githubactions&logoColor=white">
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=white">
</p>

---

### 🗺️ Platform at a glance (Mermaid)
```mermaid
flowchart LR
  U[Users/Jobs] -->|HTTP| GW(API Gateway)
  GW --> CR{Cloud Run Services}
  CR -->|Async| PS[Pub/Sub]
  PS --> DF[Dataflow]
  DF --> BQ[(BigQuery)]
  BQ --> DBT[dbt Models]
  DBT --> OUT[Looker/Metabase/Apps]

  subgraph Observability
    OTLP[OpenTelemetry] --> GLogs[Cloud Logging/Tracing]
  end
  CR -.trace.-> OTLP
  DF -.metrics.-> OTLP
