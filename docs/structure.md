# Notebook structure

Each example loads a dataframe, separates features from labels, reserves test
rows and fits a scikit-learn model. Pipelines keep imputation, scaling, encoding
and text vocabulary fitting on training rows. The model then predicts the test
rows for the score table and confusion matrix.

The patient CSV stays at the root. Other CSVs are in `datasets/`; benchmark
loaders use the installed scikit-learn data. Notebook outputs are calculated
when the cells run.
