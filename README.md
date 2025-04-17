 Sentiment-Analysis-of-Tweet

Sure! Here's a clean, professional, and beginner-friendly `README.md` content for your Sentiment Analysis of Tweets project using the 

Sentiment140 dataset:
 💬 Sentiment Analysis of Tweets
This project performs Sentiment Analysis on tweets using the Sentiment140 dataset, which contains 1.6 million labeled tweets. The goal is to classify tweets as either positive or negative based on their content.

 📁 Dataset-
- Name: Sentiment140
- Source: [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Size: 1.6 million tweets
- Labels:  
  - `0` → Negative sentiment  
  - `4` → Positive sentiment (converted to `1` in preprocessing)

 🧠 What this project does-
- Loads and cleans tweet data  
- Preprocesses text (removing special characters, stopwords, stemming, etc.)
- Converts text into numerical features using TF-IDF Vectorizer
- Trains a Logistic Regression model
- Evaluates the model using accuracy score
- Predicts sentiment on new tweets

🔧 Libraries Used-
pandas
numpy
re
nltk
scikit-learn

Install them using:
pip install pandas numpy nltk scikit-learn

⚙️ Project Workflow-
1. Data Loading  
   Load the dataset and understand its structure.
2. Data Cleaning  
   - Remove unwanted characters  
   - Remove stopwords  
   - Apply stemming
3. Vectorization  
   Use TF-IDF to convert text to numerical format.
4. Model Training  
   Train a Logistic Regression classifier.
5. Evaluation  
   Measure performance using accuracy and classification report.
6. Prediction  
   Try out custom tweet inputs for sentiment prediction.

🧪 Sample Output-

Original Tweet: I love this phone!  
Predicted Sentiment: Positive 💖

Original Tweet: Worst service ever.  
Predicted Sentiment: Negative 😡

📌 Future Improvements-
- Use deep learning (LSTM, BERT) for better accuracy  
- Add emoji and hashtag handling  
- Build a web app interface using Flask or Streamlit

---

