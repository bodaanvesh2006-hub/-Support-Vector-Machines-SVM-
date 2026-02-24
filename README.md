Support Vector Machines (SVM) Classification

# Objective

The objective of this task is to understand and implement Support Vector Machines (SVM) for both linear and non-linear classification problems.# Tools & Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

 Dataset
* Dataset Used: Breast Cancer Dataset
* Source: Scikit-learn built-in dataset
* Description: This dataset contains features computed from breast cancer cell images, used to classify tumors as malignant or benign.

 Steps Performed
 1. Data Loading

* Loaded dataset using sklearn
* Extracted features (X) and target labels (y)
 2. Data Preprocessing

* Split dataset into training and testing sets
* Applied feature scaling using StandardScaler
3. Model Implementation

* Trained SVM with linear kernel
* Trained SVM with RBF (non-linear) kernel
 4. Model Evaluation

* Calculated accuracy for both models
* Compared performance of linear and RBF kernels
5. Hyperparameter Tuning

* Tuned parameters such as C and gamma
* Observed improvement in model performance
6. Visualization

* Visualized decision boundary using 2D features
* Analyzed how SVM separates different classes
7. Cross-Validation

* Performed 5-fold cross-validation
* Calculated mean accuracy for reliable evaluation
 📊 Results

* Linear SVM Accuracy: XX%
* RBF SVM Accuracy: XX%
* Tuned SVM Accuracy: XX%
* Cross-Validation Score: XX%

📈 Observations

* Linear SVM works well for linearly separable data
* RBF kernel performs better for complex, non-linear data
* Hyperparameter tuning improves accuracy
* Feature scaling is essential for SVM performance

