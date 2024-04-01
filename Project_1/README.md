# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/DHANUSHLINGAN/MLOps-Projects.git

```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n clas python=3.8 -y
```

```bash
conda activate clas
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui


### dagshub
[dagshub](https://dagshub.com/)
# Create your own dagshub server
MLFLOW_TRACKING_URI=https://dagshub.com/DHANUSHLINGAN/MLOps-Projects.mlflow \
MLFLOW_TRACKING_USERNAME=DHANUSHLINGAN \
MLFLOW_TRACKING_PASSWORD=c0aff57a24c14dceb34be2c0ffe3cc1a914d4485 \
python script.py
Run this to export as env variables:

```bash

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag




## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)
