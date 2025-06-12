# SMS/Email Spam Classifier 🚫📩

This is a simple Streamlit web app that classifies a given message as **Spam** or **Not Spam** using an ML model trained on text data.

## 🔧 How It Works
- The message is cleaned and stemmed using NLTK.
- TF-IDF vectorization is applied.
- A trained model (likely Naive Bayes or Logistic Regression) makes the prediction.

## 📦 Setup
1. Clone the repo:
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier

2. Install dependencies:
pip install -r requirements.txt

3. Run the app:
streamlit run app.py


## 📁 Files
- `app.py`: Streamlit frontend + prediction code.
- `model.pkl`: Trained ML model.
- `vectorizer.pkl`: TF-IDF vectorizer.
