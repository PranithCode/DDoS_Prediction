# DDoS Detection using Machine Learning

This project focuses on the detection of Distributed Denial of Service (DDoS) attacks using supervised machine learning techniques. The dataset used is a labeled network traffic dataset containing both benign and DDoS attack flows. Various preprocessing, visualization, and classification steps are carried out to build an accurate detection model.

Features include packet statistics, header info, duration, flags, active/idle times, and flow metrics.

Labels: BENIGN (0), DDoS (1)

## Data Preprocessing
1. Removed leading/trailing whitespace in column names

2. Handled and dropped all rows with missing values

3. Converted categorical labels to numeric format

4. Checked for balanced class distribution

## Exploratory Data Analysis
1. Visualized label distribution

2. Performed statistical summaries using .describe()

3. Generated feature-wise histograms for inspection of feature distributions

## Machine Learning Model
1. Model Used: Random Forest Classifier (sklearn.ensemble.RandomForestClassifier)

2. Split Ratio: 75% training, 25% testing

3. Hyperparameter Tuning: GridSearchCV 

## Evaluation Metrics
1. Accuracy: 99.95%

2. Precision, recall, and F1-score all ~1.00

3. Excellent performance for both classes
