# 🛒 Amazon Product Reviews Sentiment Analysis

## 📌 Overview
This project builds a **sentiment analysis pipeline** for product or service reviews.

### 🚀 It performs:
- 🧹 **Data preprocessing** (cleaning, tokenization, lemmatization, stopword removal)
- 🧮 **Feature extraction** with `TF-IDF` and `CountVectorizer`
- 🤖 **Model training** with `Logistic Regression` and `Multinomial Naive Bayes`
- 📏 **Evaluation** using `accuracy`, `classification report`, and `confusion matrix`
- 📊 **Visualization** of the most frequent positive and negative words

---

## 📂 Dataset
The notebook expects a CSV file named **`Reviews.csv`** with at least:
- `Text` — review text
- `Sentiment` — target label (positive/negative)
- Data Link: https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews

💡 *You can replace `Reviews.csv` with your own dataset as long as the column names match.*

---

## 🛠 Steps Performed in the Notebook
1️⃣ **Load and inspect** the dataset  
2️⃣ **Preprocess the text** (cleaning, tokenizing, lemmatizing)  
3️⃣ **Vectorize text** with `TF-IDF` and `CountVectorizer`  
4️⃣ **Train models**: Logistic Regression & Multinomial Naive Bayes  
5️⃣ **Evaluate** using accuracy, confusion matrix, and classification report  
6️⃣ **Visualize** common words for each sentiment  

---

## 📦 Dependencies
- Python **3.8+**
- `pandas`, `numpy`
- `scikit-learn`
- `nltk`
- `spacy`
- `matplotlib`, `seaborn`
- `tqdm`, `joblib`

---

## 🔄 Clone Repository
```bash
git clone https://github.com/Mohamed-Kenawy/Amazon_Product_Reviews_Sentiment_Analysis.git
cd Amazon_Product_Reviews_Sentiment_Analysis
