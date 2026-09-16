# End-to-End Data Analytics & Business Intelligence Pipeline

An end-to-end data analytics personal project executing the complete data lifecycle: data auditing, wrangling, SQL-based exploratory analysis, interactive dashboard design, and statistical hypothesis testing.

---

## 📌 Project Architecture & 5-Phase Roadmap

| Phase | Core Objective | Key Deliverables & Methods | Status |
| :--- | :--- | :--- | :--- |
| **Phase 1: Data Immersion & Wrangling** | Inspect data quality, handle nulls, clean outliers, engineer features | Data dictionary, automated Pandas cleaning script, clean CSV export | `Completed` |
| **Phase 2: Exploratory Data Analysis (EDA)** | Query underlying patterns and business metrics using relational SQL | Multi-table joins, window functions (`RANK`, `LAG`), trend checks | `Completed` |
| **Phase 3: Interactive Dashboarding** | Translate analysis into actionable visual KPIs for decision-makers | 3–5 core KPIs defined, Star-Schema model, Power BI interactive dashboard | `In Progress` |
| **Phase 4: Statistical Testing & Validation** | Apply statistical rigor to validate observed patterns | Hypothesis formulation, two-sample t-test / chi-square test | `Upcoming` |
| **Phase 5: Executive Synthesis** | Communicate findings to technical and non-technical stakeholders | Structured slide presentation with actionable business recommendations | `Upcoming` |

---

## 🛠️ Tech Stack
- **Data Wrangling:** Python (Pandas, NumPy)
- **Data Querying & Aggregation:** SQL (PostgreSQL / MySQL)
- **Business Intelligence:** Microsoft Power BI, Advanced Excel
- **Statistical Testing:** SciPy, Statsmodels
- **Documentation:** Markdown Data Dictionaries, Executive Presentation

---

## 📂 Repository Structure

```text
├── phase-1-data-wrangling/
│   ├── data_dictionary.md           # Field definitions, data types, and business context
│   └── data_cleaning_pipeline.py    # Automated cleaning script
├── phase-2-sql-exploratory-analysis/
│   └── business_analysis_queries.sql # Core SQL queries answering business questions
├── phase-3-bi-dashboard/
│   ├── kpi_definitions.md           # Business formulas and KPI definitions
│   └── sales_dashboard.pbix         # Power BI report file (or exported PDF)
├── phase-4-statistical-testing/
│   └── hypothesis_validation.py     # Statistical testing scripts and p-value evaluations
└── phase-5-executive-deck/
    └── executive_presentation.pdf   # Final presentation deck
