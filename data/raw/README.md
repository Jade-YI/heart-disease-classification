# Raw data

## Dataset

**Dataset name:** Heart Failure Prediction Dataset  
**File name:** `heart.csv`  
**Curator:** Federico Soriano  
**Source:** <https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction>  
**Date accessed:** 2026-09-19

## Important outcome definition

Despite the name of the Kaggle dataset, the outcome variable
`HeartDisease` represents the presence or absence of heart disease.

It does not represent:

- incident heart failure during follow-up;
- heart-failure mortality;
- time-to-event data;
- treatment effectiveness or safety.

This project is therefore framed as a cross-sectional clinical
classification study rather than a heart-failure prediction study.

## Data provenance

The Kaggle dataset combines observations from five pre-existing heart
disease datasets:

- Cleveland;
- Hungarian;
- Switzerland;
- Long Beach VA;
- Statlog Heart.

The combined dataset contains 918 observations and 11 candidate
predictors, plus the binary outcome `HeartDisease`.

Several component datasets originate from the UCI Heart Disease
collection:

<https://archive.ics.uci.edu/dataset/45/heart+disease>

Original UCI citation:

> Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989).
> Heart Disease [Dataset]. UCI Machine Learning Repository.
> <https://doi.org/10.24432/C52P4X>

## Raw-data policy

The file stored in this directory is treated as immutable raw data.

It must not be edited manually. All cleaning, recoding, exclusion, and
imputation decisions will be implemented in R code so that the analysis
can be reproduced from the original file.