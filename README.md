# 📄 Document Type Detection using Natural Language Processing (NLP)

## Overview

This project implements a **Document Type Detection** system using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The system automatically classifies news articles into predefined categories based on their textual content.

The project was developed as part of an **NLP Midterm Project** and demonstrates a complete text classification pipeline, including text preprocessing, feature extraction, model training, evaluation, and prediction on unseen documents.

---

## Features

* Text preprocessing pipeline

  * Tokenization
  * Case folding
  * Punctuation removal
  * Stop-word removal
  * Stemming
  * Lemmatization
* Feature extraction

  * Bag of Words (BoW)
  * TF-IDF
* Machine Learning classifiers

  * Naive Bayes
  * Logistic Regression
  * Support Vector Machine (SVM)
* Performance evaluation

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix
* Predict document category for new input text

---

## Dataset

The project uses publicly available news classification datasets.

### BBC News Dataset

Categories:

* Business
* Entertainment
* Politics
* Sport
* Technology

### AG News Dataset

Categories:

* World
* Sports
* Business
* Science & Technology

---

## Project Workflow

```text
Raw Text
     │
     ▼
Text Preprocessing
     │
     ├── Tokenization
     ├── Case Folding
     ├── Remove Punctuation
     ├── Remove Stop Words
     ├── Stemming
     └── Lemmatization
     │
     ▼
Feature Extraction
     │
     ├── Bag of Words
     └── TF-IDF
     │
     ▼
Machine Learning Models
     │
     ├── Naive Bayes
     ├── Logistic Regression
     └── Support Vector Machine
     │
     ▼
Prediction & Evaluation
```

---

## Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* NLTK
* Scikit-learn
* Matplotlib

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Nazmul-Shanto/document-type-detection.git
```

Move into the project directory:

```bash
cd document-type-detection
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Run the Jupyter Notebook or Google Colab notebook:

```bash
Document_Type_Detection.ipynb
```

or execute the Python script:

```bash
python main.py
```

---

## Machine Learning Models

### Naive Bayes

A probabilistic classifier that performs well on text classification tasks using word frequencies.

### Logistic Regression

A linear classification algorithm commonly used for multi-class text classification.

### Support Vector Machine (SVM)

A powerful supervised learning algorithm that finds the optimal decision boundary between document categories.

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics provide a comprehensive comparison of the classifiers.

---

## Sample Categories

### BBC News

* Business
* Entertainment
* Politics
* Sport
* Technology

### AG News

* World
* Sports
* Business
* Science & Technology

---

## Folder Structure

```text
Document-Type-Detection/
│
├── data/
│   ├── BBC/
│   └── AGNews/
│
├── notebooks/
│   └── Document_Type_Detection.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_extraction.py
│   ├── models.py
│   └── prediction.py
│
├── requirements.txt
├── README.md
└── LICENSE
```


## Future Improvements

* Deep learning models (LSTM, GRU, CNN)
* Transformer-based models (BERT, RoBERTa)
* Hyperparameter optimization
* Cross-validation
* Model deployment with Flask or FastAPI
* Web interface for real-time document classification

---

## Learning Outcomes

This project demonstrates practical experience in:

* Natural Language Processing
* Text preprocessing
* Feature engineering
* Machine Learning
* Text classification
* Model evaluation
* Python programming
* Data analysis

---

## Authors

**MD Nazmul Alam Shanto**

Bachelor of Science in Computer Science & Engineering (CSE)

American International University-Bangladesh (AIUB)

---

## License

This project is intended for educational and research purposes.

---

## Acknowledgements

* BBC News Dataset
* AG News Dataset
* NLTK
* Scikit-learn
* Google Colab
* Open-source Python community
