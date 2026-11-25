### Hi, I'm Lana Voynich 👋
**Data & Analytics Engineer | Python • SQL • Prefect 3 • Docker • dbt Core • BigQuery & Snowflake**

I build reliable, well-tested backend data pipelines and governed dimensional models. With **12+ years of enterprise SQL, database, and data integration experience**, I specialize in turning messy multi-source operational data into clean, production-ready warehouse datasets—with automated orchestration, containerization, and strict data quality guardrails.

---

### Core Engineering Stack

* **Orchestration & Containers:** Prefect 3 (`prefect-dbt`), Docker (`python:3.11-slim`), GitHub Actions CI/CD
* **Transformation & Modeling:** dbt Core (incremental models, seeds, snapshots, tests), Kimball Dimensional Modeling, Medallion Architecture
* **Languages & Data Processing:** Python (`pandas`, `requests`), Advanced SQL (CTEs, window functions, query optimization), Bash, Perl
* **Cloud Warehouses & Databases:** Google BigQuery, Snowflake, Oracle, PostgreSQL, MySQL, SQL Server
* **Data Quality & Governance:** Source-to-target reconciliation, deduplication, automated schema/singular testing, SQLFluff, Ruff, RBAC & PII protection

---

### Featured Data & Analytics Engineering Projects

#### 1. [Animal Shelter Operations & Stay Analytics ELT](https://github.com/lvoynich/shelter-analytics-elt)
*Orchestrated, containerized cloud ELT pipeline transforming ~80,000 raw shelter records in Google BigQuery.*
* **Orchestration & Runtime:** Automated end-to-end execution with **Prefect 3** (retry/backoff policies + fail-fast dependency gating) packaged inside a portable **Docker** Linux container.
* **Warehouse & Modeling:** Engineered a partitioned and clustered Kimball star schema (`dim_animals`, `fct_shelter_stays`) with incremental `MERGE` updates and `LAG()`/`ROW_NUMBER()` visit sequencing.
* **Data Quality & CI/CD:** Built a `dbt seed` entity-resolution crosswalk boosting canine breed match rates from 59.6% to **99.5%**, backed by **26+ automated dbt tests** and GitHub Actions linting (`ruff`, `sqlfluff`, `dbt parse`).

#### 2. [Pet Matcher Analytics Engine](https://github.com/lvoynich/pet-matcher-analytics-engine)
*Multi-layer analytics pipeline and automated recommendation engine.*
* Engineered a Python/Pandas ingestion layer across multi-source raw streams into transactional landing tables, modeled governed SQL dimension tables, and built a custom Euclidean distance matching engine.

#### 3. Cloud Data Pipeline — Dog Sports Performance & Budget Tracker(https://github.com/lvoynich/dog-sports-pipeline)
*End-to-end modern data stack pipeline loading local event and budget data into **Snowflake**.*
* Built a secure Python ETL pipeline using encrypted key-pair authentication and a modular **dbt Core** star-schema transformation layer with automated schema assertions and documentation.

---

### What I Focus On
* **Backend Pipeline Reliability:** Designing idempotent ingestion scripts, retry logic, and fail-fast orchestration gates so bad upstream data never corrupts downstream marts.
* **Data Hygiene & Reconciliation:** Untangling legacy SQL, eliminating fan-out duplicates, and reconciling financial and operational metrics to 100% tie-out.
* **Self-Serve Warehouse Foundations:** Delivering clean, documented, and governed datasets that downstream analysts and BI tools can trust.

---

### Connect With Me
* **LinkedIn:** [Lana Voynich on LinkedIn](https://www.linkedin.com/in/lana-voynich-4b658557/)
* **Email:** lvoynich@mac.com
* **Professional Focus:** Open to remote Analytics Engineering and Data Engineering opportunities.
