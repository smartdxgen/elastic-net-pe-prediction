# elastic-net-pe-prediction
Elastic-Net Logistic-Regression Model for Predicting Pulmonary Embolism 
# Interpretable Prediction of Pulmonary Embolism in Patients Undergoing CTPA

## Overview

This repository contains the analysis code for a retrospective multicentre study developing and internally evaluating an interpretable elastic-net logistic regression model to estimate the probability of computed tomography pulmonary angiography (CTPA)-confirmed pulmonary embolism (PE) among adults with suspected PE who underwent CTPA.

The study was conducted using data from three emergency departments affiliated with Mashhad University of Medical Sciences.

## Objectives

The code supports:

- Development of an elastic-net logistic regression model.
- Predictor preprocessing and standardisation.
- Hyperparameter selection using cross-validation.
- Probability calibration, where applicable.
- Internal validation using bootstrap optimism correction.
- Evaluation of model discrimination and calibration.
- Generation of tables and figures reported in the manuscript.

The final implementation and analysis procedures should be verified against the published manuscript and the scripts in this repository.

## Repository Contents

- `src/`: Model development and analysis code.
- `scripts/`: Scripts for running analyses and generating results.
- `requirements.txt`: Python dependencies.
- `results/`: Selected non-sensitive outputs, if included.

File names and directory descriptions should be updated to reflect the actual repository contents.

## Requirements

Python 3.x and the packages required by the analysis scripts are needed to run the code. The exact Python version and package versions should be specified after the computational environment has been verified.

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Reproducibility

The analysis scripts document the computational procedures used for model development and evaluation. Reproduction of the reported results requires access to the underlying study dataset and the specified computational environment.

Where patient-level data cannot be publicly shared because of ethical, institutional, or confidentiality restrictions, the repository provides code without distributing the underlying clinical data.

## Data Availability and Patient Confidentiality

Patient-level clinical data are not included in this repository. Access to the underlying data, if permitted, is subject to the relevant institutional approvals, ethical requirements, and data-access policies.

## Intended Use

This repository is intended for research transparency and methodological reproducibility. The model has been evaluated in a population of patients referred for and undergoing CTPA. Its performance should not be assumed to generalise to all emergency-department patients with suspected PE without further validation.

The model is a research tool and is not intended to replace clinical assessment or established diagnostic pathways.

## License

A license will be specified by the authors. Until a license is added, reuse and redistribution of the code should not be assumed to be permitted.

## Contact

For questions about the methodology or code, please contact the corresponding author listed in the associated manuscript.
