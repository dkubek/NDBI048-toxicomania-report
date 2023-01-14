# Toxicomania Report

Run ``mlflow`` server using SQLite database on ``localhost`` with port ``5000``
```sh
mlflow server --backend-store-uri "sqlite:///$PWD/mlflow.db" --default-artifact-root "file:$PWD/mlruns" -h localhost -p 5000
```