# mlflow
In this project we are going to go ahead to do some interesting learning sample project with ML classic and deep learning Algorithems and flow all models and generative AI apps on a unified, end-to-end, open source MLOps platform (MLFLOW)

# To run:
## preparing requirements
```python
 python3 -m venv .venv 
 ```
### Upgrade pip to latest version
```python
pip install -U pip
pip install -r requirements.txt
```
### if you are going to run notebooks file in your editor likes VScode , you you need to install ipkernel but you can run ina local jupyter notebook or google colab 
```python
pip install ipykernel
```
#### Note: for your facilitate you can install some extensions to help you 
you project is ready to run , so for each notebook files, open it and run each cells with **Shift+Enter** but before running commands on mlflow , you must to run mlflow ui to run mlflow server on your server(Local/Public)
```python
mlflow ui
```
mlflow runs on **port 5000** as a default port but if it's already use, you can change it via -p switch
```python
mlflow ui -p 8080
```
# MLFLOW :A Tool for Managing the Machine Learning Lifecycle
MLflow is an open-source platform, purpose-built to assist machine learning practitioners and teams in handling the complexities of the machine learning process. MLflow focuses on the full lifecycle for machine learning projects, ensuring that each phase is manageable, traceable, and reproducible.
you can Store each phase of your training steps to mlflow and do lots of operation such as compare parameters, losses, accuracy,... and control lifecycle of an ml-projects

For more detail: https://mlflow.org/docs/latest/index.html/

# Stucture:
for each project learning we have a folder and in each folder we have a README file to elaborate the project and purposes.