<p align="center">
  <img src="https://github.com/juandelaf1/juandelaf1/raw/main/banner_Juan_perfil.png" alt="Juan de la Fuente Banner" width="100%">
</p>

# Juan de la Fuente

**Analytics Engineer** — Building reliable data systems close to business decisions.

[LinkedIn](https://linkedin.com/in/juandelafuentelarrocca) · [Portfolio](https://juandelaf1.github.io) · [Email](mailto:juandelafuentelarrocca@gmail.com)

---

Before engineering data, I ran a business. Managing inventory, costs, logistics, and margins taught me that data is only valuable when it helps someone make a better decision. That principle guides every system I build.

### Focus areas

- Analytics Engineering · Data Pipelines · Data Modeling
- SQL · Python · ETL/ELT
- Data Quality · Testing · API Design
- Production Systems · Business Intelligence

### Featured projects

---

**SkyCast** — Enterprise climate intelligence platform

**Problem:** Municipalities lacked unified real-time climate monitoring across 5 data sources.

**Built:** Modular ingestion pipeline from AEMET OpenData and crowdsourced reports, validated through Pydantic, stored in PostgreSQL with time-series partitioning, served via FastAPI REST API, visualized in Streamlit dashboard with alert engine.

**Engineering focus:** 158 automated tests in CI/CD, circuit breaker pattern for external API failures, data quality checks at every pipeline stage.

→ FastAPI · PostgreSQL · Streamlit · Docker · Python

---

**OptimusPrice** — ML-driven hotel revenue management

**Problem:** Hotels rely on manual pricing or OTAs charging 15-30% commission — slow, reactive, and margin-eroding.

**Built:** Random Forest regressor with Optuna hyperparameter optimization, feature engineering pipeline extracting 40+ demand signals from booking history and competitor data, served via FastAPI inference endpoint, Streamlit management dashboard with confidence intervals.

**Engineering focus:** Model interpretability (feature importance scores for stakeholder trust), automated retraining when MAPE exceeds 20%, input validation rejecting out-of-range features.

→ Python · scikit-learn · Optuna · Streamlit · Docker

---

**DashLogistics** — Multi-market logistics intelligence

**Problem:** Logistics providers need route-level cost prediction across 50 US states with multiple data sources updating at different cadences.

**Built:** Multi-source ETL pipeline ingesting fuel prices (AAA API, daily), weather (OpenWeatherMap, hourly), population data, and operational records. XGBoost cost prediction with Optuna tuning. Streamlit dashboard tracking 15+ KPIs with state-level maps.

**Engineering focus:** Data quality gate preventing bad data from reaching the model, decoupled ingestion from prediction (single source failure doesn't block pipeline), confidence scoring for partial feature availability.

→ Python · Pandas · XGBoost · Streamlit · PostgreSQL · Docker

---

**NetTension** — EU telecom network stress simulation

**Problem:** EU regulators need quantitative evidence of the "scissors effect" (traffic growing exponentially while revenue declines) to inform infrastructure policy.

**Built:** DuckDB-powered analytical pipeline processing 41,937 rows of CNMC regulatory data joined with 1.8M+ Eurostat macroindicators. Six pre-registered hypotheses tested using regression analysis and time-series decomposition. Power BI dashboard for interactive exploration.

**Engineering focus:** Hypothesis-first methodology preventing confirmation bias, DuckDB enabling sub-30-second query times on a laptop without infrastructure provisioning, fully containerized reproducible analysis.

→ Python · DuckDB · Power BI · Docker

---

*Full case studies with architecture diagrams at [juandelaf1.github.io](https://juandelaf1.github.io)*

---

### Currently building

- **Golden Forecast** — ML pipeline and dashboard for gold price prediction. Docker + CI/CD in progress.
- **DataScope** — Multi-source salary analytics platform aggregating compensation data across industries.

---

### Approach

1. **Understand** — Map the business context, identify the decision, define success.
2. **Model** — Design architecture before writing production code.
3. **Build** — Implement with tests at every layer, validation at every boundary.
4. **Measure** — Validate output against the original business problem.

---

[Let's connect →](https://linkedin.com/in/juandelafuentelarrocca)
