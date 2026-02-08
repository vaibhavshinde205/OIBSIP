# Task 4 – Email Spam Detection

This project is part of the **Data Science Internship at OASIS INFOBYTE**.  
The goal of this task is to build a Machine Learning model that classifies emails as Spam or Not Spam using Natural Language Processing techniques.

---

# Objective
To develop a text classification model that can detect spam emails based on the content of the message.

---

# Dataset Information

The dataset contains email messages labeled as:

- Ham (Not Spam)  
- Spam  

### Features Used
- Email Message Text  

Target variable: **Spam or Not Spam**

---

# Machine Learning Workflow

1. Load the dataset  
2. Clean and preprocess text data  
3. Convert text into numerical form using TF-IDF  
4. Split dataset into training and testing sets  
5. Train Naive Bayes classifier  
6. Evaluate model performance  
7. Visualize confusion matrix  
8. Analyze important spam words  

---

# Model Used
**Multinomial Naive Bayes**

Reason for using:
- Works efficiently with text data  
- Suitable for word frequency–based features  
- Fast and effective for spam detection  

---

# Results

- **Accuracy:** ~96%  
- Model successfully detects spam messages  

---

# Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Natural Language Processing (NLP)  

---

# How to Run

```bash
python spam_detection.py
```

---

# File Structure

```bash
Task4_Spam_Detection/
├── spam.csv
├── spam_detection.py
└── README.md
```

---

