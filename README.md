## ML Flow experiment

## vhchtjy
fhvcf 

import dagshub
dagshub.init(repo_owner='krishtech1602', repo_name='mlflowexperiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

# mlflowexperiments
