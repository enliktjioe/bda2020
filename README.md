## BDA2020
- Repository made for Business Data Analytics Course in Spring 2019/2020 (University of Tartu)
- I made it open-source, use it responsibly

## Homework (HW) keywords
- HW1: Introduction (Python and Pandas, Data Understanding, Data Preparation, Gathering Interesting Facts)
- HW2: Customer Segmentation and Regression Problem (RFM, Kmeans, DBSCAN, Imputation, Correlation, MAE, RMSE, R-square)
- HW3: Classification Problems (Employee Attrition, Pandas Get Dummies, DecisionTree, SVM, SVC, Logistic Regression, RandomForestClassifier, XGBClassifier)
- HW4: Cross-sell / Up-sell using Recommendations (Market Basket Analysis, Collaborative Filtering, apriori, association_rules, one-hot encoding, LabelEncoder, fuzz, SVD, KNNBasic, NormalPredictor, Neural Network, Embedding, Reshape, Dense)  
- HW5: A/B Testing & Uplift Modelling (Hypothesis, QQ-plot, shapiro test, KNN, Logistic Regression, XGB Model)
- HW6: Knowledge graphs & Fairness and Explainability (triples, networkx, tensorflow, ampligraph, ComplEx, XGBoost, eli5 feature importances, shap)

## Practice Session (Lab) keywords
- Lab01: Python Basic, Data Science Tutorial (Numpy, Pandas, Matplotlib), Work with Missing Values, Pandas Profiling Report)
- Lab02: Data Science and Descriptive Data Analysis (Data cleaning, loc, iloc, Data Viz)
- Lab03: Customer Segmentation (Clustering) (RFM, Kmeans, Gaussian Mixture Models(GMM))
- Lab04: Customer Lifecycle Management - Regression (LinearRegression, MSE, R2, MAE)
- Lab05: Customer Lifecycle Management: Churn Prediction - Classification (MinMaxScaler, Logistic Regression, XGB)
- Lab06: Model Evaluation - Classification (Unbalanced dataset, random oversampling, ROC/AUC, Precision, Recall, K-Fold Cross Validation)
- Lab07: Recommendation System (Item-based collaborative filtering, Content-Based Filtering, CountVectorizer)
- Lab08: Cross-sell/Up-sell: Recommendations system using Neural networks + Embeddings (ANN, Deep Learning, Keras, 
- Lab09: A/B Testing
- Lab10: Uplift Modeling
- Lab11: Fraud Detection (Hyperparameter tuning, GridSearchCV)
- Lab12: Knowledge Graph (ampligraph, knowledge embeddings, PCA, 
- Lab13: Fairness and Explainability (feature importances, eli5, Skater, SHAP, 


## Troubleshooting
### URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:847)>
- Found on macOS 10.12.6 using Jupyter Notebook, insert this code cell

`import ssl
ssl._create_default_https_context = ssl._create_unverified_context`
