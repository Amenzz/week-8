# Fraud Detection Project

This project focuses on building a robust fraud detection pipeline using transaction and IP address data. It includes feature engineering techniques such as frequency counts, transaction velocity, and time-based features to capture user behavior patterns. Additionally, IP addresses are converted and matched to geographic ranges to enrich the dataset with location information. To address the common problem of class imbalance in fraud datasets, SMOTE is applied on the training set to synthetically balance minority class samples.

The pipeline further preprocesses the data by scaling numerical features and encoding categorical variables, preparing it for machine learning model training and evaluation. The project leverages popular Python libraries like pandas, scikit-learn, and imbalanced-learn, and follows best practices to ensure reliable and interpretable fraud detection results.
