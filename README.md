# Datheon_Machine_Learning_-_Data_Science_Internship

# 🚀 Datheon Machine Learning & Data Science Internship

## 📌 Internship Project Portfolio

Welcome to my **Machine Learning & Data Science Internship Project Repository** at Datheon.

This repository contains four practical machine learning and data science projects developed using Python and popular machine learning libraries.

The projects demonstrate practical knowledge of data preprocessing, exploratory data analysis, feature engineering, supervised machine learning, natural language processing, model evaluation, and data visualization.

The main objective of these projects is to apply machine learning techniques to real-world datasets and develop predictive models.

---

# 👨‍💻 About the Internship

**Internship:** Machine Learning & Data Science Internship  
**Organization:** Datheon  
**Domain:** Machine Learning, Data Science and Artificial Intelligence  
**Programming Language:** Python  
**Development Environment:** Jupyter Notebook / Google Colab  

---

# 📂 Repository Structure

```text
Datheon_Machine_Learning_&_Data_Science_Internship/
│
├── README.md
│
├── Task_1_Iris_Classification/
│   └── Iris_Classification.ipynb
│
├── Task_2_Housing_Regression/
│   └── California_Housing_Regression.ipynb
│
├── Task_3_Customer_Churn/
│   └── Customer_Churn_Prediction.ipynb
│
└── Task_4_Sentiment_Analysis/
    └── Sentiment_Analysis_NLP.ipynb
```

---

# 📊 PROJECTS

## 🌸 TASK 1: Iris Flower Classification

### Project Overview

The Iris Flower Classification project implements supervised machine learning algorithms to classify iris flowers into three different species based on their physical measurements.

The dataset contains four numerical features and three flower species.

### Dataset

Source: Seaborn Iris Dataset

https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Variable

- Setosa
- Versicolor
- Virginica

### Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Machine Learning Algorithms

1. Logistic Regression
2. Decision Tree Classifier

### Implementation Steps

1. Load the Iris dataset using Pandas.
2. Perform exploratory data analysis.
3. Visualize relationships using Seaborn pairplots.
4. Handle feature scaling using StandardScaler.
5. Split the dataset into 80% training and 20% testing.
6. Train Logistic Regression and Decision Tree models.
7. Evaluate classification performance.
8. Generate confusion matrix heatmaps.
9. Visualize decision boundaries.
10. Compare model performance.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Expected Outcome

Develop a classification model capable of predicting iris flower species using flower measurements.

---

## 🏠 TASK 2: California Housing Price Prediction

### Project Overview

This project uses supervised machine learning regression algorithms to predict median house values in California based on housing and demographic information.

The project focuses on regression analysis, feature engineering, missing value treatment, multicollinearity, and regularization.

### Dataset

California Housing Dataset

https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.csv

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

### Target Variable

- Median House Value

### Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels

### Machine Learning Algorithms

1. Ordinary Least Squares (OLS) Regression
2. Ridge Regression (L2 Regularization)
3. Lasso Regression (L1 Regularization)

### Implementation Steps

1. Load the California Housing dataset.
2. Perform exploratory data analysis.
3. Identify and handle missing values.
4. Generate correlation heatmaps.
5. Perform feature engineering.
6. Create interaction and ratio features.
7. Encode categorical variables using OneHotEncoder.
8. Standardize numerical features using StandardScaler.
9. Analyze multicollinearity using Variance Inflation Factor (VIF).
10. Train OLS, Ridge and Lasso models.
11. Optimize regularization parameters using GridSearchCV.
12. Evaluate regression performance.
13. Visualize actual versus predicted values.
14. Analyze residual distributions.
15. Compare model performance.

### Evaluation Metrics

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

### Expected Outcome

Build and compare regression models to predict California median housing prices and identify the best-performing model.

---

## 📞 TASK 3: Telecom Customer Churn Prediction

### Project Overview

This project develops an ensemble machine learning classification system to predict customer churn using telecom subscription records.

Customer churn refers to customers discontinuing their subscription or service.

The goal is to identify customers who are likely to leave a telecom company so that businesses can improve customer retention strategies.

### Dataset

IBM Telco Customer Churn Dataset

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

### Important Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Tech Support
- Contract
- Monthly Charges
- Total Charges

### Target Variable

- Churn (Yes / No)

### Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

### Machine Learning Algorithms

1. Random Forest Classifier
2. XGBoost Classifier

### Implementation Steps

1. Load the telecom customer churn dataset.
2. Explore the dataset and identify missing values.
3. Convert TotalCharges into numerical format.
4. Handle missing values using imputation.
5. Analyze customer churn distribution.
6. Perform exploratory data analysis.
7. Encode categorical features using OneHotEncoder.
8. Standardize numerical features.
9. Handle class imbalance using class weighting.
10. Train Random Forest and XGBoost classifiers.
11. Perform stratified cross-validation.
12. Optimize model hyperparameters using GridSearchCV.
13. Evaluate model performance.
14. Generate ROC-AUC curves.
15. Plot confusion matrices.
16. Extract the top 10 important features.
17. Compare model performance.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

### Expected Outcome

Develop an ensemble classification model that predicts whether telecom customers are likely to churn and identifies important factors associated with customer churn.

---

## 💬 TASK 4: Sentiment Analysis Using NLP

### Project Overview

This project develops a Natural Language Processing (NLP) classification system to analyze customer or movie reviews and classify them into positive and negative sentiments.

The project demonstrates text preprocessing, feature extraction, machine learning classification, and sentiment prediction on custom user input.

### Dataset

Sentiment Reviews Dataset

https://www.datheon.in/datasets/sentiment_reviews.csv

### Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

### NLP Techniques

1. Text Cleaning
2. Lowercasing
3. HTML Tag Removal
4. Punctuation Removal
5. Tokenization
6. Stopword Removal
7. Lemmatization
8. TF-IDF Vectorization

### Machine Learning Algorithms

1. Multinomial Naive Bayes
2. Logistic Regression

### Implementation Steps

1. Load the sentiment reviews dataset.
2. Explore the dataset and identify missing values.
3. Clean text by removing HTML tags and special characters.
4. Convert text into lowercase.
5. Perform word tokenization.
6. Remove unnecessary stopwords.
7. Apply lemmatization using WordNetLemmatizer.
8. Split the dataset into training and testing sets.
9. Convert text into numerical features using TF-IDF.
10. Train Multinomial Naive Bayes.
11. Train Logistic Regression.
12. Evaluate model performance.
13. Generate classification reports.
14. Visualize confusion matrices.
15. Compare model accuracy.
16. Plot ROC curves.
17. Develop a custom predict_sentiment() function.
18. Test custom review sentences.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

### Expected Outcome

Develop an NLP-based sentiment classification system capable of identifying positive and negative reviews and predicting sentiment for new user-provided text.

---

# 🛠️ Technologies and Tools

The following technologies and libraries are used throughout the projects.

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| NLTK | Natural Language Processing |
| XGBoost | Gradient boosting |
| Statsmodels | Statistical analysis |
| Jupyter Notebook | Development environment |
| Google Colab | Cloud notebook execution |
| GitHub | Version control and project hosting |

---

# ⚙️ Installation and Setup

## 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Datheon_Machine_Learning_&_Data_Science_Internship.git
```

## 2. Navigate to the project directory

```bash
cd Datheon_Machine_Learning_&_Data_Science_Internship
```

## 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
pip install nltk xgboost imbalanced-learn statsmodels
```

## 4. Run Jupyter Notebook

```bash
pip install notebook
jupyter notebook
```

Open the required project folder and execute the notebook cells.

Alternatively, upload the notebooks to Google Colab and run them online.

https://colab.research.google.com/

---

# 📈 Model Evaluation and Performance

Each project uses appropriate evaluation metrics to assess model performance.

| Project | Evaluation Metrics |
|---|---|
| Iris Classification | Accuracy, Precision, Recall, F1 |
| Housing Price Prediction | RMSE, MAE, R² |
| Customer Churn Prediction | Accuracy, Precision, Recall, F1, ROC-AUC |
| Sentiment Analysis | Accuracy, Precision, Recall, F1, ROC-AUC |

Actual model performance values are generated by executing the notebooks.

---

# 🎯 Learning Outcomes

Through these projects, I gained practical experience in:

- Data loading and preprocessing.
- Exploratory Data Analysis (EDA).
- Missing value handling.
- Feature scaling and encoding.
- Feature engineering.
- Correlation and multicollinearity analysis.
- Supervised machine learning.
- Classification and regression.
- Ensemble learning techniques.
- Natural Language Processing.
- TF-IDF feature extraction.
- Hyperparameter tuning.
- Cross-validation.
- Model evaluation and visualization.
- Building reusable prediction functions.
- Organizing projects using GitHub.

---

# 📌 Future Improvements

Potential improvements include:

- Advanced feature selection techniques.
- More extensive hyperparameter optimization.
- Testing additional machine learning algorithms.
- Deploying trained models using Flask or Streamlit.
- Creating interactive dashboards.
- Improving model generalization.
- Implementing automated model evaluation pipelines.

---

# 👨‍🎓 Author

**Name:** Amritha Nandakumar.A 
**Internship Organization:** Datheon  
**Internship Domain:** Machine Learning & Data Science  


---

# 📜 Internship Acknowledgement

I would like to thank **Datheon** for providing the opportunity to work on practical Machine Learning and Data Science projects.

These projects helped me strengthen my Python programming skills and gain hands-on experience with real-world datasets and machine learning algorithms.

This repository is maintained as a portfolio of my internship project implementations.

---

# ⭐ Repository Information

**Repository Name:** Datheon_Machine_Learning_&_Data_Science_Internship

**Visibility:** Public

**Projects:** 4

**Programming Language:** Python

**Domain:** Machine Learning & Data Science

---

⭐ If you find this repository useful, feel free to explore the projects and their implementations.

**Thank you for visiting my repository!**
