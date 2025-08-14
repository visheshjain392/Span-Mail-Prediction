# 📧 Spam Mail Classification

This is a basic **Spam Mail Classification** project implemented in **Google Colab**.  
It uses **Machine Learning** to identify whether an email is **Spam** or **Not Spam** based on its text content.

---

## 📌 Project Overview
The goal of this project is to build a simple model that can automatically classify emails as **spam** or **ham** (not spam).  
This is a common Natural Language Processing (NLP) problem and serves as a beginner-friendly introduction to text classification.

---

## ⚙️ Features
- Loads and preprocesses email dataset
- Text cleaning & tokenization
- Converts text to numerical vectors using **TF-IDF**
- Trains a **Naive Bayes Classifier** (can be replaced with other algorithms)
- Evaluates model performance using accuracy, precision, recall, and F1-score
- Predicts whether a given email is spam or not

---

## 🛠️ Technologies Used
- **Python** (Google Colab environment)
- **Pandas** → Data handling
- **NumPy** → Numerical computations
- **Scikit-learn** → Machine learning models & metrics
- **NLTK** → Text preprocessing
- **Matplotlib/Seaborn** → Data visualization

---

## 📂 Dataset
You can use:
- [SpamAssassin Public Dataset](https://spamassassin.apache.org/old/publiccorpus/)
- [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)

Make sure to upload the dataset to Google Colab or mount Google Drive.

---

## 🚀 How to Run
1. **Open in Google Colab**  
   - Upload the `.ipynb` file to your Google Drive or open directly from GitHub.

2. **Install Required Libraries**  
   ```python
   !pip install nltk scikit-learn matplotlib seaborn
