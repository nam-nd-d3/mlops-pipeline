## Create buckets for mlflow
```mkdir -p ./buckets/mlflow```

## To Run
```docker-compose --env-file ./.env up```
## Train and tracking on mlflow via http://locahost:5000/
```docker exec -it mlflow_server bash```
```python train.py```
