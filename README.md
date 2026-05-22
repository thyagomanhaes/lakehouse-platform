# lakehouse-platform
A production-style Metadata-Driven Lakehouse Data Platform with Pyspark and Databricks ensuring data quality and governance

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
