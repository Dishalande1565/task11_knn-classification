# KNN Classification — Task 11

## AI & ML Internship

### About
Implementation of K-Nearest Neighbors (KNN) Classification
using Iris Dataset with Elbow Method for optimal K selection
and ROC Curve evaluation.

---

### Dataset
- Name     : Iris Dataset
- Rows     : 150
- Features : 4 (sepal length, sepal width,
               petal length, petal width)
- Classes  : Setosa / Versicolor / Virginica

---

### Steps Completed
1. Loaded Iris Dataset
2. Feature Scaling using StandardScaler
3. Train-Test Split (80/20)
4. Elbow Method to find Optimal K
5. Trained KNN Model with Optimal K
6. Evaluated Accuracy and F1 Score
7. Plotted Confusion Matrix
8. Plotted ROC Curve with AUC Score
9. Compared accuracy at different K values

---

### Results
- Optimal K  : 3 or 5
- Accuracy   : 96-100%
- F1 Score   : 0.96-1.00
- AUC Score  : 0.97-1.00

---

### Tools Used
- Python 3
- Jupyter Lab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

### How to Run
1. Clone this repository
2. Open Jupyter Lab
3. Open knn_classification_task11.ipynb
4. Run all cells → Shift + Enter

---

### Interview Questions Covered
- Why KNN is called Lazy Learner?
- How to choose Optimal K?
- Impact of Scaling on KNN?
- Common Distance Metrics?

---

### File Structure
knn-classification/
├── README.md
├── .gitignore
└── knn_classification_task11.ipynb
