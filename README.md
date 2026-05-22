# lakehouse-platform
A production-style Metadata-Driven Lakehouse Platform using:

Databricks concepts
PySpark
Delta Lake
Airflow
Docker
MinIO/S3
Data Quality
Incremental processing
Governance concepts
Reusable ingestion framework

                FILES / APIs / FIVETRAN
                         │
                         ▼
              Metadata-Driven Ingestion
                         │
                         ▼
                  Bronze Layer
               (Raw Delta Tables)
                         │
                Data Quality Rules
                         ▼
                  Silver Layer
            (Cleaned & Validated)
                         │
                  Business Logic
                         ▼
                    Gold Layer
                  (Analytics)
