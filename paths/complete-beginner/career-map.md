# Beginner Career and Industry Skills Map

This map converts recurring requirements in employer job descriptions into learning
priorities. It is not a promise that every role is entry-level or that every employer
uses the same title.

## Role comparison

| Skill area | Data Analyst | Junior Data Scientist | Python Automation | ML Engineer | AI/GenAI Engineer |
| --- | :---: | :---: | :---: | :---: | :---: |
| Python | Working | Strong | Strong | Strong | Strong |
| SQL | Strong | Strong | Working | Strong | Working–Strong |
| Spreadsheets/BI | Strong | Working | Helpful | Helpful | Helpful |
| Statistics | Working | Strong | Foundation | Working | Working |
| Classical ML | Awareness | Strong | Helpful | Strong | Working |
| Deep learning | Optional | Working | Optional | Working–Strong | Working |
| Git/Linux | Working | Working | Strong | Strong | Strong |
| APIs/testing | Helpful | Working | Strong | Strong | Strong |
| Cloud | Awareness | Working | Working | Strong | Strong |
| Docker/CI/CD | Optional | Helpful | Working | Strong | Strong |
| Data pipelines | Working | Working | Working | Strong | Working |
| LLM/RAG/evaluation | Optional | Helpful | Helpful | Helpful | Strong |
| Communication/domain framing | Strong | Strong | Strong | Strong | Strong |

**Foundation:** explain and perform a small guided task.  
**Working:** independently complete a normal task.  
**Strong:** design, debug, test and explain trade-offs in a project.

## Evidence employers can inspect

### Data analyst

- complex SQL case study with joins, CTEs and windows;
- decision-focused analysis with appropriate visualization;
- dashboard or reproducible report;
- data-quality checks and clear stakeholder summary.

### Junior data scientist

- analyst evidence plus statistical inference;
- leak-resistant ML pipeline with baseline;
- metric/threshold rationale and error slices;
- experiment or causal-thinking case study where appropriate.

### Python automation developer

- packaged CLI/API with tests and CI;
- file/API/database integration;
- logging, retries, configuration and secrets handling;
- measured reduction of a real manual workflow.

### ML engineer

- training/evaluation pipeline plus tested inference;
- data/model/config versioning;
- container, CI, service metrics and rollback plan;
- latency, throughput, memory and cost evidence.

### AI/GenAI engineer

- software-engineering evidence;
- RAG or model workflow with a fixed evaluation set;
- citation/grounding, abstention and regression tests;
- prompt injection, permissions, privacy, latency and cost controls;
- safe tool calls with validation and approval boundaries.

## Current hiring-signal synthesis

The following signals were observed on official employer/certification pages reviewed
for this repository's July 2026 snapshot:

- Amazon roles repeatedly combine Python/another programming language, SQL,
  statistics or ML, data pipelines, visualization, Git/Linux, cloud and production
  software practices.
- Amazon ML engineering requirements emphasize model deployment, batch/real-time
  processing, containers, CI/CD, APIs, PyTorch/TensorFlow and the full software
  lifecycle.
- IBM describes AI engineering as creating repeatable enterprise AI value in
  collaboration with client, sales and specialist teams; its data roles stress
  communication and trusted data foundations.
- TCS's India AI-career route highlights hands-on Python/SQL and web/API technology,
  skill-first assessment, learning agility and recognized degree/experience
  eligibility for particular hiring programs.
- Google's Professional ML Engineer blueprint combines conventional ML,
  foundation-model applications, Python/SQL literacy, pipelines, MLOps, monitoring,
  responsible AI, data engineering and governance.
- Microsoft/GitHub credential blueprints reinforce Git, repositories,
  collaboration, security and modern development practice as foundational.

See the [JD research method](jd-research-method.md) for links, scope and limitations.

## Skills that beginners often omit

1. Writing clear README and setup instructions
2. SQL beyond basic `SELECT`
3. Testing preprocessing and inference
4. Git branches, review and collaboration
5. Linux/terminal fluency
6. Data licensing and privacy
7. Baselines and error analysis
8. Communication of trade-offs and limitations
9. Deployment and monitoring basics
10. Cost, latency, security and failure handling

## Skills that beginners often over-prioritize

- memorizing many model formulas without implementation;
- learning several deep-learning frameworks;
- collecting cloud certificates before one working project;
- using many agent frameworks before understanding a simple tool loop;
- fine-tuning large models before building an evaluated baseline;
- chasing every new model release.

## Role selection test

Choose the role whose weekly work you want—not only its title.

- Prefer querying, explaining and stakeholder decisions? **Data analyst**
- Prefer experiments, uncertainty and predictive modeling? **Data scientist**
- Prefer reliable software and workflow automation? **Python automation**
- Prefer deployment, pipelines, performance and operations? **ML engineer**
- Prefer AI product workflows, retrieval, evaluation and safety? **AI engineer**

Review 20 current local/target-market JDs before finalizing. Titles vary substantially.
