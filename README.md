# Credit-Risk-Analysis-and-Prediction-Modelling-of-Bank-loans

**Situation:**

A financial institution is looking to improve its credit risk assessment process for loan applicants. Currently, the institution relies on traditional methods which may not effectively capture the nuances of individual borrower risk. To enhance their decision-making process, they aim to implement data-driven credit risk models.

**Task:**


The task involves building and deploying credit risk prediction models using machine learning techniques. The primary objective is to accurately assess the probability of default (PD) for loan applicants based on various features provided in the dataset. This involves several steps:

Data Preprocessing:

Summary statistics and descriptive statistics analysis to understand the dataset's characteristics.
Handling missing values and null values to ensure data integrity.
Identifying and removing duplicate records to avoid bias in model training.
Detecting and addressing outliers in the dataset.
Exploratory Data Analysis:

Visualizing the distribution of features using bar plots and histograms to gain insights into the data.
Feature Engineering:

Standard scaling normalization to bring continuous variables to the same range.
Handling Imbalanced Data:

Using Synthetic Minority Over-sampling Technique (SMOTE) to address the imbalance in the target variable (probability of default).
Model Building:

Implementing various classification models including Decision Tree, Random Forest, and Logistic Regression.
Model Evaluation:

Assessing model performance using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.
Model Optimization:

Tuning hyperparameters to improve the performance of the best-performing models.
Deployment:

Deploying the optimized model into the institution's existing credit risk assessment system for real-time predictions.

**Action:**


The project team collected the dataset from a reliable source (UCI Machine Learning Repository) and performed thorough data preprocessing and exploratory analysis. They utilized Python libraries such as pandas, NumPy, and seaborn for data manipulation and visualization. Machine learning models were built using scikit-learn, and techniques like SMOTE were applied to handle imbalanced data. Various classification algorithms were trained and evaluated to identify the best-performing model.

**Result:**


After implementing the models and evaluating their performance, the project achieved an accuracy of 85%. The optimized model was deployed successfully into the institution's credit risk assessment system, improving the accuracy of loan default predictions and enhancing the overall decision-making process.
