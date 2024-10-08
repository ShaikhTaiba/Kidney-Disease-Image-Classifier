# Kidney-Disease-Image-Classifier
A machine learning model for classifying kidney diseases using medical images. The project employs CNNs for image classification and integrates MLflow for experiment tracking and DVC for data version control, ensuring reproducibility and scalability in the model development process.


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

# How  to run?
### STEPS:

clone the repository

```bash
https://github.com/ShaikhTaiba/Kidney-Disease-Classification-MLflow-DVC
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- Install the requirements
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


#### cmd
- mlflow ui

### dagshub
- [dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/ShaikhTaiba/Kidney-Disease-Image-Classifier.mlflow \
MLFLOW_TRACKING_USERNAME=ShaikhTaiba \
MLFLOW_TRACKING_PASSWORD=[Your access token] \
python script.py

Run this to export as env variables:

```bash

$env:MLFLOW_TRACKING_URI = "https://dagshub.com/ShaikhTaiba/Kidney-Disease-Image-Classifier.mlflow"
$env:MLFLOW_TRACKING_USERNAME = "ShaikhTaiba"
$env:MLFLOW_TRACKING_PASSWORD = "[Your access token]"   # Replace [Your access token] with your dagshub access token 

```

