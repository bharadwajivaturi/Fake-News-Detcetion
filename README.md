# Fake News Detcetion
Short Description

- A machine learning-based application that classifies news articles as "fake" or "true" using Natural Language Processing (NLP) and Logistic Regression.

# Features
- **Text Classification:** Analyzes news content to detect fake vs real news.
- **Batch Processing:** Supports CSV uploads for bulk prediction.
- **Interactive Web Interface:** Built with Streamlit for easy user interaction.
- **Model Performance:** Achieves high accuracy with detailed evaluation metrics.

# Technical Implementation
- Combined and shuffled Fake and True news datasets.

Preprocessed text by:
- Converting to lowercase.
- Removing punctuation.
- Eliminating stopwords.
- Handling duplicates and missing values.

# Model Architecture
- **Vectorization:** TF-IDF for feature extraction.
- **Classifier:** Logistic Regression.
- **Evaluation:** Accuracy score, confusion matrix, and classification report.

# Performance
- **Training Accuracy:** High performance on training data.
- **Test Accuracy:** Strong generalization to unseen data.

# Usage
- **Single Prediction:** Enter a news headline for instant classification.
- **Batch Processing:** Upload a CSV file with a 'text' column for multiple predictions.
- **Results:** Download predictions with confidence scores.
