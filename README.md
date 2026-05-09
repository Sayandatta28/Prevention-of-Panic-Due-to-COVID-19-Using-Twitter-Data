# 🦠 Prevention of Panic Due to COVID-19 Using Twitter Data

This project focuses on detecting panic-related tweets during the COVID-19 pandemic using **Sentiment Analysis** and **Machine Learning** techniques. The primary objective is to analyze public emotions and identify panic or anxiety-related content from Twitter datasets.

The system collects tweets related to hashtags such as **#afraid**, **#anxiety**, and **#depressed**, processes the textual data using NLP techniques, and classifies the sentiment of tweets into **Positive**, **Negative**, and **Neutral** categories.

---

## 🚀 Project Objectives

- Analyze COVID-19 related Twitter data
- Detect panic and anxiety-related tweets
- Perform sentiment analysis using NLP
- Compare the performance of different machine learning models
- Visualize tweet patterns using WordCloud

---

## 🛠️ Technologies Used

- Python
- Machine Learning
- Natural Language Processing (NLP)
- Pandas
- NumPy
- TextBlob
- Scikit-learn
- WordCloud
- Matplotlib

---

## 📂 Project Structure
```text
Prevention-of-Panic-Due-to-COVID-19-Using-Twitter-Data/
│
├── Covid-19 Twitter Sentiment Analysis.ipynb
├── Covid_19_Tweets_Dataset.xlsx
├── Pickle_RL_Model.pkl
├── README.md
```

---

## 📊 Dataset

The dataset contains tweets collected from Twitter using keywords and hashtags related to mental stress and panic during COVID-19, including:

- #afraid
- #anxiety
- #depressed

The dataset is used to analyze user sentiment and emotional behavior during the pandemic.

---

## ⚙️ Methodology

### 1️⃣ Data Collection
Tweets related to COVID-19 panic and anxiety are collected from available Twitter datasets.

### 2️⃣ Data Preprocessing
The following preprocessing steps are performed:

- Remove punctuation
- Remove stopwords
- Convert text to lowercase
- Clean unnecessary symbols and characters

### 3️⃣ Sentiment Analysis
Using **TextBlob**, the polarity score of each tweet is calculated:

- Positive Sentiment
- Negative Sentiment
- Neutral Sentiment

### 4️⃣ Text Visualization
WordCloud is used to visualize the most frequent words in tweets.

### 5️⃣ Feature Extraction
**Count Vectorizer** is used to transform text data into numerical vectors for machine learning models.

### 6️⃣ Machine Learning Models
The following classification models are implemented and compared:

- Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 📈 Features

- COVID-19 Tweet Analysis
- Sentiment Classification
- Panic Detection
- NLP-based Text Processing
- WordCloud Visualization
- Machine Learning Model Comparison

---

## 📊 Output

The project classifies tweets into:

- ✅ Positive
- ❌ Negative
- ⚪ Neutral

It also compares model performance based on classification accuracy.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Prevention-of-Panic-Due-to-COVID-19-Using-Twitter-Data.git
cd Prevention-of-Panic-Due-to-COVID-19-Using-Twitter-Data

2. Install Required Libraries
pip install pandas numpy scikit-learn textblob matplotlib wordcloud

3. Run the Notebook

Open the Jupyter Notebook or Google Colab file and run all cells.
