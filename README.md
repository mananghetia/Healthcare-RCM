## Healthcare Revenue Cycle Management (RCM)

RCM is the process that hospitals use to manage the financial aspects, from the time the patient schedules an appointment till the time the provider gets paid.

# Technology
- Azure Data Factory 
- Azure Data Lake Storage
- Azure SQL
- Databricks
- Python/PySpark
- Spark SQL
- Power BI

# Description
- Engineered a scalable end-to-end data pipeline on Azure (Azure Data Factory, Azure Data Lake Storage, Azure SQL, Databricks with PySpark) to migrate on-premises sales data to the cloud; automated daily ETL of ~50K+ records, boosting data freshness and reducing manual effort by ~40%.
- Designed and implemented a metadata-driven ETL framework in Databricks (Python/PySpark, Spark SQL) with a Medallion architecture (bronze/silver/gold layers) and config-driven incremental loads (active/inactive flags); improved processing efficiency by ~30% and ensured high data quality with automated SCD2 (slowly changing dimension) handling.
- Integrated security and governance best practices by leveraging Azure Key Vault for secret management, Unity Catalog for metadata governance, and GitHub for CI/CD; ensured enterprise-grade data protection and maintainability, aligning with high-quality engineering standards.
- Developed dimensional data models and interactive analytics dashboards by building aggregate tables with Spark SQL and delivering Power BI reports visualizing key business KPIs (sales, revenue, top products), accelerating customer-focused decision-making through actionable insights.
