# Resume Project Writer

## Purpose

Turn raw descriptions of technical projects into concise, technically accurate, and strong resume bullet points.

The goal is to communicate what the user actually built, how they built it, and what result they achieved without exaggerating their experience.

## When to use

Use this skill when the user wants to:

* describe a project on a resume;
* improve existing project bullet points;
* adapt a project description for an internship;
* emphasize ML, backend, data, or software engineering experience;
* shorten a long project description;
* make technical achievements easier for recruiters to understand;
* select the most valuable details from a project.

## Workflow

### 1. Understand the project

Extract the important facts:

* What problem was solved?
* What did the user personally implement?
* Which technologies were used?
* Which algorithms or models were used?
* How was the solution evaluated?
* What measurable result was achieved?
* What engineering decisions were important?

Do not start rewriting until the technical contribution is understood.

### 2. Identify the strongest signals

Prioritize information that demonstrates:

* technical depth;
* practical implementation;
* measurable results;
* experimentation;
* engineering responsibility;
* understanding of validation and evaluation;
* performance improvements;
* real-world constraints.

Remove details that do not help evaluate the candidate.

### 3. Build each bullet around a contribution

Prefer the structure:

**Action + technical approach + result**

For example:

> Built a time-series forecasting pipeline using LightGBM with lag and calendar features, evaluated with walk-forward validation and achieved an RMSLE of X.

Another valid structure is:

**Problem + implementation + impact**

Use whichever reads more naturally.

### 4. Make technologies specific

Prefer:

> LightGBM, pandas, scikit-learn

instead of:

> machine learning technologies

Prefer:

> walk-forward cross-validation

instead of:

> tested the model carefully

Use concrete technical terms when they accurately describe the work.

### 5. Include metrics when available

Good metrics include:

* validation score;
* accuracy;
* F1;
* ROC-AUC;
* RMSLE;
* RMSE;
* latency;
* memory usage;
* throughput;
* dataset size;
* training speed;
* percentage improvement.

Never invent metrics.

If no quantitative result exists, describe the technical outcome instead.

### 6. Adapt to the target role

For ML positions, prioritize:

* datasets;
* feature engineering;
* validation;
* models;
* metrics;
* experiments;
* data leakage prevention;
* model comparison.

For software engineering positions, prioritize:

* architecture;
* APIs;
* performance;
* testing;
* databases;
* concurrency;
* deployment;
* reliability.

Only emphasize technologies and experience that actually exist in the project.

### 7. Remove weak wording

Avoid phrases such as:

* worked on;
* participated in;
* familiar with;
* helped with;
* used different technologies;
* successfully developed;
* interesting project.

Replace them with concrete actions when justified:

* implemented;
* designed;
* trained;
* evaluated;
* optimized;
* built;
* integrated;
* automated;
* analyzed.

## Rules

* Never invent technologies, metrics, responsibilities, or achievements.
* Never make the project sound larger than it actually was.
* Do not describe team achievements as personal achievements unless the user was responsible for them.
* Prefer concrete technical details over adjectives.
* Avoid buzzword-heavy language.
* Avoid excessive claims such as "state-of-the-art" unless objectively justified.
* Do not list every library used in the project.
* Focus on technologies that demonstrate relevant skills.
* Preserve important ML terminology when applying for ML roles.
* Keep bullet points concise.
* Avoid repeating the same action verb in consecutive bullets.
* Use past tense for completed projects and present tense for ongoing projects.
* Keep terminology consistent across the resume.

## Recommended project structure

A strong project usually needs 2–4 bullet points.

### Bullet 1 — Project and problem

Explain what was built and what task it solves.

### Bullet 2 — Technical implementation

Describe the main models, architecture, algorithms, or engineering decisions.

### Bullet 3 — Evaluation or experimentation

Describe validation, testing, comparison, optimization, or experiments.

### Bullet 4 — Result

Include the strongest measurable result when one exists.

Do not force four bullets if the project does not contain enough meaningful information.

## ML project example

Raw description:

> I participated in Kaggle Store Sales. I used LightGBM and made different time features and lag features. Then I tested models on different periods and combined several models.

Possible resume version:

* Built a time-series forecasting pipeline for the Kaggle Store Sales dataset using LightGBM with lag, rolling, promotion, and calendar features.
* Implemented walk-forward cross-validation to reproduce the competition forecasting horizon and reduce temporal leakage.
* Compared multiple model configurations and combined predictions using validation-based ensemble weights.
* Achieved an RMSLE of X on the final validation setup.

The value of `X` must only be included if it was provided or verified.

## Output format

When rewriting a project, provide:

1. Recommended final version
2. Optional shorter version if space is limited
3. Brief explanation of major changes when useful

Do not provide many alternative phrasings unless the user asks for them.
