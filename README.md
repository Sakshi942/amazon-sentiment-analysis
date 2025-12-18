📊 Sentiment Analysis of Amazon Product Reviews using DistilBERT

This project demonstrates an end-to-end NLP pipeline for sentiment analysis of Amazon product reviews using a fine-tuned DistilBERT transformer model. The sentiment predictions are further used for dashboard-based insights and visualization.

🔍 Project Overview

The goal of this project is to classify Amazon product reviews into Positive and Negative sentiment using a transformer-based NLP model.
A pre-trained DistilBERT model was fine-tuned on a small labeled subset of reviews to demonstrate supervised sentiment classification. The predicted sentiments are then used to analyze customer feedback trends.

📁 Dataset

Source: Amazon product reviews (CSV format)

Key columns:

Review → customer review text

label → sentiment label (0 = Negative, 1 = Positive)

Predicted_Sentiment → model output sentiment

A small manually labeled subset was used for fine-tuning to demonstrate the NLP pipeline.

⚙️ NLP & Machine Learning Pipeline

Data Loading & Cleaning

Loaded Amazon reviews from CSV

Performed text cleaning (lowercasing, removing special characters, stopwords)

Labeling

Manually labeled reviews as Positive or Negative

Converted labels into numeric format for model training

Tokenization

Used Hugging Face DistilBertTokenizerFast

Converted text into token IDs and attention masks

Model Fine-tuning

Used pre-trained distilbert-base-uncased

Fine-tuned the classification head using Hugging Face Trainer

Trained for 2 epochs on labeled review data

Model Evaluation

Evaluated performance using:

Accuracy

Precision

Recall

F1-score

Used a train-test split for evaluation

Inference & Output Generation

Generated sentiment predictions for all reviews

Saved results to CSV for dashboard integration

📈 Dashboard & Insights

Sentiment predictions were exported and used in Power BI

Dashboard highlights:

Overall positive vs negative sentiment

Product-wise sentiment trends

Brand-level sentiment analysis

🛠 Technologies Used

Python

Hugging Face Transformers

DistilBERT

PyTorch

Pandas & NumPy

Scikit-learn

Power BI (for visualization)

🚀 Future Improvements

Increase labeled dataset size

Add Neutral sentiment using confidence thresholds

Perform hyperparameter tuning

Deploy model as an API

📌 Key Takeaway

This project focuses on practical application of transformer-based NLP, demonstrating how a pre-trained language model can be fine-tuned and integrated into a real-world analytics workflow.







