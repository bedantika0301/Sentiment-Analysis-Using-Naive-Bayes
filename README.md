Sentiment Analysis using Naive Bayes

Project Overview

This project is a basic Sentiment Analysis model built using Machine Learning. It classifies text into:

Positive
Neutral
Negative

The model is trained using the Naive Bayes algorithm and uses Bag of Words for feature extraction.


Objective

To develop a simple ML-based system that can analyze user input text and determine its sentiment.

Technologies Used
Python
Scikit-learn
Natural Language Processing (NLP)

How It Works
Input text is taken from the user
Text is cleaned (lowercase, remove punctuation)
Converted into numerical form using CountVectorizer
Model predicts sentiment using Multinomial Naive Bayes


Project Structure
sentiment-analysis
│── main.py
│── README.md


Installation & Setup
1. Install dependencies
pip install scikit-learn
2. Run the program
python main.py


Example Usage
Enter a sentence: I love this product
Sentiment: positive
Confidence: 0.85


Dataset

The model uses a small custom dataset with labeled sentences:

Positive examples
Negative examples
Neutral examples


 Features
Simple and beginner-friendly
Real-time sentiment prediction
Confidence score output
Handles positive, negative, and neutral sentiments


Limitations
Small dataset → limited accuracy
Cannot detect sarcasm
Basic NLP (no deep learning)


Future Improvements
Use larger datasets (IMDb, Twitter)
Implement advanced models (LSTM, BERT)
Add GUI (Tkinter / Streamlit)
Deploy as a web app

References
Scikit-learn Documentation
NLP tutorials

Author
Bedantika Banerjee
25BCE10597

Bedantika Banerjee
25BCE10597
