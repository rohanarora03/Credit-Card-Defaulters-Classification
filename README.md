# Credit-Card-Defaulters-Classification

**Description:**
This project involves predictive analysis of credit card default payments in Taiwan, utilizing demographic and financial variables from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients). The objective is to build an accurate classification model to identify potential defaulters.

**Project Overview:**
Credit card default prediction is crucial for financial institutions to manage credit risk and reduce financial losses. This project employs various machine learning algorithms to predict default payments, enhancing decision-making processes in the credit industry.

**Key Features:**
- **Data Processing and ETL:** Efficient extraction, transformation, and loading of data to ensure high-quality inputs for the machine learning models.

- **Statistical Analysis and EDA:** Thorough exploratory data analysis (EDA) to understand the data distribution, identify patterns, and detect anomalies. Statistical analysis helps in selecting the most accurate predictors of defaulters.

- **Correlation Analysis:** Identifying significant relationships between variables to enhance the predictive power of the models.

- **Data Engineering and Modeling:** Applying data engineering and data warehousing techniques to create a structured and optimized dataset for model training, employing data modeling techniques to build and refine machine learning models.

- **Model Development:** Utilization of various classification algorithms, focusing on achieving high prediction accuracy. The LightGBM algorithm, in particular, achieved an impressive 82% accuracy.

- **Model Evaluation:** Assessing model performance using data mining techniques such as ROC curve, AUC, and confusion matrix to ensure reliable predictions and identify key predictors of default payments.

**Methodology:**
- **Data Preparation:**
  - Load and preprocess the dataset.
  - Handle missing values and outliers.
  - Perform feature engineering and selection.
- **Exploratory Data Analysis (EDA):**
  - Visualize data distributions and relationships.
  - Conduct statistical tests to identify significant predictors.
- **Model Building:**
  - Implement various classification algorithms including Logistic Regression, Decision Trees, Random Forest, and LightGBM.
  - Train and optimize models using cross-validation techniques.
- **Model Evaluation:**
  - Evaluate models using metrics such as accuracy, ROC curve, AUC, and confusion matrix.
  - Identify the best-performing model based on evaluation metrics.

**Results:**
The LightGBM algorithm achieved the highest prediction accuracy of 82%. Key predictors of default payments were identified, providing valuable insights into the factors influencing credit card defaults.

**Conclusion:**
This project demonstrates the effective use of machine learning techniques to predict credit card defaulters. The insights gained can be utilized by financial institutions to mitigate risks and make informed decisions.
