# Data

Download the public datasets and place them in this folder (or set the `DATA_DIR` environment variable).
On Google Colab the notebooks read from `/content/drive/MyDrive/datasets` instead.

| File | Used by | Source |
|---|---|---|
| `Telco-Customer-Churn.csv` | churn-prediction | [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (rename `WA_Fn-UseC_-Telco-Customer-Churn.csv`) |
| `portfolio.csv`, `profile.csv`, `transcript.csv` | starbucks-offer-response, starbucks-rfm-segmentation | Starbucks Capstone Challenge dataset (Udacity Data Scientist Nanodegree), the three JSON files converted to CSV with `pandas.DataFrame.to_csv()` (keeps the `Unnamed: 0` index column the notebooks drop) |

Expected sizes: portfolio 10 rows, profile 17,000 rows, transcript 306,534 rows, Telco 7,043 rows.
