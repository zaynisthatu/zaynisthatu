<h1 align="center">Hi 👋, I'm Zain</h1>
<h3 align="center">Cloud & DevOps Engineer · Docker · Kubernetes · GitOps · CI/CD</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/zain-ashfaq-cloud-engineer" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:zaynisthatu@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

### 👨‍💻 About Me
- 🧭 Self-taught. Path: C++ → Python → data automation → DevOps
- 🔭 Building **[VAULT](https://github.com/zaynisthatu/vault-pipeline)**: a staged DevOps pipeline around a self-built app, with every bug and fix documented
- 🔍 Currently working on: observability (Prometheus, Grafana, Loki) on the VAULT cluster
- ⚙️ Hands-on with CI/CD (GitHub Actions), GitOps (ArgoCD), rolling updates, Kubernetes NetworkPolicy and health probes, and load testing (k6)
- 📍 Pakistan (UTC+5), remote
- 🤝 Open to junior and internship roles, and contract work

### 🛠️ Hands-on Tools
<p align="left">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white" alt="k6" />
</p>
<p align="left">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
</p>

### 🚀 Featured Projects

- 🔗 **[incident-01-cpu-throttling](https://github.com/zaynisthatu/incident-01-cpu-throttling)**
  <br/> *Load-tested Google's Online Boutique (12 services) on a local `kind` cluster with k6. At 500 concurrent users there were 0% failed requests, yet the app was unusable: the Linux CFS bandwidth controller was throttling `currencyservice` and `frontend` at their 200m CPU limit. Found with `kubectl top`, fixed by raising the limit to 400m via rolling update. Avg latency 3.86s → 1.39s, p95 7.21s → 3.12s, throughput 48.9 → 96.8 req/s.*

- 🔗 **[vault-pipeline](https://github.com/zaynisthatu/vault-pipeline)**
  <br/> *A staged DevOps pipeline built around a self-built Node.js/React/SQLite app: multi-stage Docker build and GHCR, a 3-node k3d Kubernetes cluster, ArgoCD GitOps, rolling updates, and observability. Every stage documents the real bugs hit and how they were fixed (Challenge → Root Cause → Fix → Source), plus a "Known gaps" section.*

- 🔗 **Data engineering practice** (each repo runs locally and shows real outputs)
  - **[databricks-pyspark-gold-layer](https://github.com/zaynisthatu/databricks-pyspark-gold-layer)**: PySpark exercise that turns nested JSON post exports into a clean "gold" table (union, null and duplicate handling, enrichment from a notes file). Synthetic data; runs locally, with a Databricks notebook version.
  - **[sql-postgresql-practice](https://github.com/zaynisthatu/sql-postgresql-practice)**: 23 PostgreSQL queries (joins, self joins, subqueries, aggregates) with their real outputs, plus a log of my mistakes with the actual error messages.
  - **[data-cleaning-etl-notebooks](https://github.com/zaynisthatu/data-cleaning-etl-notebooks)**: Colab notebooks that clean public datasets with pandas and load a table into Supabase (Postgres).
