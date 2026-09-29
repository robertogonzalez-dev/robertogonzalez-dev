## Hi, I'm Roberto 👋

**Data Engineer** · Engineer at Venanpri Group · 🟢 Open to data engineering roles

I build data platforms end to end: ingestion pipelines, dbt-modeled warehouses, the APIs and dashboards that serve them, and the tooling and infrastructure that keep them reliable.

💼 [LinkedIn](https://www.linkedin.com/in/robertogonzalezdev) · 📫 [djbeto2209@gmail.com](mailto:djbeto2209@gmail.com)

---

### How my projects fit together

```text
 CommercePulse ───────────► PulseForecast ───────────► PulseInfra
 data platform               ML forecasting             AWS deployment
 (DuckDB + dbt)              (LightGBM + FastAPI)       (Terraform + ECS)
       ▲
       └── dbt-warden: lints dbt projects like CommercePulse in CI
```

### Featured projects

| Project | What it is | Highlights |
|---|---|---|
| **[CommercePulse](https://github.com/robertogonzalez-dev/CommercePulse)** | End-to-end e-commerce analytics platform | Medallion architecture (bronze, silver, gold) on DuckDB · star schema with 7 facts and 6 dimensions · 205 dbt tests · FastAPI + Streamlit on top |
| **[PulseForecast](https://github.com/robertogonzalez-dev/PulseForecast)** | 14-day SKU demand forecasting | Leak-free features with a test that proves it · rolling-origin backtests · LightGBM at 12.8% WAPE vs 23.6% for the seasonal-naive baseline (synthetic benchmark) |
| **[dbt-warden](https://github.com/robertogonzalez-dev/dbt-warden)** | Open-source linter for dbt projects | Reads `manifest.json` to enforce tests, docs, naming and source freshness · zero dependencies · CI-friendly exit codes and pre-commit hook · 99% test coverage |
| **[PulseInfra](https://github.com/robertogonzalez-dev/PulseInfra)** | Terraform on AWS for PulseForecast | ECS Fargate + ALB + ECR modules · keyless GitHub Actions deploys via OIDC · automatic rollback · cost guardrails |
| **[FamilyRoots](https://github.com/robertogonzalez-dev/FamilyRoots)** | Private family genealogy web app | GEDCOM import from Ancestry · interactive React Flow tree · role-based privacy for living relatives · FastAPI, PostgreSQL, React/TypeScript |

### Tech I work with

- **Data:** Python · SQL · dbt · DuckDB · PostgreSQL · pandas · LightGBM
- **Backend & apps:** FastAPI · SQLAlchemy · Streamlit · React · TypeScript
- **Infrastructure:** Docker · Terraform · AWS (ECS, ECR, S3, IAM) · GitHub Actions
