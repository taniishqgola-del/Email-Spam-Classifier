# 📧 Email Spam Detection using Machine Learning

## Project Overview

This project is a Machine Learning and Natural Language Processing (NLP) application designed to classify text messages or emails as **Spam** or **Not Spam (Ham)**. The model analyzes textual content and predicts whether a message is legitimate or potentially unwanted.

The project demonstrates the complete workflow of an NLP-based classification system, from data preprocessing and feature extraction to model training, evaluation, and deployment.

---

## Objectives

* Detect spam messages automatically
* Apply Natural Language Processing techniques
* Compare multiple classification algorithms
* Achieve high precision and reliable predictions
* Deploy the model through an interactive web application

---

## Key Features

* Text Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Extraction using TF-IDF
* Machine Learning Model Training
* Spam Prediction Interface
* Streamlit Web Application
* Model Evaluation and Optimization

---

## Project Structure

```text
Email-Spam-Detection/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── spam.csv
├── requirements.txt
└── README.md
```

### File Description

| File             | Description                    |
| ---------------- | ------------------------------ |
| app.py           | Main Streamlit application     |
| model.pkl        | Trained machine learning model |
| vectorizer.pkl   | Text vectorization model       |
| spam.csv         | Dataset used for training      |
| requirements.txt | Project dependencies           |
| README.md        | Project documentation          |

---

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* WordCloud
* Matplotlib

---

## Data Preprocessing

The following preprocessing steps were applied:

* Text normalization
* Lowercase conversion
* Removal of punctuation
* Stop-word removal
* Tokenization
* Stemming
* Duplicate removal

These steps help improve model accuracy and prediction quality.

---

## Feature Engineering

Text data was converted into numerical format using:

* Bag of Words (BoW)
* TF-IDF Vectorization

These techniques transform textual information into machine-readable features.

---

## Machine Learning Models Evaluated

Several machine learning algorithms were tested and compared:

* Multinomial Naive Bayes
* Bernoulli Naive Bayes
* Gaussian Naive Bayes

Each model was evaluated using classification metrics to determine the most effective solution.

---

## Model Performance

### Evaluation Metrics

* Accuracy
* Precision
* Classification Performance

### Selected Model

**Multinomial Naive Bayes**

The selected model achieved the highest precision and demonstrated reliable spam detection performance.

---

## Application Workflow

1. User enters a message
2. Text is preprocessed
3. TF-IDF vectorization is applied
4. Trained model analyzes the message
5. Prediction is generated
6. Result is displayed as Spam or Not Spam

---

## Deployment

The project includes a web-based interface built using Streamlit, allowing users to test messages in real time.

### Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## Future Enhancements

* Deep Learning Integration
* Real-time Email Filtering
* Multi-language Spam Detection
* Cloud Deployment
* Advanced NLP Models

---

## Conclusion

This project demonstrates the practical implementation of Machine Learning and Natural Language Processing for spam message detection. By combining effective preprocessing techniques with classification algorithms, the system provides accurate and reliable spam filtering capabilities through an easy-to-use web interface.
