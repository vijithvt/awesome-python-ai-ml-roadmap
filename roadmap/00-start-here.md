# Stage 0 — Start Here

**Time:** 1–2 weeks  
**Goal:** establish a reproducible workflow before studying models.

## Outcomes

You can use a terminal, create an isolated Python environment, work with Git, run
tests, read documentation, and explain safe use of data and AI.

## Setup

Install:

- [Python](https://www.python.org/downloads/) (a currently supported release)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [VS Code](https://code.visualstudio.com/docs/python/python-tutorial) or another editor
- [uv](https://docs.astral.sh/uv/getting-started/installation/) or Python `venv`

Cloud alternative: [Google Colab](https://colab.research.google.com/) when local
installation or GPU access is a barrier. Learn local environments before production.

## Learn and do

1. **Terminal:** navigate, create files/directories, inspect processes, and use pipes.
   Use [The Missing Semester](https://missing.csail.mit.edu/) selectively.
2. **Git:** initialize, stage, commit, branch, merge, pull, and resolve one conflict.
   Use [Pro Git chapters 1–3](https://git-scm.com/book/en/v2).
3. **Environment:** create a project with `pyproject.toml`, an isolated environment,
   dependency lock, `.gitignore`, and README.
4. **Notebook vs module:** use notebooks for exploration and `.py` modules for
   reusable/tested logic.
5. **Responsible work:** never commit secrets or personal data. Read the
   [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
   overview and [Google's Rules of ML](https://developers.google.com/machine-learning/guides/rules-of-ml).

## Build: reproducible starter repository

Create a repository containing:

```text
src/
tests/
notebooks/
data/README.md
.env.example
.gitignore
pyproject.toml
README.md
```

Add a script that reads a CSV path from the command line, prints its row/column
count, and reports missing values. Add one unit test and setup/run instructions.

## Exercises

1. Make five meaningful commits instead of one bulk commit.
2. Create and merge a feature branch.
3. Remove a deliberately added secret from the latest unpushed commit.
4. Recreate the environment from the repository instructions.
5. Explain why a notebook that runs only with hidden cell state is not reproducible.

## Checkpoint

Give the repository to another person—or use a clean temporary directory. They
should be able to clone, install, test, and run it using only the README.

**Evidence:** repository URL, passing test output, and a 150-word reflection.
