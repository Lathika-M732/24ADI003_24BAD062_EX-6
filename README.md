# 24ADI003_24BAD062_EX-6
SCENARIO 1 – BAGGING

In this scenario, the Bagging (Bootstrap Aggregating) technique is used to improve the performance of a Decision Tree classifier for predicting whether a patient has diabetes. The Diabetes dataset is loaded and preprocessed, and the data is split into training and testing sets. A Decision Tree model is first trained, and then BaggingClassifier is applied to create multiple decision trees using different bootstrap samples. The performance of the base model and the bagging model is compared using accuracy and confusion matrix. Visualization such as accuracy comparison bar graph and confusion matrix are used to analyze the results.

SCENARIO 2 – BOOSTING (AdaBoost, Gradient Boosting)

In this scenario, Boosting techniques such as AdaBoost and Gradient Boosting are used to predict whether a customer will churn. The Telco Customer Churn dataset is loaded and preprocessed by handling categorical variables and missing values. The data is then divided into training and testing sets. AdaBoost and Gradient Boosting models are trained to improve prediction accuracy by focusing on previously misclassified samples. The performance of both models is evaluated using classification metrics, and visualizations such as ROC Curve and Feature Importance plots are used to compare the models.

SCENARIO 3 – RANDOM FOREST

In this scenario, the Random Forest algorithm, an ensemble learning technique that combines multiple decision trees, is used to predict whether a person earns more than 50K salary. The Adult Income dataset is loaded and preprocessed by encoding categorical variables and handling missing values. The dataset is then split into training and testing sets. A Random Forest model is trained with different numbers of trees to analyze performance. The model is evaluated using accuracy and other classification metrics. Visualizations such as Feature Importance and Accuracy vs Number of Trees graphs help understand the contribution of features and model performance.

SCENARIO 4 – STACKING

In this scenario, the Stacking ensemble method is used to predict the presence of heart disease. The Heart Disease dataset is loaded and preprocessed before splitting it into training and testing sets. Multiple base models such as Logistic Regression, Support Vector Machine (SVM), and Decision Tree are trained individually. These models are then combined using a StackingClassifier with a meta-model to improve prediction performance. The stacked model is compared with individual base models to analyze improvements in accuracy. Visualization such as a model comparison bar chart is used to show the performance of different models.

SCENARIO 5 – SMOTE

In this scenario, SMOTE (Synthetic Minority Oversampling Technique) is used to handle class imbalance in fraud detection. The Credit Card Fraud Detection dataset is loaded, and the class distribution is analyzed to identify imbalance between normal and fraudulent transactions. SMOTE is applied to generate synthetic samples for the minority class to balance the dataset. A machine learning model is trained before and after applying SMOTE, and the performance of both models is compared using classification metrics. Visualizations such as class distribution graphs and Precision-Recall Curve are used to analyze the improvement in fraud detection performance.
