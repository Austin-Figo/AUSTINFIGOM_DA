# Crime Hotspot Prediction

## Overview

An academic machine-learning project intended to analyse historical crime records and identify geographic areas with elevated crime probability.

## Work completed so far

The project owner has confirmed the following work:

- Obtained a crime dataset from an online source.
- Cleaned and organised the records into a structured dataset.
- Performed crime-data analysis and classification-oriented work.
- Defined the objective as identifying areas with a higher probability of crime.

## Reproducibility status

This repository does not yet contain the original dataset, preprocessing code, model implementation, or evaluation outputs. The following details must be recovered from the original project before the work can be described as a validated predictive system:

- Dataset name, source URL, licence, date range, and geographic coverage
- Exact feature columns and target-label definition
- Missing-value, duplicate, and outlier handling
- Geographic aggregation method and spatial resolution
- Model algorithm and hyperparameters
- Train/test strategy, including chronological validation where appropriate
- Confusion matrix, precision, recall, F1-score, and baseline comparison

## Methodological considerations

A hotspot label must be defined using a documented spatial unit and time window. Avoid random splitting when future-period prediction is the goal; use a chronological holdout to reduce temporal leakage. Geographic coordinates should be treated with the dataset's precision and privacy limitations in mind.

## Current status

**In progress — source code and dataset validation required.**

No model accuracy or algorithm is claimed here until the original implementation is inspected and rerun.
