# Chest-Disease-Classification-from-Chest-CT-Scan-Image
git add .

git commit -m "Updated"

git push origin main

conda create -n chest python=3.8 -y
conda activate chest
pip install -r requirements.txt
python app.py


Mlflow dagshub connection uri
MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/MLflow-Expriement-demo.mlflow \
MLFLOW_TRACKING_USERNAME=entbappy \
MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0 \


python script.py
RUN from bash terminal
export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/MLflow-Expriement-demo.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0