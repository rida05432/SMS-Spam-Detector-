# SMS Spam Detector 

This project is a **machine learning-based SMS Spam Detector** built with Python in Jupyter Notebook.  
It classifies SMS messages as **spam** or **ham (not spam)** by analyzing the text content using Natural Language Processing (NLP) and supervised learning models.  

The goal is to demonstrate how text preprocessing, feature extraction, and machine learning can solve real-world classification problems.

---

## 🚀 Features
- Cleans and preprocesses SMS text data.  
- Transforms text into numerical features using **TF-IDF / Bag of Words**.  
- Trains multiple ML models and compares their performance.  
- Classifies new SMS messages as **Spam** or **Ham**.  
- Achieves high accuracy with low false positives.  

---

## 🛠 Tech Stack
- **Python**  
- **Jupyter Notebook**  
- **Pandas** – data handling  
- **NumPy** – numerical processing  
- **Scikit-learn** – machine learning & evaluation  
- **NLTK / Regex** – text cleaning and preprocessing  

---

## 📊 Models Used
- Naïve Bayes (MultinomialNB)  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

Performance is evaluated using **accuracy, precision, recall, and F1-score**.

---

## 📈 Results
- Accuracy: ~95%+ (depending on train/test split).  
- Balanced precision and recall to minimize false positives.  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/rida05432/sms-spam-detector.git
   cd sms-spam-detector
