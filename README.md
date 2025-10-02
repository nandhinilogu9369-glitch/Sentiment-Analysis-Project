# Sentiment-Analysis
# 🎬 Sentiment Analysis on IMDB Movie Reviews  

## 📌 Project Overview  
This project performs **sentiment analysis** on the IMDB movie reviews dataset.  
We apply **text preprocessing with Regex**, vectorize using **TF-IDF**, and train a **Logistic Regression model** to classify reviews as **positive** or **negative**.  

We also compare performance between raw text and cleaned text to evaluate the **impact of preprocessing** on model accuracy.  

---

## 📂 Dataset  
- **Source:** IMDB Movie Reviews Dataset  
- **Size:** 50,000 reviews (25,000 positive, 25,000 negative)  
- **Balanced:** Yes, equal distribution of classes  

---

## ⚙️ Workflow  

1. **Data Exploration**  
   - Load and inspect IMDB dataset  
   - Visualize class balance  

2. **Text Preprocessing**  
   - Remove HTML tags, punctuation, and numbers using Regex  
   - Apply **TF-IDF Vectorization** (max features = 5000, stopwords = English)  

3. **Model Training**  
   - Split data into **train/test sets**  
   - Train a **Logistic Regression** classifier  

4. **Evaluation**  
   - Accuracy, confusion matrix, classification report  
   - Compare results on **raw vs cleaned text**  
   - Generate **word clouds** for insights  

5. **Model Saving**  
   - Save trained model using `joblib`  

---

## 📊 Visualizations  
- Word frequency and word clouds for positive/negative reviews  
- Confusion matrix heatmap  
- Accuracy comparison between raw and cleaned datasets  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Matplotlib, Seaborn, WordCloud** – Visualization  
- **scikit-learn** – ML modeling (TF-IDF, Logistic Regression)  
- **Regex, String** – Text cleaning  

---

## 🚀 How to Run  

1. Clone this repo and open the notebook:  
   ```bash
   git clone <your-repo-url>
   cd sentiment-analysis-imdb
   jupyter notebook "Sentiment Analysis Project.ipynb"
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run all cells in order to:

Load dataset

Preprocess text

Train model

Evaluate results

📌 Results
Preprocessing improves accuracy compared to raw text.

Logistic Regression with TF-IDF is effective for IMDB sentiment classification.

The trained model can be reused for new movie reviews.

