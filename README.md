# spotifyProject

These project demonstrates data engeering pipeline built on Azure. It uses Azure Data Factory to build pipeline.


## Data Ingestion
The source table is ingested into the Raw container of Azure Data Lake Storage (ADLS), which will act as the Bronze layer.

### Key Features
1. Implemented incremental data load and data backfilling within the same pipeline.
2. Created fully parametrized reusable datasets.
3. Used ForEach activity in Azure Data Factory to loop the pipeline across multiple source table's.

<img width="1741" height="625" alt="Image" src="https://github.com/user-attachments/assets/5d9f11c9-cbe3-4f56-ba01-d639749467db" />

<img width="1783" height="737" alt="Image" src="https://github.com/user-attachments/assets/216f7b82-42dc-4fd1-b334-4db5de936504" />

## Data Transformation



