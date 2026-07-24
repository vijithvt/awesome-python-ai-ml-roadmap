# Stage 1 — Python Foundations

**Time:** 4–8 weeks  
**Prerequisite:** [Stage 0](00-start-here.md)  
**Goal:** write readable, tested Python programs without tutorial dependence.

## Learn in this order

1. Values, types, operators, input/output
2. Conditions, loops, comprehensions
3. Functions, scope, type hints, docstrings
4. Lists, tuples, dictionaries, sets
5. Files, CSV, JSON, paths
6. Exceptions and logging
7. Modules, packages, environments
8. Classes and data classes
9. Iterators, generators, context managers
10. Testing, debugging, linting, basic complexity
11. HTTP requests and REST API basics

## Primary resources

- [The official Python tutorial](https://docs.python.org/3/tutorial/)
- [Automate the Boring Stuff](https://automatetheboringstuff.com/) for practical
  beginner automation
- [pytest: Get Started](https://docs.pytest.org/en/stable/getting-started.html)
- [Python typing documentation](https://docs.python.org/3/library/typing.html)

Experienced developers may move quickly through syntax, but should still complete
the checkpoint using idiomatic Python, tests, typing, and packaging.

## Practice progression

### Foundations

1. Convert temperatures and validate input.
2. Count word frequencies without external libraries.
3. Implement FizzBuzz, then test boundary cases.
4. Group transactions by category and calculate totals.
5. Validate a password against configurable rules.

### Data and files

1. Parse a log file and summarize status codes.
2. Merge two CSV files by an identifier and report unmatched rows.
3. Recursively find duplicate files using hashes.
4. Transform nested JSON into a flat report.
5. Stream a large text file without loading it fully into memory.

### Software practices

 1. Refactor one script into modules with a CLI entry point.
 2. Add type hints and run a type checker.
 3. Add unit tests for success, edge, and failure cases.
 4. Replace `print` debugging with structured logging.
 5. Consume a public API with timeout, retry, and error handling.

## Build: data quality CLI

Build `datacheck`, a command-line application that:

- accepts CSV or JSON;
- reports schema, duplicates, missing values, and invalid types;
- supports a small YAML/JSON validation configuration;
- writes machine-readable and human-readable reports;
- has tests and useful error messages.

Do not use pandas for the first implementation. Add a pandas adapter after the core
works so you understand both standard-library and data-library approaches.

## Checkpoint

In a 45-minute closed-reference session, implement a small file-processing tool with
functions, exceptions, CLI arguments, logging, and three tests.

**Exit criteria:** you can explain mutability, scope, generators, exceptions,
dependency isolation, test boundaries, and time/space complexity at a practical level.
