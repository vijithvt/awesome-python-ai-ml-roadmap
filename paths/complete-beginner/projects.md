# Beginner Project Portfolio

Build these in increasing independence. The objective is not twelve repositories;
combine related mini-projects and publish the strongest three or four.

## Level 0 — Guided mini-builds

### 1. Personal learning tracker

**Skills:** Python values, conditions, functions, JSON  
**Build:** record study sessions, topics, duration and confidence; show weekly totals.  
**Tests:** invalid duration, empty topic, missing file.  
**Stretch:** CLI commands and CSV export.

### 2. File organizer with dry run

**Skills:** paths, files, errors, logging  
**Build:** organize files by extension/date without overwriting.  
**Safety:** default to preview; require confirmation before moves.  
**Stretch:** undo manifest and duplicate detection.

### 3. Public API reporter

**Skills:** HTTP, JSON, validation, retry, caching  
**Build:** fetch non-sensitive public data and create a report.  
**Tests:** timeout, rate limit, malformed response, empty result.

## Level 1 — Foundation portfolio

### 4. Data quality CLI

Follow [Stage 1](../../roadmap/01-python-foundations.md). Include CSV/JSON support,
schema rules, missing/duplicate summaries, tests and machine-readable output.

### 5. SQL business case

Create a small relational dataset with customers, products, orders and returns.
Answer at least 15 stakeholder questions using joins, CTEs and windows. Include query
tests or expected result checks.

### 6. Decision-ready data story

Follow [Stage 2](../../roadmap/02-data-foundations.md). Include provenance, license,
data-quality report, SQL analysis, Python analysis, charts, uncertainty and a
non-technical summary.

## Level 2 — Core ML portfolio

### 7. Regression system

Examples: energy consumption, rental demand or delivery duration.

Required:

- naive baseline;
- temporal/group-aware split where needed;
- preprocessing pipeline;
- MAE plus error distribution/slices;
- saved model and batch CLI;
- model card.

### 8. Imbalanced classification system

Examples: equipment fault, delayed delivery or ticket escalation.

Required:

- transparent rules/logistic baseline;
- PR-AUC and class-specific metrics;
- calibration and threshold-cost analysis;
- subgroup/error analysis;
- FastAPI prediction endpoint with tests.

### 9. Text classification and routing

Route public support issues or news categories. Compare keyword rules, TF-IDF linear
model and a pretrained transformer. Report latency, model size, confusion pairs and
cases where the simpler baseline wins.

## Level 3 — Applied AI portfolio

### 10. Cited document assistant

Use public/authorized documents. Include:

- document provenance and permissions;
- chunking/retrieval comparisons;
- retrieval recall@k evaluation;
- answer/citation verification and abstention;
- prompt-injection cases;
- latency/cost report;
- UI/API and system card.

### 11. Visual classifier

Use an openly licensed modest dataset. Include source-aware splits, simple baseline,
transfer learning, augmentation ablation, per-class metrics, robustness checks and
an error gallery.

### 12. Training-gap recommender

Useful for an education/training domain portfolio:

- skills taxonomy and transparent rules baseline;
- learner-role gap calculation;
- course ranking with explanations;
- human approval and feedback;
- privacy/consent and fairness analysis;
- optional LLM only for explanations, not unsupported scoring.

## Capstone choices by role

| Role | Recommended capstone |
| --- | --- |
| Data analyst | decision-ready operational analytics portal |
| Junior data scientist | calibrated prediction/forecasting decision support |
| Python automation | tested multi-system workflow with audit and rollback |
| ML engineer | deployed model pipeline with tracking, CI and monitoring |
| AI/GenAI engineer | permission-aware cited assistant with evaluation and security |

## Portfolio repository rules

Every published capstone must meet the
[project standard](../../projects/project-standard.md) and contain:

- problem/user/non-goals;
- architecture diagram;
- data/model cards;
- setup, run, test and reproduction commands;
- baseline, experiment table and error analysis;
- demo;
- privacy, security, fairness and limitations;
- operational/cost notes;
- explicit attribution and license.

## Originality rule

Following a tutorial is allowed during learning. A portfolio project must change the
problem, data, constraints, evaluation or system design substantially. Credit every
source. Never rename a cloned repository and present it as original work.
