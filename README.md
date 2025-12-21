
# Harness + GitHub + Docker CI/CD PoC (No AWS)

This repository demonstrates an end-to-end CI/CD pipeline using:

- GitHub for source control
- Harness CI for pipeline orchestration
- Docker for containerization
- Local deployment (no cloud dependency)

## Flow

1. Code push to GitHub
2. Harness CI pipeline triggers
3. Docker image built with commit SHA
4. Existing container stopped
5. New container deployed locally
6. /health endpoint validated

## Endpoint

GET /health → 200 OK

## Why this PoC

- Cloud-agnostic
- Production-grade CI/CD logic
- Interview-ready demonstration
