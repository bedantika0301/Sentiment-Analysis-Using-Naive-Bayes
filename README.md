Sentiment Analysis Using Naive Bayes

A simple and beginner-friendly Machine Learning project that performs sentiment analysis on user input text. The model classifies sentences into positive, negative, or neutral sentiments using the Multinomial Naive Bayes algorithm.



Features:
Classifies text into Positive, Negative, Neutral
Real-time user input prediction
Displays confidence score
Basic text preprocessing (lowercase, punctuation removal)
Easy to understand and implement



Tech Stack:
Python
Scikit-learn
Natural Language Processing (NLP)



How It Works:
A small dataset of labeled sentences is used for training
Text is preprocessed (lowercase + punctuation removal)
CountVectorizer converts text into numerical features (Bag of Words)
Naive Bayes model is trained on the dataset
User input is analyzed and sentiment is predicted with confidence score



Project Structure:
sentiment-analysis/
│── main.py
│── README.md
│── requirements.txt



Installation & Setup:
1. Clone the repository
git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis
2. Install dependencies
pip install -r requirements.txt
3. Run the project
python main.py



Example Usage:
Enter a sentence: I love this product
Sentiment: positive
Confidence: 0.85



Limitations:
Uses a small dataset (low accuracy)
Cannot detect sarcasm or complex language
Basic NLP implementation



Future Improvements:
Use larger datasets (IMDb, Twitter)
Implement TF-IDF vectorization
Add deep learning models (LSTM, BERT)
Build a web app using Streamlit


Author:
Bedantika Banerjee
25BCE10597
