# Sentiment Analysis of Netflix Reviews Using RoBERTa and TF-IDF

## Overview

This project performs sentiment analysis on Netflix reviews using two approaches:
1. **Deep Learning**: RoBERTa Transformer-based model.
2. **Traditional Machine Learning**: TF-IDF vectorization with Logistic Regression.

The goal of this project is to classify Netflix reviews into positive and negative sentiments based on user ratings.

## Dataset

The dataset consists of 113,068 Netflix user reviews with the following columns:
- **reviewId**: Unique identifier for each review.
- **userName**: Name of the reviewer.
- **content**: Review text provided by the user.
- **score**: Rating given by the user (1 to 5 stars).
- **thumbsUpCount**: Number of likes (thumbs up) received by the review.
- **reviewCreatedVersion**: The version of the Netflix app when the review was created.
- **at**: Timestamp of the review.
- **appVersion**: The version of the Netflix app being reviewed.

For this project, the dataset is limited to 2,500 samples for training and testing.

## Installation

To get started, clone this repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/netflix-sentiment-analysis.git
cd netflix-sentiment-analysis
pip install -r requirements.txt
