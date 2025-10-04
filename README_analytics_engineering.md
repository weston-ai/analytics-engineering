# Analytics Engineering Portfolio

**End-to-end analytics engineering project demonstrating SQL mastery, dimensional modeling, dbt transformations, and data quality engineering.**

## About This Project

This repository showcases production-grade analytics engineering practices, built as part of my transition from research science (PhD in Molecular Physiology, EPA postdoc) to analytics engineering.

**What's Inside:**
- Advanced analytical SQL patterns (window functions, CTEs, complex aggregations)
- Kimball-style dimensional modeling (star schemas, SCDs, fact/dimension tables)
- dbt transformation pipelines (staging → intermediate → marts)
- Comprehensive data quality testing and validation
- Cloud data warehouse implementation (Snowflake/BigQuery)
- BI dashboards and visualization layer

## Technical Stack

- **SQL:** PostgreSQL, advanced analytical patterns, query optimization
- **dbt:** Transformation framework, testing, documentation, incremental models
- **Python:** Data validation (Pydantic), quality checks, automation
- **Cloud:** AWS (S3, Athena, Glue), Snowflake/BigQuery
- **BI Tools:** Tableau/Power BI for dashboard layer
- **Version Control:** Git, CI/CD with GitHub Actions

## Project Structure
├── sql/                    # SQL queries and analytical patterns
├── dbt_project/           # dbt transformation pipeline
│   ├── models/
│   │   ├── staging/       # Clean, standardized source data
│   │   ├── intermediate/  # Business logic and joins
│   │   └── marts/         # Dimensional models (facts & dimensions)
│   ├── tests/             # Data quality tests
│   └── macros/            # Reusable transformations
├── docs/                  # Documentation and design decisions
└── scripts/               # Python utilities and automation

## Current Progress

**Completed:**
- [ ] Week 1-2: Advanced SQL patterns
- [ ] Week 3-4: Dimensional modeling (Kimball methodology)
- [ ] Week 5-10: dbt pipeline development
- [ ] Week 11-12: Cloud deployment + BI dashboards
- [ ] Week 13-16: Portfolio polish + job search

*This project is actively being built. Check back for updates.*

## Key Projects

### 1. Dimensional Data Warehouse
Complete star schema implementation with:
- Fact tables (transactional grain)
- Slowly Changing Dimensions (Type 1 & 2)
- Conformed dimensions across business areas
- Incremental loading strategies

### 2. Data Quality Framework
Multi-layer testing approach:
- Schema validation at ingestion
- Business rule enforcement in transformations
- Reconciliation and anomaly detection
- Automated test suite with >80% coverage

### 3. dbt Transformation Pipeline
Production-grade dbt project with:
- Clear layering (staging → intermediate → marts)
- Comprehensive documentation
- Incremental models for scale
- CI/CD integration

## Design Principles

- **Grain clarity:** Every table has explicitly documented grain
- **Data quality first:** Tests as living documentation
- **Analyst-friendly:** Denormalization for query simplicity
- **Performance-aware:** Optimized for cloud warehouse costs
- **Production-ready:** Monitoring, alerts, documentation

## Background

PhD in Molecular Physiology with 3 years at EPA doing epidemiology, statistics, and data science with R. Extensive experience with messy real-world data, statistical modeling, and research rigor applied to business problems.

**Technical skills:** Python (SQLAlchemy, Pandas, Polars, APIs), R (dplyr, ggplot), database design, ETL pipelines, version control.

## Contact

Looking for remote analytics engineering opportunities. Open to conversations about data quality, dimensional modeling, or analytics engineering best practices.

[LinkedIn] | [Email]

---

*This is a portfolio project demonstrating analytics engineering capabilities. Data used is anonymized/synthetic.*
