# System Architecture for ML

## Overview
Design patterns and architecture for scalable ML systems: model versioning, storage, feature stores, data pipelines, serving, and monitoring.

## Learning Objectives
- Understand ML system components and interactions
- Design feature stores and data contracts
- Plan model versioning and CI/CD for models
- Choose serving strategies (batch vs online)
- Monitor model drift and data quality

## Sections / Labs
1. ML system diagrams and component responsibilities
2. Feature store design (Feast overview)
3. Model registry and versioning (MLflow example)
4. Serving patterns: REST, gRPC, streaming
5. Monitoring and observability (Prometheus/Grafana)
6. ML governance, security, and compliance policies

## Example: Model packaging checklist
- Containerize model with a predictable entrypoint
- Attach model metadata and version
- Add health and metrics endpoints
- Automate deployment with CI (GitHub Actions)

## Exercises
- Design an ML system for an online recommendation service
- Implement a simple feature store using a DB + ingest pipeline
- Create a model registry entry using `mlflow`
