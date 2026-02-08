#  Task 1 – Iris Flower Classification

This project is part of the **Data Science Internship at OASIS INFOBYTE**.  
The goal of this task is to build a Machine Learning model that can classify iris flowers into their correct species based on flower measurements.

---

#  Objective
To train a classification model that predicts the species of an iris flower using features such as sepal length, sepal width, petal length, and petal width.

---

#  Dataset Information

The dataset contains measurements of iris flowers belonging to three species:

- Setosa  
- Versicolor  
- Virginica  

### Features Used
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

Target variable: **Species**

---

#  Machine Learning Workflow

1. Load the dataset  
2. Remove unnecessary columns  
3. Encode categorical labels  
4. Split dataset into training and testing sets  
5. Train Random Forest Classifier  
6. Evaluate model performance  
7. Visualize confusion matrix  
8. Analyze feature importance  

---

#  Model Used
**Random Forest Classifier**

Reason for using:
- Handles multi-class classification well  
- Robust to noise  
- Provides feature importance  

---

#  Results

- **Accuracy:** 100%  
- Model successfully classifies iris flower species  

---

#  Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

#  How to Run

```bash
python iris_classification.py
```

---

#  File Structure

```bash
Task1_Iris_Classification/
├── Iris.csv
├── iris_classification.py
└── README.md
```

---


