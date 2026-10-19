# Deep Learning for Hypertension Progression and Heart Failure Risk Prediction

## Overview
This research project explores whether deep learning models can use blood-pressure time series, physiological signals, and clinical features to support prediction of hypertension progression and heart-failure risk.

The project is at the proposal/prototype stage. No clinical performance claims are made; model results will be reported only after experiments are completed and validated.

## Research questions
- Can temporal patterns in blood-pressure measurements improve prediction of cardiovascular risk compared with suitable baseline models?
- How do LSTM, one-dimensional CNN, and Transformer models compare on the selected datasets?
- Which input features contribute most to model predictions, and how reliably do the models generalize?

## Planned approach
1. Identify appropriate public, de-identified datasets and review their access conditions.
2. Document inclusion criteria, prediction targets, and train/validation/test splits before modelling.
3. Clean and preprocess time-series data; document missing-data handling and any class-balancing methods.
4. Establish simple baseline models before evaluating deep-learning architectures.
5. Evaluate discrimination, calibration, and error using metrics appropriate to each prediction task.
6. Use explainability methods where suitable and document limitations and potential data leakage.
7. Publish reproducible code and report results transparently.

## Candidate model families
- LSTM networks for sequential patterns
- 1D-CNN models for local waveform patterns
- Transformer-based models for longer-range temporal relationships
- Baselines such as logistic regression and tree-based models

These are planned candidates, not claims that the models have already been trained or validated.

## Planned evaluation
Metrics will depend on the final dataset and target. Candidate metrics include AUROC, AUPRC, sensitivity, specificity, calibration/Brier score, and MAE/RMSE for regression tasks. Splits will be designed to reduce leakage, and external validation will be pursued where feasible.

## Data and ethics
Use only datasets whose terms permit the intended research. Follow each dataset's access, attribution, privacy, and publication requirements. Do not upload patient-level data, credentials, private keys, or personally identifiable information to this repository. This project is research software, not a clinical diagnostic tool.

## Repository status
**Status:** Research planning and initial repository setup.

Planned next steps:
- [ ] Select and document datasets
- [ ] Define prediction targets and cohort criteria
- [ ] Add reproducible preprocessing scripts
- [ ] Implement baseline models
- [ ] Implement and compare deep-learning models
- [ ] Add evaluation and explainability notebooks
- [ ] Document experiments and limitations

## Suggested repository structure
```text
.
├── data/
│   └── README.md
├── docs/
│   └── research-plan.md
├── notebooks/
├── src/
│   └── README.md
├── tests/
├── .gitignore
└── README.md
```

## Disclaimer
This repository is for research and educational purposes only. It does not provide medical advice, diagnosis, or treatment recommendations.
