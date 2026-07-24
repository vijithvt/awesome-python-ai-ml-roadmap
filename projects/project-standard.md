# End-to-End Project Standard

A portfolio project is complete only when another person can understand, reproduce,
evaluate, and operate it at the intended scale.

## Required repository structure

```text
README.md
pyproject.toml
src/
tests/
notebooks/
configs/
data/README.md
models/README.md
docs/
  dataset-card.md
  model-card.md
  architecture.md
.github/workflows/
```

Generated data/models may be excluded when too large or restricted; provide
versioned download or regeneration instructions.

## README checklist

- [ ] Problem, users, and non-goals
- [ ] Demo/screenshots and architecture
- [ ] Data source, license, permission, and schema
- [ ] Baseline and success metrics
- [ ] Setup, configuration, run, test, and reproduce commands
- [ ] Experiment/evaluation results with error analysis
- [ ] Safety, privacy, bias, security, and limitations
- [ ] Deployment and monitoring approach
- [ ] License and acknowledgements

## Engineering checklist

- [ ] Locked dependencies; secrets use environment variables
- [ ] Deterministic seeds where practical
- [ ] Modular preprocessing/training/inference
- [ ] Unit, integration, and data/schema tests
- [ ] Logging and actionable errors
- [ ] CI checks
- [ ] Versioned model/data/config identifiers
- [ ] No large generated files or credentials committed

## Evaluation checklist

- [ ] Naive and meaningful baselines
- [ ] Justified splits and leakage review
- [ ] Metrics tied to actual error costs
- [ ] Confidence intervals or repeated-run variation when relevant
- [ ] Slice and qualitative error analysis
- [ ] Robustness/out-of-distribution checks
- [ ] Latency, memory, throughput, and cost where relevant
- [ ] Known failure cases and escalation/fallback

## Review rubric (100)

| Area | Points |
| --- | ---: |
| Problem framing and value | 15 |
| Data quality, provenance, and ethics | 15 |
| Baseline, method, and experiment design | 20 |
| Evaluation and error analysis | 20 |
| Software/reproducibility | 15 |
| Deployment, safety, and operations | 10 |
| Communication | 5 |

**Portfolio-ready:** 80+, with no critical privacy, security, leakage, or licensing
issue.
