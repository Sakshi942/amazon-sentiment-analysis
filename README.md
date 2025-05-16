# 📊 Sentiment Analysis of Amazon Product Reviews with AI-Powered Insights Dashboard

This Power BI dashboard analyzes customer sentiments from Amazon product reviews using an AI-powered NLP model. It provides a deep dive into customer feedback trends, helping understand how different products are perceived by users.

## 🔍 Project Overview

This project uses a pre-trained Hugging Face sentiment analysis model to classify Amazon product reviews as **Positive** or **Negative**. The results are visualized in Power BI through interactive charts and KPIs, making it easy to derive actionable insights from large-scale textual data.

## 📁 Data Source

- Dataset: Amazon Product Reviews (CSV)
- Columns used: `brand`, `name`, `reviews.rating`, `reviews.text`, `text_sentiment` (AI-predicted)

---

## 📈 Dashboard Pages

### 📌 Page 1: Overall Customer Sentiment

- **Pie Chart**: Visual breakdown of total positive vs negative reviews.
- **Clustered Column Chart**: Positive vs negative review distribution across top 10 products.
- **KPI Cards**:
  - 📗 Total Positive Sentiment %
  - 📕 Total Negative Sentiment %
- **Slicers**:
  - ⭐ Review Ratings (1–5)
  - 🏷️ Brands

---

### 📌 Page 2: Product Popularity Analysis

- **Top 10 Most Loved Products**: Based on positive sentiment counts.
- **Top 10 Most Hated Products**: Based on negative sentiment counts.
- **KPI Card**: Average Customer Rating
- **Slicers**:
  - ⭐ Review Ratings
  - 🏷️ Brands

---

## 🛠 Technologies Used

- **Power BI** for interactive visualizations
- **Python** + **Hugging Face Transformers** for sentiment analysis
- **Pandas** for data cleaning and processing

---

## 🌟 Key Insights

- Discover which Amazon products are loved the most.
- Identify negatively perceived products quickly.
- Filter customer sentiment by brand and rating.

---

## 📎 File

- `Amazon_Sentiment_Dashboard.pbix` — Power BI report file

---

## 📌 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Interact with slicers and visuals to explore the data.
3. Gain insights into what drives customer satisfaction or dissatisfaction.

---

## 🙋‍♀️ Author

**Sakshi** – Aspiring Data Analyst | Passionate about turning data into actionable insights 🌸

---






