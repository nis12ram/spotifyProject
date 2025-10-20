# spotifyProject

These project demonstrates data engeering pipeline built on Azure. It uses Azure Data Factory to build pipeline.


## Data Ingestion
source table ingested into raw container of Azure Data Lake Storage(ADLS) which will act as our bronze layer

### Key Features
1. Implemented incremental data load and data backfilling within the same pipeline.
2. Created fully parametrized reusable datasets.
3. Used ForEach activity in Azure Data Factory to loop the pipeline across multiple source table's.






