# 52-Week Beginner Curriculum

This one-year core assumes 8–10 hours/week. It creates a strong foundation; some
learners will need additional months for their specialization and job search.

## Phase 0 — Orientation and tools

### Week 0 — Understand the field

**Learn:** AI vs ML vs deep learning vs generative AI; data lifecycle; role families;
realistic expectations; responsible use.

**Primary:** [Elements of AI](https://www.elementsofai.com/) introduction and
[Google Introduction to ML](https://developers.google.com/machine-learning/intro-to-ml).

**Lab:** classify 20 everyday systems as rules, analytics, ML, GenAI, or uncertain.
For each, state input, output, user, value, and possible harm.

**Evidence:** one-page role choice and learning contract.

### Week 1 — Terminal, Git and reproducibility

**Learn:** files, paths, shell commands, repositories, commits, branches, README,
licenses, environments and secrets.

**Primary:** [Missing Semester](https://missing.csail.mit.edu/) shell/Git lectures
and [GitHub Skills](https://skills.github.com/).

**Lab:** complete [Stage 0](../../roadmap/00-start-here.md).

**Evidence:** first reproducible repository with at least five meaningful commits.

## Phase 1 — Python programming

### Week 2 — Values, types and expressions

Read [Python tutorial chapters 2–3](https://docs.python.org/3/tutorial/).
Build a unit converter with validated input. Complete 15 short expression/type tasks.

### Week 3 — Conditions and loops

Build a command-line quiz with scoring, retries and input validation. Solve 12 loop
problems, including counting, filtering and nested iteration.

### Week 4 — Functions and decomposition

Refactor the quiz into small functions with docstrings and type hints. Write tests
for pure functions. Explain parameters, return values, scope and side effects.

### Week 5 — Core collections

Use lists, tuples, dictionaries and sets to analyse a small transaction list. Build
a contact book that prevents duplicate identifiers.

### Week 6 — Files, CSV, JSON and paths

Create a multi-format data converter using `pathlib`, `csv` and `json`. Handle
encoding, missing files and malformed input.

### Week 7 — Errors, logging and debugging

Learn exceptions, stack traces, debugger basics and structured logging. Diagnose ten
deliberately broken snippets before viewing fixes.

### Week 8 — Modules, packages and environments

Convert earlier code into an installable package with `pyproject.toml`. Pin/lock
dependencies and recreate the environment in a clean directory.

### Week 9 — Classes and data classes

Model a small library or training-enrolment system. Prefer functions when stateful
objects do not simplify the design.

### Week 10 — Testing and code quality

Learn pytest fixtures/parametrization, formatting, linting, type checking and coverage
interpretation. Add CI using [GitHub Actions](https://docs.github.com/en/actions).

### Week 11 — APIs and HTTP

Learn requests, status codes, JSON, timeouts, pagination and rate limits. Consume a
public API without committing credentials.

### Week 12 — Python checkpoint

Build the [Data Quality CLI](../../roadmap/01-python-foundations.md) without pandas.
Use the [project standard](../../projects/project-standard.md).

**Gate:** another person can install, test and run it from the README.

## Phase 2 — Data analysis and SQL

### Week 13 — NumPy

Learn arrays, shapes, dtypes, indexing, broadcasting and vectorization through
[NumPy Learn](https://numpy.org/learn/). Reimplement five operations using loops,
then compare array implementations.

### Week 14 — pandas foundations

Load, inspect, select, filter, sort and transform tables using
[pandas Getting Started](https://pandas.pydata.org/docs/getting_started/).

### Week 15 — Cleaning and validation

Repair inconsistent types, categories, dates, duplicates, units and missing values.
Create validation checks before analysis.

### Week 16 — Joining and aggregation

Use merge, groupby, pivot and reshape. Predict and verify row counts before/after
joins. Implement an anti-join to find unmatched records.

### Week 17 — SQL foundations

Use [SQLBolt](https://sqlbolt.com/) for SELECT, filters, joins and aggregates, then
repeat locally with SQLite or PostgreSQL.

### Week 18 — Intermediate SQL

Practise CTEs, subqueries, CASE, dates and window functions using
[PostgreSQL's tutorial](https://www.postgresql.org/docs/current/tutorial.html) and
[PGExercises](https://pgexercises.com/).

### Week 19 — Visualization

Learn chart selection, labels, scales and uncertainty with
[Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html) and
[Fundamentals of Data Visualization](https://clauswilke.com/dataviz/).

### Week 20 — Statistics I

Study distributions, sampling, central tendency, spread and correlation with
[OpenIntro Statistics](https://www.openintro.org/book/os/).

### Week 21 — Statistics II

Study estimation, confidence intervals, hypothesis tests, power, effect size and
multiple-comparison caution.

### Week 22 — Exploratory analysis workflow

Select an openly licensed dataset, write questions before analysis, create a
data-quality report, and document provenance/license.

### Week 23 — Communication

Turn the analysis into an executive summary, technical appendix and five-minute
presentation. Separate observation, interpretation and recommendation.

### Week 24 — Data checkpoint

Complete the [decision-ready exploratory report](../../roadmap/02-data-foundations.md)
with both SQL and Python.

**Gate:** every claim is traceable to code/query and includes limitations.

## Phase 3 — Practical mathematics and classical ML

### Week 25 — Vectors and matrices

Use the relevant [Mathematics for Machine Learning](https://mml-book.github.io/)
sections and [3Blue1Brown linear algebra](https://www.3blue1brown.com/topics/linear-algebra).
Implement dot product, matrix multiplication and cosine similarity.

### Week 26 — Gradients and optimization

Understand derivatives, partial derivatives, chain-rule intuition and gradient
descent. Implement linear regression using NumPy.

### Week 27 — Probability and uncertainty

Study conditional probability, Bayes rule, expectation and common distributions
with [Seeing Theory](https://seeing-theory.brown.edu/). Simulate rather than memorize.

### Week 28 — ML framing and baselines

Define unit of prediction, target, features, constraints, baseline, error costs and
success metrics before choosing an algorithm.

### Week 29 — Splits, cross-validation and leakage

Learn random, stratified, grouped and temporal splitting. Construct a leaky example,
measure the misleading improvement, then fix it.

### Week 30 — Linear/logistic models

Use scikit-learn pipelines for regression/classification. Interpret coefficients
carefully and examine preprocessing effects.

### Week 31 — Trees and ensembles

Compare decision trees, random forests and gradient boosting. Tune only after
establishing a baseline and validation strategy.

### Week 32 — Metrics and thresholds

Use MAE/RMSE/R² for regression and precision/recall/F1/ROC-AUC/PR-AUC/calibration
for classification. Select thresholds from real error costs.

### Week 33 — Feature engineering and pipelines

Build `Pipeline` and `ColumnTransformer` flows that prevent preprocessing leakage.
Handle numerical, categorical, text and date features.

### Week 34 — Unsupervised learning

Explore clustering, PCA and anomaly detection. Validate stability and usefulness;
do not assume every cluster is meaningful.

### Week 35 — Interpretation and fairness

Study global/local interpretation, subgroup error analysis, proxy variables, data
representation, human oversight and the limits of technical fairness metrics.

### Week 36 — ML checkpoint

Complete the [prediction-system project](../../roadmap/04-machine-learning.md).

**Gate:** defend split, metric, baseline, model, threshold and limitations to a mixed
technical/domain audience.

## Phase 4 — Deep learning and modern AI

### Week 37 — Neural-network intuition

Learn layers, activations, loss, backpropagation and optimization. Implement a tiny
network or computational graph to observe gradients.

### Week 38 — PyTorch tensors and data

Follow [PyTorch Learn the Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)
through tensors, datasets, data loaders and transforms.

### Week 39 — Training loops

Write training/validation loops, checkpointing and metric logging without a
high-level trainer. Overfit a tiny batch as a debugging check.

### Week 40 — Transfer learning

Fine-tune a modest pretrained model. Compare frozen features, partial fine-tuning
and a simple baseline.

### Week 41 — NLP and transformers

Learn tokenization, embeddings, attention and transformer task families through
[Hugging Face's LLM Course](https://huggingface.co/learn/llm-course/).

### Week 42 — LLM APIs and structured output

Build a small text workflow with schema validation, retries, timeouts, cost logging
and a deterministic non-LLM fallback where possible.

### Week 43 — Retrieval-augmented generation

Build ingestion, chunking, embeddings, retrieval and cited generation. Evaluate
retrieval before answer generation.

### Week 44 — LLM evaluation and security

Create normal, edge and adversarial cases. Study prompt injection, data leakage,
permissions and unsafe tool use with [OWASP GenAI Security](https://genai.owasp.org/).

### Week 45 — AI checkpoint

Complete either the transfer-learning classifier or cited knowledge assistant from
the [project guide](projects.md).

## Phase 5 — Production and employability

### Week 46 — APIs with FastAPI

Build validated inference endpoints, health checks and tests using the
[FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/).

### Week 47 — Containers

Containerize the application using [Docker Get Started](https://docs.docker.com/get-started/).
Run it from a clean environment and document CPU/memory requirements.

### Week 48 — ML lifecycle and monitoring

Track experiments/artifacts, define data/model versions, monitor service and quality
signals, and practise rollback. Use [MLflow](https://mlflow.org/docs/latest/) locally.

### Week 49 — Cloud concepts

Learn compute, storage, identity, networking, managed databases and cost controls.
Deploy only if free-credit/budget limits are configured. Cloud choice should follow
the target market, not fashion.

### Week 50 — Portfolio

Upgrade three strongest projects to the
[end-to-end project standard](../../projects/project-standard.md). Add demos,
architecture, results, limitations, and reproducibility instructions.

### Week 51 — Interview preparation

Practise Python, SQL, ML concepts, project deep dives, system design at beginner
scope, and behavioral stories using [job readiness](job-readiness.md).

### Week 52 — Application sprint

Tailor resume/GitHub to one target role; select 20 suitable openings; extract
requirements; close the highest-frequency gap; seek referrals; track outcomes and
iterate weekly.

## Specialization extension

After Week 52, spend 6–12 additional weeks on one:

- [NLP, LLMs and GenAI](../../roadmap/06-llms-and-genai.md)
- [Computer vision](../../roadmap/07-computer-vision.md)
- [MLOps and production AI](../../roadmap/08-mlops-production.md)
- advanced analytics/experimentation for data roles
