# Entropy as an Interpretable Signal in Network Traffic

## Overview

This project explores Shannon entropy as a simple, interpretable signal for identifying anomalous port usage in network traffic.  
Using synthetic data, it demonstrates how entropy can highlight deviations from expected behaviour without relying on machine learning models.

The aim is not detection performance, but understanding.

---

## Why this matters (defensive context)

In security monitoring, complexity is often introduced prematurely through machine learning, even when simpler signals may already reveal useful structure.

Entropy provides:
- a compact summary of distributional behaviour
- an interpretable scalar signal
- a lightweight baseline for exploratory analysis or feature design

This project illustrates how such a signal behaves in controlled conditions.

---

## Approach

- Generate synthetic network traffic representing:
  - normal, concentrated port usage
  - anomalous or diffuse port usage
- Compute Shannon entropy over port distributions
- Compare entropy values across scenarios
- Visualise differences using simple plots

No model fitting or threshold optimisation is performed.

---

## Repository contents

- A single Jupyter notebook containing:
  - synthetic data generation
  - entropy computation
  - visualisation and discussion
- Minimal helper functions used directly within the notebook

---

## Outputs

Key outputs include:
- side-by-side comparisons of low-entropy vs high-entropy port usage
- discussion of when entropy is informative and when it is not

---

## Limitations & boundaries

- Data is synthetic and simplified
- No claims are made about operational deployment
- Entropy alone is not sufficient for detection; it is a signal, not a solution

---

## Design choice note

This project intentionally avoids machine learning to emphasise that:
- interpretable statistical signals can surface structure directly
- simple baselines should be explored before reaching for complex models

---

## Ethics & use

All data are synthetic.  
This work is defensive in nature and intended for learning, analysis and feature exploration.

