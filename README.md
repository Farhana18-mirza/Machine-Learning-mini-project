# Machine-Learning-mini-project
### **Mini Project Description: Diabetes Prediction Using Linear Regression, Logistic Regression, and K-Nearest Neighbors (KNN)**

This mini project focuses on predicting diabetes using machine learning algorithms by analyzing a diabetes dataset. The dataset is loaded using the Pandas library, and the input features and target variable (`Outcome`) are separated. The data is then divided into training and testing sets using the `train_test_split()` function.

Three machine learning algorithms are implemented and compared:

* **Linear Regression** is used as a baseline model to understand the relationship between the input features and the target variable.
* **Logistic Regression** is applied for binary classification to predict whether a patient has diabetes (1) or not (0). The model's performance is evaluated using **accuracy, confusion matrix, and classification report**.
* **K-Nearest Neighbors (KNN)** is implemented using both **Euclidean distance (p=2)** and **Manhattan distance (p=1)** to classify patients based on the similarity of their medical attributes. The accuracy of each KNN model is calculated and compared.

The project demonstrates the complete machine learning workflow, including **data preprocessing, model training, prediction, and performance evaluation**. By comparing different algorithms, the project helps identify the most suitable model for diabetes prediction while providing practical experience with supervised machine learning techniques in Python using **NumPy, Pandas, Matplotlib, and Scikit-learn**.
