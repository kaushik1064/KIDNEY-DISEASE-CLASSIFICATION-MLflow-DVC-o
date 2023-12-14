# KIDNEY-DISEASE-CLASSIFICATION-MLflow-DVC-o

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
https://github.com/kaushik1064/KIDNEY-DISEASE-CLASSIFICATION-MLflow-DVC-o
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p cnncls python=3.8 -y
```

```bash
conda activate cnncls
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

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kaushik1064/KIDNEY-DISEASE-CLASSIFICATION-MLflow-DVC-o.mlflow \
MLFLOW_TRACKING_USERNAME=kaushik1064 \
MLFLOW_TRACKING_PASSWORD=698b6701fc36eeb759e0f8ecd64caaf1ecf24e87 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kaushik1064/KIDNEY-DISEASE-CLASSIFICATION-MLflow-DVC-o.mlflow

export MLFLOW_TRACKING_USERNAME=kaushik1064

export MLFLOW_TRACKING_PASSWORD=698b6701fc36eeb759e0f8ecd64caaf1ecf24e87

```
