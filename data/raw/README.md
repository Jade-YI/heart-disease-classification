# Raw data

## Dataset

**Dataset name:** Stroke Prediction Dataset  
**File:** `healthcare-dataset-stroke-data.csv`  
**Source:** <https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset>  
**Date accessed:** 2026-09-20

The dataset contains 5,110 observations and 12 variables describing
demographic, clinical, and lifestyle characteristics together with
recorded stroke status.

Each row represents one individual. The variable `stroke` is coded as:

- `0`: no recorded stroke;
- `1`: recorded stroke.

## Raw-data policy

The CSV file in this directory is preserved in its original downloaded
form and must not be edited manually.

All variable renaming, recoding, missing-value handling, exclusions,
and derived variables will be implemented in R code. Cleaned datasets
will be written to `data/processed/`.

## Important limitations

The dataset does not provide information about the sampling frame,
recruitment dates, stroke dates, follow-up time, or the timing of
clinical measurements relative to stroke.

It should therefore be used for data-quality assessment and descriptive
analysis, not for estimating stroke incidence or causal effects.