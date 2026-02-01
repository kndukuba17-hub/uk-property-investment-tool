# 🛍️ Retail Sales & Customer Sentiment Pipeline

## 📌 Business Overview
In high-volume B2C retail (like Boots UK or Pharmica), analysing sales data alongside customer feedback is critical for maximizing revenue.

This project is an **end-to-end data pipeline** that:
1.  **Generates realistic sales data:** Simulates transaction logs with messy real-world attributes (missing values, dates).
2.  **Calculates Revenue Metrics:** Identifies top-performing categories and high-value products.
3.  **Applies NLP (Natural Language Processing):** Uses `TextBlob` to automatically classify customer reviews as Positive, Neutral, or Negative.
4.  **Visualizes ROI:** Produces actionable charts for stakeholders to identify quality control issues immediately.

## 🛠️ Tech Stack
* **Core:** Python 3.10
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning/NLP:** TextBlob (Sentiment Polarity Scoring)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebooks

## 📊 Key Insights Generated
* **Automated Quality Control:** The script flags products with a Net Sentiment Score below -0.1 for immediate review.
* **Revenue Optimization:** Aggregates sales data to highlight "Cash Cow" categories vs. underperforming stock.
* **Data Cleaning:** features robust handling of `Null` values in unstructured text data.

## 🚀 How to Run
1.  Open the `Retail_Analysis_Pipeline.ipynb` file in this repository.
2.  Click the **"Open in Colab"** badge (if visible) or download to run locally.
3.  The script will generate mock data automatically—no external CSV download required.
