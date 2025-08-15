# AKS5

flowchart TD
    A[Data Source<br>(CSV, Excel, API)] --> B[Data Cleaning & Preprocessing<br>(Excel, Power Query, Scripts)]
    B --> C[Automated ETL Pipeline<br>(Azure Data Factory / Manual Upload)]
    C --> D[Azure SQL Database<br>(Hosted in Cloud)]
    D --> E[Data Governance<br>(Roles, Permissions, Audit Logs)]
    E --> F[Power BI<br>(DirectQuery / Import)]
    F --> G[Interactive Dashboards & Reports]
    G --> H[Publish & Share<br>(Power BI Service)]
