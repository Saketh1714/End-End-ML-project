# End-End-ML-project

1.update the config.yaml
2.update the schema.yaml
3.update the params.yaml
4.update the entity
5.update the configuration manager in src config
6.update the components
7.update the pipeline
8.update the main.py
9.update the app.py

import dagshub
dagshub.init(repo_owner='Saketh1714', repo_name='End-End-ML-project', mlflow=True)

import mlflow
with mlflow.start_run():
mlflow.log_param('parameter name', 'value')
mlflow.log_metric('metric name', 1)

673179184642.dkr.ecr.ap-south-1.amazonaws.com/mlproj
