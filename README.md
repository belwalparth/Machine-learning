# Credit Card Fraud Detection

A notebook-based machine learning project for exploring and classifying credit card transactions as fraudulent or legitimate.

## Project contents

- `Creditcardfraud.ipynb` — end-to-end notebook for data exploration, preprocessing, model training, and evaluation.
- `train.csv` and `test.csv` — training and test data.
- `sample_submission.csv` — example submission structure.
- `playground-series-s6e11.zip` — archived dataset bundle.
- `results.txt` — recorded training metrics.

## Getting started

1. Clone or download this repository and open `Creditcardfraud.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Install the notebook's Python dependencies if they are not already available:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Ensure the CSV files are available in the notebook's working directory, then run the notebook cells in order.

The repository includes the CSV files directly, so the ZIP archive is not required to run the notebook when those files are present.

## Recorded results

`results.txt` reports the following training-set metrics:

- Accuracy: `0.7814`
- F1 score: `0.7775`

These are training metrics, not a measure of performance on a held-out test set. For fraud detection, also consider class imbalance and evaluate with appropriate validation metrics before using a model for real-world decisions.

## Notes

This repository is an educational data science project. The datasets are large; make sure your environment has sufficient memory before loading them. The notebook and recorded metrics are provided for exploration and should not be treated as evidence of production readiness.
