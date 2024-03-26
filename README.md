# Chest-Disease-Classification-from-Chest-CT-Scan-Image
git add .

git commit -m "Updated"

git push origin main


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

conda create -n chest python=3.8 -y
conda activate chest
pip install -r requirements.txt
python app.py


MLFLOW_TRACKING_URI=https://dagshub.com/rohitkabadi/MLFlow.mlflow \
MLFLOW_TRACKING_USERNAME=rohitkabadi \
MLFLOW_TRACKING_PASSWORD=c366d9e0a5a96b91f0a95fbfde85d01af20acbe5 \
python script.py


RUN from bash terminal

export MLFLOW_TRACKING_URI=https://dagshub.com/rohitkabadi/MLFlow.mlflow

export MLFLOW_TRACKING_USERNAME=rohitkabadi 

export MLFLOW_TRACKING_PASSWORD=c366d9e0a5a96b91f0a95fbfde85d01af20acbe5