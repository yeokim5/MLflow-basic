import dagshub
dagshub.init(repo_owner='yeokim5', repo_name='MLflow-basic', mlflow=True)

import mlflow
with mlflow.start_run():
mlflow.log_param('parameter name', 'value')
mlflow.log_metric('metric name', 1)
