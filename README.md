
# 📩 SMS Spam Classifier

This is a machine learning project that classifies SMS messages as **Spam** or **Not Spam (Ham)** using **NLP preprocessing** and a **Multinomial Naive Bayes** model.

---

## 📁 Project Files

| File                         | Description                       |
|------------------------------|-----------------------------------|
| `sms_spam_classifier.ipynb`  | Jupyter notebook (EDA to model)   |
| `spam.csv`                   | Original SMS dataset              |
| `spam_classifier_model.pkl`  | Trained Naive Bayes model         |
| `tfidf_vectorizer.pkl`       | TF-IDF vectorizer                 |
| `README.md`                  | Project overview                  |

---

## 🔍 Features

- Text cleaning: lowercasing, stopword removal, punctuation, stemming
- TF-IDF vectorization
- Naive Bayes model for classification
- Evaluation: accuracy, precision, recall, F1-score

---

## 📊 Dataset Info

- Source: [Kaggle SMS Spam Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- 5,572 messages
  - `ham` → 4,825
  - `spam` → 747

---

## 🔧 Model Performance

- **Accuracy**: 96.77%
- **Precision (Spam)**: 0.99
- **Recall (Spam)**: 0.77
- **F1-score (Spam)**: 0.86

---

## 💡 How to Use

1. Clone the repo:
```bash
git clone https://github.com/MallikarjunSonna/sms-spam-classifier.git
cd sms-spam-classifier
```

2. Open the notebook:
```bash
jupyter notebook sms_spam_classifier.ipynb
```

---

## ✍️ Author

**Mallikarjun Sonna**  
_Data Science Intern | Machine Learning & Gen AI Enthusiast_  
📧 mallusonna43@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mallikarjuncs)  
🔗 [GitHub](https://github.com/MallikarjunSonna)
