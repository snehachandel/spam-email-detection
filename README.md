# 📧 Spam Email Detection System

A machine learning project that classifies SMS messages as **Spam** or **Ham** using Natural Language Processing (NLP) and a Naive Bayes classifier.

> ✅ Achieved **~98% accuracy** on test data

---

## 🚀 Features
- Text preprocessing and data cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Text vectorization using CountVectorizer
- Naive Bayes classifier for spam detection
- 98% accuracy on the UCI SMS Spam Collection dataset

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| Scikit-learn | ML model + vectorization |
| Matplotlib | Data visualization |
| Jupyter Notebook | Development environment |

---

## 📂 Project Structure
```
spam-email-detection/
│
├── data/
│   └── spam.csv              # SMS Spam Collection dataset
├── notebooks/
│   └── spam_detection.ipynb  # Main notebook
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run

1. **Clone the repository**
```bash
git clone https://github.com/snehachandel/spam-email-detection.git
cd spam-email-detection
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Open the notebook**
```bash
jupyter notebook notebooks/spam_detection.ipynb
```

---

## 🤖 How It Works
1. Load the SMS Spam Collection dataset (5,572 messages)
2. Clean and preprocess text (lowercase, remove punctuation)
3. Convert text to numerical features using CountVectorizer
4. Train a Multinomial Naive Bayes model on 80% of the data
5. Evaluate on the remaining 20% — achieving **98% accuracy**

---

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | ~98% |
| Model | Multinomial Naive Bayes |
| Dataset | UCI SMS Spam Collection |

---

## 📌 Example
```
Input:  "Congratulations! You've won a free iPhone. Click here to claim now."
Output: 🚨 SPAM

Input:  "Hey, are we still meeting for lunch tomorrow?"
Output: ✅ HAM
```

---

## 📦 Dataset
This project uses the [UCI SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) — a public dataset of 5,572 tagged SMS messages.

---

## 👩‍💻 Author
**Sneha Chandel** — [LinkedIn](https://linkedin.com/in/sneha-chandel-766825339) | [GitHub](https://github.com/snehachandel)
```

