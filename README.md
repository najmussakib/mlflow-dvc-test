# MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

The core components of MLflow are:

Experiment Tracking 📝: A set of APIs to log models, params, and results in ML experiments and compare them using an interactive UI.

Model Packaging 📦: A standard format for packaging a model and its metadata, such as dependency versions, ensuring reliable deployment and strong reproducibility.

Model Registry 💾: A centralized model store, set of APIs, and UI, to collaboratively manage the full lifecycle of MLflow Models.

Serving 🚀: Tools for seamless model deployment to batch and real-time scoring on platforms like Docker, Kubernetes, Azure ML, and AWS SageMaker.

Evaluation 📊: A suite of automated model evaluation tools, seamlessly integrated with experiment tracking to record model performance and visually compare results across multiple models.

Observability 🔍: Tracing integrations with various GenAI libraries and a Python SDK for manual instrumentation, offering smoother debugging experience and supporting online monitoring.

- CMD
    - `mlflow ui`

# Dagshub

- [Documentation](https://dagshub.com/)

- dagshub.init(repo_owner='najmussakib', repo_name='mlflow-dvc-test', mlflow=True)

MLFLOW_TRACKING_URI=https://dagshub.com/najmussakib/mlflow-dvc-test.mlflow \
MLFLOW_TRACKING_USERNAME= \
MLFLOW_TRACKING_PASSWORD= \


Run this in the terminal to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/najmussakib/mlflow-dvc-test.mlflow

export MLFLOW_TRACKING_USERNAME=

export MLFLOW_TRACKING_PASSWORD=

```

# AWS

-  Set Mlflow in AWS:
    - set s3 bucket for artifacts
    - set EC2 instance for tracking server and install mlfow dependencies
    - aws configure for cli access
