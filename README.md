# Amir Ebrahim

Senior Analytics Engineer in Austin, Texas. I work on cloud data platforms, business modeling and BI reliability. This portfolio turns those methods into runnable examples with explicit contracts, failure cases and verifiable results.

## Portfolio

| Project | What it demonstrates | Review in a few minutes |
|---|---|---|
| **[Retail analytics platform](https://github.com/PharaohFresh/analytics-engineering-portfolio)** | dbt/BigQuery facts, finance marts, semantic metrics, independent QA and Airflow | [Business grain](https://github.com/PharaohFresh/analytics-engineering-portfolio/tree/main/case_studies/grain_contracts) and [checkout telemetry](https://github.com/PharaohFresh/analytics-engineering-portfolio/tree/main/case_studies/retail_telemetry) |
| **[Governed analytics delivery](https://github.com/PharaohFresh/agentic-analytics-delivery)** | SQL lineage, environment isolation, approval-bound changes and crash recovery | [Executable delivery proof](https://github.com/PharaohFresh/agentic-analytics-delivery/blob/main/examples/delivery-demo.json) |
| **[Governed query optimizer](https://github.com/PharaohFresh/governed-query-optimizer)** | Duplicate-sensitive result equivalence, modeled scan reduction and reviewed local SQL staging | [Safe and rejected candidates](https://github.com/PharaohFresh/governed-query-optimizer/blob/main/examples/demo-report.json) |
| **[Revenue reconciliation pipeline](https://github.com/PharaohFresh/revenue-reconciliation-pipeline)** | Cumulative payment ingestion, stable booking identity, exact cents and resumable delivery | [Reconciliation and recovery proof](https://github.com/PharaohFresh/revenue-reconciliation-pipeline/blob/main/examples/demo-report.json) |

Each README explains the business problem, implementation decisions, quickstart, tests and limitations. The new demos use invented records and local execution. The warehouse separately supports Google's public retail dataset. Public examples contain no employer source or private customer data.

## How I work

Define the business grain before joining data. Verify values and relationships as well as counts. Separate a proposed change from its authorization, then independently read back the result. Treat API acceptance, observed behavior and business outcomes as different kinds of evidence.

**Portfolio tools:** SQL, Python, dbt, BigQuery, Airflow, SQLite and SQLGlot. My broader platform work includes Microsoft Fabric, Tableau and Power BI; the runnable public cases document their actual scope rather than implying live integrations.

[LinkedIn](https://www.linkedin.com/in/amirebrahim/)
