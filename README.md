Customer Insurance Purchases Prediction

Project Overview

This machine learning project aims to predict whether a customer will purchase health insurance based on their **Age** and **Estimated Salary**. The project involves implementing and comparing multiple classification algorithms to determine the most effective model.

Objective

To analyze customer data and build a classification model that predicts insurance purchase decisions using the following algorithms:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  

The best-performing algorithm is selected based on accuracy, generalization, and overfitting risk.

---

Dataset

- Name: `Social_Network_Ads.csv`
- Features Used: Age, Estimated Salary  
- Target: Purchased (0 = No, 1 = Yes)

---

 Folder Structure

insurance-prediction-project/
├── Logistic_Regression/
│ └── logistic_regression.ipynb
├── KNN/
│ └── knn_model.ipynb
├── SVM/
│ └── svm_model.ipynb
├── Decision_Tree/
│ └── decision_tree.ipynb
├── Random_Forest/
│ └── random_forest.ipynb
├── Social_Network_Ads.csv
├── report.pdf
├── README.md
How to Run the Project

1. Clone or download this repository.
2. Install required libraries (if not already installed):
   ```bash
   pip install pandas numpy matplotlib scikit-learn
3.Open .ipynb files using Jupyter Notebook or Google Colab.

4.Run each model file separately to view training results, predictions, and visualizations.

Model	                        Accuracy 		Inferences
Logistic Regression	          89%		Performs well on linearly separable data
K-Nearest Neighbors	          93%		Sensitive to feature scaling and K
Support Vector Machine (SVM)	  90%		High margin separation; slower on large datasets
Decision Tree	                  91%		Tends to overfit without pruning
Random Forest                  	  91%		Best performer, reduced variance

Author
Vani Sree M
B.Tech CSE (AI & ML), ANITS Engineering College
India
 LinkedIn : https://www.linkedin.com/in/vani-sree-meesala-28244a323/
 GitHub : https://github.com/mVanisree



