# Classification notebooks

Practice projects using pandas, matplotlib and scikit-learn: inspect data, split
training and test rows, fit a classifier and look at its mistakes.

| Notebook | Topic |
| --- | --- |
| [Patient basics](notebooks/patient_basics.ipynb) | Logistic regression, random forest and a majority baseline |
| [Iris](notebooks/iris.ipynb) | Flower species and a small decision tree |
| [Wine](notebooks/wine.ipynb) | Scaling numeric features |
| [Breast cancer](notebooks/breast_cancer.ipynb) | Precision, recall and class errors |
| [Digits](notebooks/digits.ipynb) | Handwritten digit images |
| [Churn](notebooks/churn.ipynb), [equipment](notebooks/equipment.ipynb) | Numeric and categorical columns |
| [Transactions](notebooks/transactions.ipynb), [network](notebooks/network.ipynb) | Label balance and confusion matrices |
| [Spam](notebooks/spam.ipynb), [sentiment](notebooks/sentiment.ipynb) | Text classification with TF-IDF |

## Run

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

Start with `notebooks/patient_basics.ipynb` or `notebooks/iris.ipynb` and run the
cells in order. The patient CSV is at the root; other CSVs are in `datasets/`.
See [dataset notes](datasets/README.md) for sources and [evaluation notes](docs/evaluation.md)
for a short explanation of the scores. These are learning exercises.
