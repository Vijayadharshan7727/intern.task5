# intern.task5
# 🧠 AI & ML Internship - Task 5: Decision Trees and Random Forests

This project is part of the AI & ML Internship task series and focuses on implementing and understanding **tree-based machine learning models** using the **Heart Disease Dataset**.

---

## 📌 Task Objective

To implement and compare **Decision Tree** and **Random Forest** classifiers on a real-world dataset. You'll also:
- Visualize the Decision Tree
- Analyze overfitting and control tree depth
- Interpret feature importance
- Evaluate the models using cross-validation

---

## 🛠 Tools & Libraries Used

- Python 3
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Graphviz / plot_tree](https://scikit-learn.org/stable/modules/generated/sklearn.tree.plot_tree.html)

---

## 📂 Dataset

**Heart Disease Dataset**  
- Source: [Kaggle - John Smith](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
- Target Column: `target` (0 = No Disease, 1 = Disease)

---

## 🚀 What’s Implemented

### ✅ Step-by-step Workflow:

1. **Data Loading & Preprocessing**
   - Loaded dataset and split into features & target.
   - Applied train-test split and standard scaling.

2. **Decision Tree Classifier**
   - Trained a decision tree.
   - Visualized the full tree using `plot_tree`.
   - Evaluated model with accuracy and classification report.

3. **Controlling Overfitting**
   - Trained a **pruned tree** with `max_depth=3` to avoid overfitting.
   - Compared training vs testing accuracy.

4. **Random Forest Classifier**
   - Trained a Random Forest with 100 estimators.
   - Compared its performance with Decision Tree.

5. **Feature Importance**
   - Plotted feature importances based on the Random Forest.

6. **Model Evaluation**
   - Used 5-fold Cross-Validation to assess performance.
   - Displayed a confusion matrix for better understanding.

---

## 📈 Results

| Model              | Accuracy (Test Set) |
|-------------------|---------------------|
| Decision Tree      | ~78%                |
| Pruned Tree        | ~82%                |
| Random Forest      | ~86%                |
| Cross-Val Score    | ~85% (avg)          |

---

## 📸 Sample Outputs

- ✅ Decision Tree Visualization
- ✅ Feature Importance Graph
- ✅ Confusion Matrix Heatmap



---

## 📁 Repository Structure

