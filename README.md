# <center>New York City Taxi Dataset Portfolio Project</center>
---
Course page: [link](https://github.com/DataTalksClub/data-engineering-zoomcamp)

A data pipeline for the NYC Taxi Trip Dataset, [[source](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)], for my data engineering portfolio project. The data pipeline is built using Apache Airflow and is deployed on Google Cloud Platform. The data pipeline is scheduled to run monthly and the data is stored in Google Cloud Storage. The data is then loaded into BigQuery for analysis.

---
## Data Model
The data model is a star schema with the following tables:
- ...
- ...
- ...

| Table | Description |
| --- | ---: |
| `fact_table` | _trip data_ |
| `dim_table` | ... |
| `dim_table` | ... |