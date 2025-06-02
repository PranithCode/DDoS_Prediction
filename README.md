#DDoS Detection using Machine Learning
This project focuses on the detection of Distributed Denial of Service (DDoS) attacks using supervised machine learning techniques. The dataset used is a labeled network traffic dataset containing both benign and DDoS attack flows. Various preprocessing, visualization, and classification steps are carried out to build an accurate detection model.

📁 Dataset
File: DDos.csv

Features include packet statistics, header info, duration, flags, active/idle times, and flow metrics.

Labels: BENIGN (0), DDoS (1)

🧹 Data Preprocessing
Removed leading/trailing whitespace in column names

Handled and dropped all rows with missing values

Converted categorical labels to numeric format

Checked for balanced class distribution

📊 Exploratory Data Analysis
Visualized label distribution

Performed statistical summaries using .describe()

Generated feature-wise histograms for inspection of feature distributions

🧠 Machine Learning Model
Model Used: Random Forest Classifier (sklearn.ensemble.RandomForestClassifier)

Split Ratio: 75% training, 25% testing

Hyperparameter Tuning: GridSearchCV 

✅ Evaluation Metrics
Accuracy: 99.95%

Precision, recall, and F1-score all ~1.00

Excellent performance for both classes
