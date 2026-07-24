# Track C — MLOps & Production AI

**Time:** 6–10 weeks; start after one useful model exists  
**Goal:** operate an AI capability reliably, safely, and economically.

## Production layers

| Layer | Skills | Evidence |
| --- | --- | --- |
| Software | packaging, typing, tests, configuration, logging | CI passes |
| Data | contracts, validation, lineage, versioning | reproducible dataset |
| Model | experiments, registry, evaluation gates | promoted artifact |
| Serving | batch/API, schema, auth, timeout, scaling | load-tested endpoint |
| Delivery | container, CI/CD, infrastructure basics | repeatable deployment |
| Operations | metrics, traces, drift, alerts, rollback | dashboard and runbook |
| Governance | model card, access, privacy, audit, approval | risk controls |

## Primary resources

- [Made With ML MLOps course](https://madewithml.com/courses/mlops/)
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/)
- [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/)
- [Docker Get Started](https://docs.docker.com/get-started/)
- [GitHub Actions documentation](https://docs.github.com/en/actions)
- [MLflow documentation](https://mlflow.org/docs/latest/)
- [Evidently documentation](https://docs.evidentlyai.com/) for evaluation/monitoring

Cloud-specific services are optional. Learn portable concepts locally first, then map
them to the cloud used by your team.

## Exercises

1. Package preprocessing and inference together; reject invalid schemas.
2. Test training code, data transformations, and API contracts separately.
3. Track parameters, metrics, artifacts, code revision, and dataset identifier.
4. Containerize the API and run it from a clean environment.
5. Add CI for lint, tests, security checks, and container build.
6. Load-test the endpoint and report p50/p95 latency and throughput.
7. Simulate schema drift and feature distribution shift.
8. Define service-level indicators and useful alert thresholds.
9. Perform a model rollback using a documented runbook.
10. Estimate cost per 1,000 predictions or requests.

## Capstone: production-grade ML service

Upgrade a previous project with:

- validated training and inference pipelines;
- experiment tracking and versioned artifacts;
- FastAPI batch/online interface with health endpoints;
- tests, container, automated CI, and dependency scanning;
- latency/load report, operational metrics, drift evaluation;
- model card, threat model, rollback and incident runbooks.

Local deployment is acceptable if reproducible. A public cloud bill is not evidence
of better engineering.
