## 1. Practical 1 — `mtcars`

- **Dataset page:** https://github.com/tidyverse/readr/blob/main/inst/extdata/mtcars.csv
- **Direct CSV:** https://raw.githubusercontent.com/tidyverse/readr/main/inst/extdata/mtcars.csv

## 2. Practical 2 — Customer Churn

- **Kaggle dataset:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Download the CSV named similar to `WA_Fn-UseC_-Telco-Customer-Churn.csv`.

> **Note:** The standard dataset has `customerID`, `TotalCharges`, `MonthlyCharges`, `Dependents`, and `tenure`. The manual's `1@#` value in `Dependents` may refer to a modified classroom copy; the standard download may not contain it.

## 3. Practical 3 — Diamonds

- **Dataset page:** https://github.com/mwaskom/seaborn-data/blob/master/diamonds.csv
- **Direct CSV:** https://raw.githubusercontent.com/mwaskom/seaborn-data/master/diamonds.csv

## 4. Practical 4 — HR / People Charm Case

- **HR Analytics dataset page:** https://github.com/RuchitaGarde/Human-Resources-Analytics/blob/master/HR_comma_sep.csv
- **Direct CSV:** https://raw.githubusercontent.com/RuchitaGarde/Human-Resources-Analytics/master/HR_comma_sep.csv

> **Note:** The manual names the file `People Charm case.csv` and appears to use columns such as `lastEvaluation`/`lastEvaluvation`, `department`, `salary`, `numberOfProjects`, and `avgMonthlyHours`. The common HR dataset uses different spellings, such as `last_evaluation`, `sales`, `number_project`, and `average_montly_hours`. Check the headers and rename columns only if needed.

## 5. Practical 5 — HR Classification

Use the same HR dataset as Practical 4:

- **Direct CSV:** https://raw.githubusercontent.com/RuchitaGarde/Human-Resources-Analytics/master/HR_comma_sep.csv

> **Note:** The classification notebook needs a target column such as `left` from the common HR dataset. Results depend on the exact dataset and preprocessing.

## 6. Practical 6 — Microloan / `lendingdata.csv`

- **Kiva crowdfunding dataset:** https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding

> **Note:** The manual lists fields including `rMPI`. This public dataset/version may not contain exactly the same columns or a file named `lendingdata.csv`. Confirm the required file with your teacher if the columns do not match.

## 7. Practical 7 — Webpage Identification Using NLTK

No CSV dataset is necessarily required. Choose a webpage URL and retrieve/process its text as instructed in the notebook.

- **NLTK documentation:** https://www.nltk.org/

## 8. Practical 8 — Spam/Ham NLP

- **UCI SMS Spam Collection:** https://archive.ics.uci.edu/dataset/228/sms+spam+collection
- **Alternative Kaggle dataset:** https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

> **Note:** The UCI download contains a text file with labels and messages. The notebook may expect `spam.csv`; convert or rename the columns to `label` and `message` (or `v1` and `v2`) as needed.

## 9. Practical 9 — Sentiment Analysis NLP

- **UCI Sentiment Labelled Sentences:** https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences

> **Note:** The practical may also run on example sentences if no external dataset is required.
