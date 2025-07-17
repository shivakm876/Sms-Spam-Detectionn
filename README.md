# 📧 Spam Message Detection – Machine Learning Project

This project builds a supervised machine learning pipeline to detect spam messages using classic NLP techniques and classification algorithms. It classifies SMS text messages as either "spam" or "ham" (not spam) based on learned patterns from labeled data.

---

## 🔍 Problem Statement

With the rise in SMS-based phishing and unwanted communication, building a reliable spam detection system is essential. This project leverages machine learning to analyze message content and classify them accurately without relying on hand-crafted rules.

---

## 🧠 Tech Stack

- **Language:** Python  
- **NLP & Data Processing:** `nltk`, `pandas`, `numpy`  
- **Vectorization:** TF-IDF from `scikit-learn`  
- **Machine Learning Models:**  
  - Logistic Regression  
  - k-Nearest Neighbors (k-NN)  
  - Random Forest  
- **Visualization & Evaluation:** `matplotlib`, `seaborn`

---

## 📂 Project Structure

spam-detection/
├── ML_Project_final.ipynb # Full pipeline in Jupyter/Colab
├── spam.csv # Dataset (optional)
├── README.md # Project overview and documentation
├── .gitignore # Clean version control exclusions


## 🛠️ Key Highlights

- Cleaned and preprocessed SMS text using `nltk`  
- Extracted features using **TF-IDF** vectorization  
- Trained and compared multiple classifiers (LogReg, k-NN, Random Forest)  
- Evaluated models with **F1-score**, confusion matrix, and classification reports  
- Achieved **96% F1-score** with Logistic Regression on the test set

---

## 📊 Results

- ✅ **96% F1-score** on real-world SMS spam dataset  
- 🔍 Visualized model performance using confusion matrix & reports  
- 📈 Reliable prediction with low false positives
- 🚀 Among all models tested, Naive Bayes achieved the highest performance, reaching a 96% F1-score on the test set, outperforming Logistic Regression, k-NN, and Random Forest.

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/spam-detection.git
   cd spam-detection
