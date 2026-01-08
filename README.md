# 🕵️‍♂️ Fake News Detector

## 📌 About the Project
This project is a **Machine Learning** implementation designed to detect whether a news article is **Real (Fact)** or **Fake (Hoax)**.

Built using Python, this system utilizes **Natural Language Processing (NLP)** techniques for text processing and the **Logistic Regression** algorithm for classification. This project was created as part of a Data Science study focusing on *Text Classification*.

## 📂 Dataset
The dataset used consists of two main CSV files:
https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets
1.  `True.csv`: Contains real/factual news articles (majority sourced from Reuters).
2.  `Fake.csv`: Contains fake/hoax news articles.

The data includes the news title, text content, subject, and publication date.

## 🛠️ Tech Stack & Methodology
The project pipeline follows these steps:

1.  **Data Cleaning:** Removing punctuation, URLs, special characters, and converting text to lowercase.
2.  **Preprocessing:** Merging datasets and shuffling data to prevent bias.
3.  **Feature Extraction:** Using **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical vectors.
4.  **Modeling:** Training the model using the **Logistic Regression** algorithm.
5.  **Evaluation:** Measuring performance using Accuracy Score and F1-Score.

## 📊 Evaluation Results
Based on testing using the test set (25% of total data), the model achieved highly satisfactory results:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **98%** |
| **F1-Score** | **98%** |

The model successfully distinguishes the formal language patterns found in real news versus the emotional/clickbait language often used in fake news.
