# Stage 4 — Classical Machine Learning

**Time:** 6–10 weeks  
**Prerequisites:** data foundations and practical math  
**Goal:** build and evaluate leak-resistant baselines for real decisions.

## Learning sequence

1. Problem framing and success metrics
2. Train/validation/test strategy and baselines
3. Preprocessing with pipelines
4. Linear and logistic models
5. Trees, random forests, gradient boosting
6. Nearest neighbors and support vector machines
7. Clustering, dimensionality reduction, anomaly detection
8. Feature engineering and selection
9. Cross-validation and hyperparameter search
10. Calibration, thresholding, interpretation, fairness
11. Error analysis and experiment reporting

## Primary resources

- [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html)
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)

## Non-negotiable habits

- Begin with a naive baseline.
- Split before fitting imputers, encoders, selectors, or scalers.
- Use a `Pipeline`/`ColumnTransformer`.
- Match metrics to error costs; accuracy alone is rarely enough.
- Keep the final test set untouched until decisions are complete.
- Record experiments, seeds, environment, and data version.
- Compare by uncertainty and operational value, not only a decimal score.

## Exercises

1. Create a dummy classifier and explain what it establishes.
2. Trigger preprocessing leakage, measure its effect, then repair it.
3. Compare linear, tree, and boosting models on the same split.
4. Build a confusion matrix and choose a threshold from explicit costs.
5. Evaluate an imbalanced problem using PR-AUC and class-specific metrics.
6. Calibrate probabilities and inspect a reliability curve.
7. Interpret errors by subgroup; distinguish performance gap from unfairness claims.
8. Cluster data, then test whether clusters are stable and useful.
9. Write a model card covering intended use and limitations.

## Build: prediction system

Pick a genuine tabular problem. Examples: churn risk, equipment failure, loan
default education demo, delivery delay, employee training recommendation, or energy
consumption. Avoid domains where an unreviewed model could cause harm.

Deliver:

- problem statement and measurable business/technical success criteria;
- dataset card and leakage analysis;
- baseline plus at least three justified model families;
- reproducible pipeline, tests, experiment table, and error analysis;
- threshold/cost analysis and model card;
- FastAPI inference endpoint or batch prediction CLI.

## Checkpoint

Defend the solution as if to a mixed engineering and business panel. Be ready to
explain why the split, metric, model, and threshold match the actual use case.
