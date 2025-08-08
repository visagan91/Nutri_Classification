# Nutri_Classification
Data Acquisition:

Data Ingestion: This is the starting point. Your system gathers all the necessary raw data, which could be image files, metadata from CSVs, or information from a database.

Data Preprocessing & Feature Engineering:

This is the cleaning and preparation stage. The raw data is passed through a sequence of steps to make it suitable for machine learning: handling missing values, capping extreme outliers, removing duplicate entries, and finally, encoding text categories and scaling numerical features to be on the same level.

Model Training & Evaluation:

Split Data: The clean data is divided into a training set (to teach the models) and a testing set (to evaluate them fairly).

Model Training Loop: Your system systematically trains multiple different algorithms (SVM, Random Forest, etc.) on the same training data. This ensures a fair competition.

Model Evaluation: Each trained model is then used to make predictions on the unseen test data. These predictions are compared against the actual answers to see how well the model performed.

Results & Analysis:

This final stage is all about making sense of the model performance. The system generates detailed reports (Classification Reports, Confusion Matrices) and summary visualizations (Bar Charts, Heatmaps).

The output is a Final Analysis Report that allows you to compare all the models and confidently select the best one for your task.