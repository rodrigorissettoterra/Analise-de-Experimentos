# Design of Experiments with Python

> **A statistical modeling study exploring factorial experimental design, effect analysis, significance testing, and response surfaces with Python.**

This repository documents a practical study of **Design of Experiments (DOE)**, focusing on how controlled experiments can be structured and analyzed to understand the influence of multiple factors on an observed response.

<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Statistics-DOE-green" alt="Design of Experiments">
  <img src="https://img.shields.io/badge/Factorial%20Design-2²-purple" alt="Factorial Design">
</p>

---

## The question

When several variables may affect an outcome, changing one factor at a time can hide interactions and require many experiments.

Design of Experiments provides a structured alternative:

> **Which factors matter, how strongly do they affect the response, and do combinations of factors create interaction effects?**

The study uses a factorial design to explore those questions quantitatively.

---

## Analytical workflow

```text
Experimental Factors
        ↓
Factorial Design
        ↓
Observed Responses
        ↓
Statistical Model
        ↓
Effect Estimation
        ↓
Significance Analysis
        ↓
Model Refinement
        ↓
Response Surface
```

---

## Topics explored

- construction of a `2²` factorial design;
- representation of the experiment in a DataFrame;
- graphical exploration of experimental responses;
- statistical model fitting;
- estimation of factor and interaction effects;
- statistical significance analysis;
- Student's t-test concepts;
- model refinement;
- standardized Pareto visualization;
- exploration of the fitted model;
- response-surface visualization;
- color maps for experimental interpretation.

---

## Tools

The study uses libraries from the Python scientific ecosystem, including:

- Pandas;
- NumPy;
- pyDOE2;
- Statsmodels;
- visualization libraries used in the notebook.

---

## Why DOE matters

A/B testing typically compares variants of a treatment.

Factorial Design of Experiments addresses a related but different problem: **understanding several controlled factors and their interactions simultaneously**.

Conceptually:

```text
A/B Test
  ↓
Treatment comparison

Factorial DOE
  ↓
Main effects + interactions
```

This makes DOE especially useful in engineering, industrial experimentation, process optimization, product development, and other environments where multiple controllable factors influence a response.

---

## What this project demonstrates

- statistical reasoning beyond predictive Machine Learning;
- experimental planning;
- interpretation of factor effects;
- interaction analysis;
- hypothesis testing;
- model simplification based on statistical evidence;
- communication of experimental results through visual analysis.

---

## Scope and limitations

This repository is an educational statistical study rather than a production experimentation platform.

The conclusions depend on the assumptions of the experimental design and fitted statistical model. In real applications, experiment randomization, replication, blocking, measurement quality, and operational constraints must also be considered.

---

## Author

**Rodrigo Terra**

Data & AI professional with interests in Data Science, experimentation, statistical modeling, Artificial Intelligence, and decision-support systems.

- GitHub: [Rodrigo Terra](https://github.com/rodrigorissettoterra)
- LinkedIn: [Rodrigo Terra](https://www.linkedin.com/in/rodrigo-rissetto-terra/)
