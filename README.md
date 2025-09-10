# KNN-Classifier-on-Iris-Dataset
This project demonstrates a simple implementation of the K-Nearest Neighbors (KNN) algorithm from scratch (without using sklearn.neighbors.KNeighborsClassifier). It classifies iris flowers into three species based on their sepal and petal measurements.

## **Project Workflow**

Data Loading & Preparation
Load Iris dataset from sklearn.datasets.
Split into train (70%) and test (30%) sets.
Standardize features using StandardScaler for fair distance comparison.

Algorithm Implementation
Define Euclidean distance function.
Build a custom KNN class with majority voting.
Model Training & Evaluation
Train with k=5.

Achieve model accuracy on test set.

**Visualization**
Scatter plot of sepal length vs. sepal width with species coloring.
User Input Prediction
Accept custom input values.
Predict the corresponding Iris species.

 ### **Visualization**

The script generates a 2D scatter plot (Sepal Length vs. Sepal Width):![THE DATA](images/output.png)


**Example User Input:**
Enter flower measurements:
Sepal length (cm): 5.8
Sepal width (cm): 2.7
Petal length (cm): 5.1
Petal width (cm): 1.9
**Output:**
KNN Classifier Accuracy (k=5): 0.98
The predicted Iris species is: virginica

**Key Concepts**

KNN Algorithm → Predicts based on majority of nearest neighbors.
Euclidean Distance → Used to measure closeness between data points.
StandardScaler → Normalizes feature scales.
Accuracy Evaluation → Measures model performance.

**Dataset Info**

Source: Iris dataset (Fisher, 1936)

Features:

Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (c)

Target Classes:
Setosa
Versicolor
Virginica

**Contributing**
Improved visualizations 
Hyperparameter tuning 
Adding more classification metrics

#### **Admin / Author**

Project Created & Maintained By:
 **Puneet Tiwari**
