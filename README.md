# Fake_News_Detection
# Fake News Detection using Machine Learning

A machine learning-based Fake News Detection system that leverages Natural Language Processing (NLP) techniques to classify news articles as **Real** or **Fake**. The project applies text preprocessing, feature extraction using TF-IDF, and multiple supervised learning algorithms to build an accurate and efficient classification model.

---

## Project Overview

The rapid spread of misinformation on digital platforms has become a major challenge in today's world. This project aims to automatically identify fake news articles using machine learning techniques, helping users distinguish between genuine and misleading information.

The system preprocesses textual data, converts it into numerical representations using TF-IDF, and trains multiple classification models to determine whether a news article is real or fake.

---

## Objectives

- Detect fake news articles using Machine Learning.
- Perform Natural Language Processing (NLP) on textual data.
- Compare the performance of multiple classification algorithms.
- Evaluate models using standard performance metrics.
- Build an automated fake news prediction pipeline.

---

## Dataset

The project uses a labeled news dataset containing:

- Real News Articles
- Fake News Articles

Each record contains the news title and article content along with its corresponding label.

---

## Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Model Evaluation
7. News Prediction

---

## Text Preprocessing

The following preprocessing techniques were applied:

- Lowercase conversion
- Removal of punctuation
- Removal of special characters
- Removal of stop words
- Stemming using Porter Stemmer
- Tokenization
- TF-IDF Vectorization

---

## Models Used

The following machine learning algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting Classifier

---

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **91.21%** |
| Decision Tree | Evaluated |
| Random Forest | Evaluated |
| Gradient Boosting | Evaluated |

**Best Performing Model:** Logistic Regression

---

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Matplotlib
- TF-IDF Vectorizer

---

## Project Structure

```text
Fake_News_Detection/
│
├── Dataset/
│   ├── Fake.csv
│   └── True.csv
│
├── FAKE_NEWS_DETECTION.ipynb
├── requirements.txt
├── README.md
└── models/
```

---

## Features

- Fake news classification
- Natural Language Processing (NLP)
- Text preprocessing pipeline
- TF-IDF feature extraction
- Multiple ML model comparison
- Performance evaluation using Accuracy, Precision, Recall, and F1-Score
- Predicts whether custom news articles are Real or Fake

---

## Sample Prediction

**Input**

```
Scientists discover a new planet capable of supporting human life.
```

**Output**

```
Prediction : Real News
Confidence : High
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Pramana31/Fake_News_Detection.git
```

Move into the project directory:

```bash
cd Fake_News_Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```
FAKE_NEWS_DETECTION.ipynb
```

---

## Future Improvements

- Deploy the model as a Flask or Django web application.
- Build a React-based frontend.
- Integrate real-time news verification APIs.
- Experiment with transformer-based models such as BERT and RoBERTa.
- Improve classification performance using deep learning techniques.

---

## Author

**Pramana Sarkar**

Master of Computer Applications (MCA)

GitHub: https://github.com/Pramana31

---

## License

This project is intended for academic and educational purposes.
