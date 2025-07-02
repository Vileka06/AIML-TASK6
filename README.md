# AIML-TASK6
**📌 Task 6: K-Nearest Neighbors (KNN) Classification**

**🎯 Objective:**
To understand and implement the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset.

**📂 Dataset:**
Used the Iris dataset available on Kaggle and loaded it locally using Pandas.

**✅ Steps Performed:**

- Data Loading:
Imported the dataset (Iris.csv) from a local directory using Pandas.

-Data Preprocessing:
 -Separated the feature matrix (X) and target vector (y).
 -Encoded target labels into integers using factorize().
 -Standardized the feature values using StandardScaler.

 -Model Training:
  -Applied KNeighborsClassifier from Scikit-learn.
  -Evaluated the model for K values ranging from 1 to 10.
  -Selected the optimal K based on the highest test accuracy.
  Evaluation Metrics:

- Calculated Accuracy Score

 -Displayed the Confusion Matrix
 -Generated a Classification Report

-Visualization:

 -Plotted Accuracy vs. K to observe performance trends
 -Visualized the decision boundaries using the first two features

 **🛠️ Tools & Libraries Used:**
 -Python
 -Pandas
 -NumPy
 -Matplotlib
 -Seaborn
 -Scikit-learn

 **Output:**[K-Nearest Neighbors classification.output.pdf](https://github.com/user-attachments/files/21000105/K-Nearest.Neighbors.classification.output.pdf)

