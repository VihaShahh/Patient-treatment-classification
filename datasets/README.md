# Dataset notes

`../patient_data.csv` has 4,412 rows. `SOURCE` is the recorded in/out
care label, not a treatment recommendation. The source attribution is
[this Kaggle dataset](https://www.kaggle.com/datasets/saurabhshahane/patient-treatment-classification).
Collection details, measurement units and redistribution rights are unverified.

## Columns

Patient predictors are nine blood-count/age measurements and the recorded `SEX` value.
The label `SOURCE` is excluded from the feature matrix. Numeric missing values are
filled using training medians; `SEX` is one-hot encoded in the training pipeline.

Additional tabular CSVs use `label` as their target. Text files use `message` and `label`.
The first cells of each notebook show the actual columns and class counts.
