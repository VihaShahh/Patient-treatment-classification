# Classification notebooks

Small pandas and scikit-learn exercises, starting with patient classification.

Install the notebook dependencies with `python -m pip install -r requirements.txt`.
Examples live in `notebooks/`.

## Examples

- [Patient Basics](notebooks/patient_basics.ipynb)
- [Iris](notebooks/iris.ipynb)
- [Wine](notebooks/wine.ipynb)
- [Breast Cancer](notebooks/breast_cancer.ipynb)
- [Digits](notebooks/digits.ipynb)
- [Churn](notebooks/churn.ipynb)
- [Equipment](notebooks/equipment.ipynb)
- [Transactions](notebooks/transactions.ipynb)
- [Network](notebooks/network.ipynb)
- [Spam](notebooks/spam.ipynb)
- [Sentiment](notebooks/sentiment.ipynb)

## Run

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

Open a notebook under `notebooks/` and choose **Run All Cells**. Start with
`patient_basics.ipynb`.
