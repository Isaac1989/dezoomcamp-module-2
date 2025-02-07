# Start up docker container for kestra
cd into this repo. Then start up the docker container for kestra using the code below:
```bash
docker compose up
```
To do ETL for the yellow and green taxi data: clone the repo
```bash 
git clone https://github.com/DataTalksClub/data-engineering-zoomcamp.git && cd data-engineering-zoomcamp/02-workflow-orchestration
```

The you can copy the contents of the documents in the flow folder to your kestra instance to run. Makes sure to modify the credentials for the  postgres based on the docker compose file in this repo.  For the ETL using GCP Bigquery, and google cloud buckets follow the tutorial of data engineering zoomcamp 