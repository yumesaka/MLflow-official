# MLflow-official

## env
```
conda create -n venv_mlflow_official python=3.9
conda activate venv_mlflow_official

conda install ipykernel
python -m ipykernel install --user --name venv_mlflow_official --display-name venv_mlflow_official
pip install mlflow

```


## Run tracking server
`mlflow server --host 127.0.0.1 --port 8080`
