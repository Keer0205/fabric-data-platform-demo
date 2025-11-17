# Microsoft Fabric Data Platform Demo

**Live end-to-end demo built for the Willmott Dixon Data Engineer role**  
Proves: PySpark | SQL | Lakehouse | Delta tables | CI/CD-ready structure | Self-service analytics

### Week 2 Complete – Bronze → Silver Layer
- Ingested NYC Taxi parquet → `bronze.trips_raw`
- Transformed with PySpark → `silver.fact_trips` (cleaned, filtered, renamed columns)
- Unit-tested with >2.8M rows assertion

**Live Notebook**: [notebooks/02_bronze_to_silver_transform.ipynb](notebooks/02_bronze_to_silver_transform.ipynb)

### Next
- Week 3: Azure DevOps CI/CD + Row-Level Security
- Week 4: Power BI semantic model + self-service dashboard

Built by Keerthana M (@Keer0205) – Nov 2025
