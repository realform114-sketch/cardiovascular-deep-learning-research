# Research Plan

## Working title
Deep Learning for Hypertension Progression and Heart Failure Risk Prediction

## Problem
Office-based blood-pressure measurements may not represent temporal variability throughout daily life. This project will investigate whether time-series blood-pressure information, physiological signals, and relevant clinical features can support cardiovascular risk prediction.

## Proposed methodology
- Conduct a focused literature review and document dataset selection.
- Define prediction targets and time horizons before model training.
- Apply signal-quality checks and preprocessing appropriate to each dataset.
- Establish baseline models, then compare LSTM, 1D-CNN, and Transformer approaches where the data support them.
- Evaluate discrimination, calibration, error, and generalization.
- Use explainability methods cautiously and report their limitations.

## Reproducibility and safeguards
- Record dataset versions, access conditions, preprocessing choices, random seeds, and software versions.
- Keep patient-level data and secrets out of version control.
- Avoid data leakage between training, validation, and test sets.
- Report negative or inconclusive results as well as positive findings.
- Do not describe a model as clinically validated without appropriate evidence.

## Current status
This document describes a planned study. Dataset selection, implementation, and validation remain to be completed.
