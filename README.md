# Python Data Analytics & NLP Lab Practicals

This repository contains nine separate Jupyter notebooks based on the uploaded lab manual.

## Practicals
1. `01_mtcars_analysis.ipynb` — dataset inspection, histogram, modal interval, scatter plot.
2. `02_churn_data_cleaning.ipynb` — churn data quality and summary statistics.
3. `03_diamond_visualization_regression.ipynb` — diamond plots, frequency table, linear regression.
4. `04_hr_people_charm_eda.ipynb` — HR exploratory data analysis.
5. `05_hr_classification_models.ipynb` — Logistic Regression and KNN.
6. `06_lendingdata_analysis.ipynb` — microloan dataset analysis.
7. `07_webpage_identification_nltk.ipynb` — webpage text extraction and keyword-based topic inference.
8. `08_spam_ham_nlp.ipynb` — TF-IDF + Naive Bayes spam detection.
9. `09_sentiment_analysis_nlp.ipynb` — NLTK VADER sentiment analysis.

## Setup
Python 3.10+ is recommended.

```bash
python -m venv .venv
# Windows PowerShell:
.venv\Scripts\Activate.ps1
# macOS/Linux:
# source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Open notebooks from the `notebooks/` folder. Run each notebook from top to bottom.

## Dataset files
The lab-manual PDF lists datasets but does not include the underlying CSVs. Place the original files in `data/`:
- `mtcars.csv`
- `Churn.csv` (or update the path in notebook 02)
- `diamond.csv` (the diamond notebook can attempt a seaborn fallback)
- `People Charm case.csv`
- `lendingdata.csv`
- `spam.csv` with `label,message` columns, or common `v1,v2` columns

Keep original dataset column names where possible. Update the `csv_path` variable if your file names differ. Notebooks deliberately calculate results from the supplied data rather than hard-coding unverified numbers.

## Notes
- Regression is evaluated with R², MAE, and RMSE; classification accuracy is not the appropriate primary metric for regression.
- The HR classification notebook attempts to detect a target column named `left`, `turnover`, `churn`, or `attrition`. If your file uses another target name, update that cell.
- The webpage practical requires an internet connection and may fail on sites that block automated access.
- Do not commit private, licensed, or sensitive datasets to a public repository unless you have permission.
