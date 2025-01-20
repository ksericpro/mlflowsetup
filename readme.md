## Link
https://blog.min.io/setting-up-a-development-machine-with-mlflow-and-minio/

https://towardsdatascience.com/machine-learning-operations-mlops-for-beginners-a5686bfe02b2

https://github.com/prsdm/mlops-project

https://mlflow.org/docs/latest/introduction/index.html

# Setup

- docker-compose --env-file config.env up -d --build

## MinIO

### Access Key
Fz5Q9g2p2LKYKpe7SdhY

### Secret Key
hg6Trh4VLT1CcwMw4Kt8LXMynUSSqQRevH44wJQw

### bucket 
zicare

# Train with mlflow

- python train.py

# to launch MLflow UI
- mlflow ui
http://127.0.0.1:5000

# fast api
- uvicorn app:app --reload
http://127.0.0.1:8000
