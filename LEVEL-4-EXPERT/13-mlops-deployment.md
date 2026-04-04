# MLOps & Deployment

## Overview
Practical guide to deploying models, CI/CD, monitoring, reproducibility, and production best practices.

## Learning Objectives
- Build reproducible training pipelines
- Create CI/CD workflows for model builds and tests
- Containerize models with Docker and deploy with Kubernetes
- Implement model monitoring and alerting
- Use feature stores, model registries, and experiment tracking

## Labs / Sections
1. Dockerizing a model and serving with FastAPI
2. GitHub Actions for model CI/CD
3. Deploy to Kubernetes with Helm charts
4. Model monitoring with Prometheus + Grafana
5. Canary deployments and rollback strategies

## Example: minimal FastAPI serving
```python
from fastapi import FastAPI
import uvicorn

app = FastAPI()

@app.get('/health')
async def health():
    return {"status": "ok"}

@app.post('/predict')
async def predict(payload: dict):
    # Load model and return prediction (example)
    return {"prediction": 0}

# Run with: uvicorn app:app --reload
```

## Exercises
- Create a GitHub Action that runs unit tests and builds a Docker image
- Deploy a model to a local Kubernetes cluster (kind/minikube)
- Implement basic model monitoring that tracks prediction distributions
