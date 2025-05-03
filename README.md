# 📦 Flipkart Reviews Sentiment Analysis

**Real Time Project (RTP)**  
**College**: CMR College of Engineering & Technology

This project analyzes customer reviews and ratings on Flipkart using Machine Learning. It classifies reviews as **positive (1)** or **negative (0)** based on the review text and star rating.

---

## ✨ Objective

To build a machine learning model that:
- Preprocesses Flipkart reviews,
- Converts text into numerical vectors using TF-IDF,
- Predicts sentiment using a Decision Tree Classifier,
- Visualizes results using charts and word clouds.

---

## 🛠️ Technologies Used

- **Python**  
- **Libraries**:
  - pandas, numpy
  - nltk
  - scikit-learn
  - matplotlib, seaborn
  - wordcloud

---

## 📂 Dataset

- File: `flipkart_data.csv`
- Key Columns:
  - `review`: Customer feedback
  - `rating`: Numerical rating (1 to 5)
  - `label`: Generated column — 1 (positive), 0 (negative)

---

## 📊 Process Overview

### 1. **Preprocessing**
- Lowercasing and punctuation removal
- Stopword removal using NLTK
- Sentiment labeling:
  - Rating ≥ 5 → Positive (1)
  - Rating < 5 → Negative (0)

### 2. **Text Vectorization**
- TF-IDF with top 2500 features

### 3. **Model Training**
- Algorithm: Decision Tree Classifier
- Data Split: 67% training, 33% testing

### 4. **Evaluation**
- Accuracy Score
- Confusion Matrix
- Word Cloud for positive reviews

---

## ✅ Accuracy

- Achieved approximately **92.47%** accuracy on training data.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/flipkart-sentiment-analysis.git
cd flipkart-sentiment-analysis
