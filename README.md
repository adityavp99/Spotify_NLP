## Spotify Reviews Sentiment Analysis

### Introduction
The Sentiment Analysis of Spotify App Reviews project focuses on classifying user reviews as positive or negative using Natural Language Processing (NLP) and Machine Learning (ML) techniques.

## Objectives
- Sentiment Classification: Develop ML models to classify user reviews as positive or negative.
- Feature Analysis: Identify key factors influencing user sentiment.
- Performance Evaluation: Assess the accuracy and effectiveness of different ML models.

## Methodology

1. Data Collection: The dataset, "Spotify App Reviews 2022" from Kaggle, includes over 61,000 reviews from the Google Play Store with features like review text, rating, thumbs up count, and developer replies.
2. Data Preprocessing: Reviews were cleaned, tokenized, and transformed to ensure suitability for ML algorithms. Steps included removing stop words, handling punctuation, and stemming.
3. Model Development: Various models including Multinomial Naive Bayes, Logistic Regression, and Random Forest were developed and trained on the preprocessed data.
4. Model Evaluation: Models were evaluated using **accuracy** and **F1-score** to determine their performance in sentiment classification.

## Results

The **Logistic Regression** model achieved the highest **accuracy (0.89)** and a strong **F1-score (0.88)**, indicating superior performance in classifying sentiments compared to other models.
Key features influencing sentiment included the review text and rating.
The model effectively identified positive and negative sentiments, providing reliable insights into user satisfaction.
Conclusion
This project highlights the potential of NLP and ML in analyzing user sentiment, demonstrating that Logistic Regression is particularly effective for this task. The results offer valuable insights for improving the Spotify user experience based on sentiment analysis.

## Future Work
- Dataset Expansion: Incorporate more diverse and extensive datasets covering various timeframes and platforms.
- Feature Enrichment: Add features such as sentiment lexicons, user demographics, and engagement metrics.
- Advanced Models: Explore deep learning models like Recurrent Neural Networks (RNNs) and transformers to capture complex dependencies and context in reviews.
- User Interface: Develop a user-friendly dashboard for real-time sentiment analysis and insights for stakeholders.
