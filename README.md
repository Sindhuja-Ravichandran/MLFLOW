# To Launch the ML Server
- Run the below command in UBUNTU 
```
mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 127.0.0.1 --port 5000
```
```
mlflow ui
```
# To open MLFLOW UI
- Use the below code in jupyter
```
import mlflow
remote_server_uri = "http://127.0.0.1:5000"
mlflow.set_tracking_uri(remote_server_uri)
```	 
 Go to link [mlflow_ui](http://127.0.0.1:5000)


# Steps Performed
- import mlflow
- set remote server uri
- experiment is created
- train.py file is executed
- executed the train.py with different parameters to get different models
- finally generated mlflow ui




# MLFLOW

