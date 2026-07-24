# Stage 2 — Data Foundations

**Time:** 4–6 weeks  
**Prerequisite:** [Python foundations](01-python-foundations.md)  
**Goal:** turn raw data into trustworthy analysis and model-ready features.

## Topics and primary resources

| Topic | Learn | Primary resource |
| --- | --- | --- |
| Arrays | shape, dtype, indexing, broadcasting, vectorization | [NumPy Learn](https://numpy.org/learn/) |
| Tables | selection, joins, grouping, missing data, time series | [pandas getting started](https://pandas.pydata.org/docs/getting_started/) |
| Visualization | chart choice, distributions, relationships, uncertainty | [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html) |
| SQL | SELECT, JOIN, GROUP BY, CTE, window functions | [SQLBolt](https://sqlbolt.com/) and [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) |
| Statistics | sampling, distributions, intervals, tests, leakage | [OpenIntro Statistics](https://www.openintro.org/book/os/) |
| Data ethics | consent, privacy, representation, documentation | [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) |

## Required workflow

For every dataset:

1. State the decision or question before opening the data.
2. Record source, license, collection process, and unit of observation.
3. Split identifiers, targets, timestamps, and candidate features.
4. Profile missingness, duplicates, ranges, and suspicious correlations.
5. Protect a test set before target-informed analysis.
6. Create a reproducible cleaning pipeline.
7. Communicate uncertainty and limitations.

## Exercises

1. Reproduce mean, variance, standardization, and matrix multiplication with NumPy.
2. Demonstrate broadcasting with three differently shaped arrays.
3. Clean inconsistent dates, categories, and units in a messy table.
4. Perform inner, left, and anti-joins; explain the resulting row counts.
5. Write SQL using a CTE and window function to rank monthly performance.
6. Create one misleading chart, explain the issue, and correct it.
7. Test whether missingness is associated with another variable.
8. Write a one-page dataset card.

## Build: decision-ready exploratory report

Choose an openly licensed dataset from:

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [OpenML](https://www.openml.org/)
- [World Bank Open Data](https://data.worldbank.org/)
- a relevant government open-data portal

Deliver:

- raw-data provenance (do not silently redistribute restricted data);
- reproducible ingestion and validation;
- SQL analysis plus pandas/NumPy analysis;
- 5–8 purposeful charts;
- findings, uncertainty, bias risks, and next questions;
- a cleaned dataset or instructions to regenerate it.

## Checkpoint

Given an unfamiliar table, produce a data-quality memo and three defensible insights
in 90 minutes. Every claim must be traceable to code.
