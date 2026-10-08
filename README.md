# Data School — University of Silesia, Katowice

This repository contains our group project from the summer school at the **University of Silesia in Katowice**. We worked together on an insurance dataset to practise data analysis, statistical testing and machine learning in Python.

**Team:** [Talha Shahzad](https://github.com/Draxo659) and [Keshav Sarmoria](https://github.com/Keshav02-rk).

## What we did

1. **Data preparation and exploration:** Checked data quality, removed duplicates, created new features and explored patterns through graphs.
2. **Hypothesis testing:** Used one-sample and two-sample t-tests, plus a chi-square test, to investigate charges and smoking patterns.
3. **Regression:** Estimated medical charges with linear regression and predicted smoking status with logistic regression.
4. **Decision trees:** Compared tree settings, evaluated predictions and explained the model’s decision rules.
5. **Clustering:** Tested different numbers of K-means clusters and interpreted the selected groups using elbow and silhouette results.

The repository includes five Jupyter notebooks with saved results and our final PowerPoint presentation

## Datasets and source

| File | Description |
| --- | --- |
| `insurance.csv` | Original dataset: 1,338 rows and 7 columns. |
| `insurance_cleaned.csv` | Final cleaned data: 1,337 rows, with one duplicate removed and BMI category and dependent-status features added. |
| `insurance_preprocessed.csv` | Final encoded and scaled version: 1,337 rows and 17 columns. |

Keep the CSV files alongside the notebooks when running them. Our preparation steps are documented in the first notebook.

**Source:** [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance), shared on Kaggle by **Miri Choi (mirichoi0218)**. Kaggle also credits the [Machine Learning with R datasets](https://github.com/stedy/Machine-Learning-with-R-datasets) associated with Brett Lantz’s book.

**Dataset licence:** Kaggle lists “Database: Open Database, Contents: Database Contents”. The original and our derived CSV datasets are shared under the [Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/odbl/1-0/), with their contents under the [Database Contents License (DbCL) v1.0](https://opendatacommons.org/licenses/dbcl/1-0/). These dataset terms do not license the project code or presentation.
