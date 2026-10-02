# Fake News Detection System

A machine learning and NLP system that classifies news text as **Fake** or **Real** and shows a confidence score.

## Features
- Text preprocessing (lowercasing, noise removal, tokenization, stopword removal)
- TF-IDF feature extraction
- Logistic Regression classifier with probability output
- Streamlit web app with Fake/Real result and confidence percentage
- Clickbait detection, readability analysis and explainable AI (important keywords)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, NLTK, Joblib, Textstat, Streamlit, VS Code

## How It Works
Input text → Preprocessing → TF-IDF → Logistic Regression → Fake/Real + probability

## Dataset
Fake.csv and True.csv (labelled news articles), merged and shuffled into news.csv.
Add the dataset source name and link here.

## Results
- Accuracy: add your final test accuracy
- Add precision, recall and F1-score from your classification report

## Installation
```
git clone <your-repo-link>
cd fake-news-detection-system
pip install -r requirements.txt
```

## Usage
1. Train the model: `python src/train_fake_news.py`
2. Run the app: `streamlit run app.py`

## Screenshots
Add 2 or 3 images: the app home page, a fake news prediction and a real news prediction.

## Limitations & Future Work
- English text only, and no live fact-checking
- Planned: deep learning/transformer models, multilingual support

## Team
Mini project, B.Tech CSE, Sree Buddha College of Engineering, Pattoor (APJ Abdul Kalam Technological University), 2026.
