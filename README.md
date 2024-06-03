# Customer Sentiment Analysis

This NLP Analysis project focuses on harnessing the power of customer feedback to drive business improvements. Applying advanced natural language processing techniques, the primary objectives involve data cleaning, topic identification, sentiment analysis, and keyphrase extraction on Amazon cell phone reviews.

![NLP](https://github.com/mhadeli/Sentiment_Analysis/assets/58530203/66a40638-b053-4a3b-bc8d-79fb688ab81e)



## Task Overview

Using Natural Language Processing (NLP) techniques, this project aims to help businesses utilize customer reviews in order to improve their products and services. By swiftly analyzing a large volume of data from reviews, we can extract meaningful insights and recognize the prevalent topics, trends, and sentiments.

### Main Objectives:

- **Data Cleaning**: Cleaning and preprocessing the customers' reviews.
- **Topic Identification**: Recognizing common topics and trends in the reviews.
- **Sentiment Analysis**: Analysing the sentiments behind each review.
- **Key Phrase Extraction**: Extracting significant phrases and terms from reviews.
- **Modelling**: Building models using Random Forests and Simpletransformers to predict various insights.
- **Evaluation**: Assessing the performance of the developed models.

## Dataset Information

The dataset is sourced from Kaggle and it comprises over 67,000 reviews of cell phones purchased from Amazon.

### Dataset Columns:

| No. | Column Name    | Description                                                   |
|-----|----------------|---------------------------------------------------------------|
| 1   | asin           | Amazon Standard Identification Number used for inventory tracking.  |
| 2   | name           | Reviewer Name                                                   |
| 3   | rating         | Reviewer Rating (scaled from 1 to 5)                          |
| 4   | date           | Review Date                                                    |
| 5   | verified       | Indicates if the reviewer is a verified customer              |
| 6   | title          | Review Title                                                   |
| 7   | body           | Review Content                                                 |
| 8   | helpfulVotes   | Count of feedbacks marked as helpful                           |
