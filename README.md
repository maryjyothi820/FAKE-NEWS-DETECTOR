## Overview

The Fake News Detection System is a Machine Learning and Natural Language Processing (NLP) based application designed to classify news articles as either Real or Fake. The system analyzes textual content, extracts meaningful features using TF-IDF vectorization, and applies machine learning algorithms to identify misinformation with high accuracy.

This project demonstrates the complete machine learning workflow, including data collection, preprocessing, feature engineering, model training, evaluation, and deployment through a web-based interface.

---

## Features

- Detects whether a news article is Real or Fake
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Machine Learning-based classification
- Real-time prediction through a Flask web application
- User-friendly interface for news verification

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Flask
- HTML
- CSS

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Text Feature Extraction using TF-IDF
4. Model Training
5. Model Evaluation
6. Web Application Development
7. Real-Time Prediction

---

## Dataset

- Fake News Dataset
- Approximately 45,000+ labeled news articles
- Dataset Size: ~20 MB

---

## Machine Learning Pipeline

### Data Preprocessing
- Lowercase conversion
- Removal of punctuation and special characters
- Stop-word removal
- Tokenization

### Feature Engineering
- TF-IDF Vectorization
- Text representation and weighting

### Model Training
- Logistic Regression
- Naive Bayes
- Random Forest (for comparison)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

---

## Performance

| Metric | Score |
|----------|----------|
| Accuracy | 94.2% |
| Precision | 93.8% |
| Recall | 94.5% |
| F1 Score | 0.94 |

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Open the browser and visit:

```text
http://127.0.0.1:5000
```

---

## Future Enhancements

- Deep Learning Models (LSTM, BERT)
- Multi-language Fake News Detection
- Cloud Deployment
- Real-Time News Monitoring
- Browser Extension Integration

---

## Project Outcome

Successfully developed an NLP-based fake news classification system capable of identifying misleading news articles with high accuracy. The project demonstrates practical applications of Machine Learning and Natural Language Processing in combating misinformation.

---

## Author

**Meri Jyothi Kandula**

- GitHub: https://github.com/maryjyothi820
- LinkedIn: https://www.linkedin.com/in/meri-jyothi/
- LeetCode: https://leetcode.com/u/Jyothi-kandula/
