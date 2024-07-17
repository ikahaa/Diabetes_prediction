Data Collection and Exploration:

Loaded the dataset and performed initial data exploration to understand its structure and basic statistics.
Checked the distribution of the target variable (Outcome) and observed the class imbalance.

Data Preprocessing:

Standardized the features to ensure they have a mean of 0 and a standard deviation of 1, which is crucial for the performance of SVM.
Split the dataset into training and testing sets using an 80-20 split, ensuring stratification to maintain the same class distribution in both sets.

Model Training:

Chose a Support Vector Machine with a linear kernel for the classification task.
Trained the SVM classifier on the training dataset.

Model Evaluation:

Evaluated the model on both the training and testing datasets.
Achieved an accuracy score of approximately 78.3% on the training data and 79.9% on the test data.

Prediction:

Implemented a function to make predictions on new data points, including necessary data preprocessing steps like standardization.
Demonstrated the prediction capability of the model with a sample input.

Technical Skills Demonstrated:

Data Preprocessing: Standardization, Data Splitting
Machine Learning Algorithms: Support Vector Machine (SVM)
Model Evaluation: Accuracy Score
Tools and Libraries: Python, Pandas, NumPy, Scikit-learn
Project Outcome:
Successfully built and evaluated a SVM classifier to predict diabetes with a high degree of accuracy, demonstrating the ability to handle medical datasets and implement 
machine learning models for binary classification tasks.
