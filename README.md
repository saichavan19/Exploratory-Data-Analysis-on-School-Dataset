# Exploratory-Data-Analysis-on-School-Dataset
This project analyzes a school dataset to identify factors affecting student performance using data cleaning and visualization techniques. It explores relationships between variables like teacher-student ratio and parental literacy. A Linear Regression model is used to predict student scores and evaluate performance.

📊 Project Summary: Exploratory Data Analysis on School Dataset

🔹 Objective
The main objective of this project is to analyze the school dataset to understand the factors affecting student performance and to build a basic model to predict student scores using data analysis and machine learning techniques.

🔹 Dataset Description
The dataset contains information about students such as:
Academic scores (Math, Science, etc.)
Socio-economic factors (Urban/Rural, Electricity, Internet)
Educational environment (Teacher-Student Ratio, Parent Literacy)
The target variable is automatically selected as Score (or the last column if not present).

🔹 Steps Performed
✅ 1. Data Understanding
Displayed first 5 rows using head()
Checked dataset structure using info() and shape
Identified data types and column names
Generated statistical summary using describe()

✅ 2. Data Cleaning
Handled missing values:
Numerical → filled with mean
Categorical → filled with mode
Removed duplicate records
Ensured dataset consistency for analysis

✅ 3. Univariate Analysis
Analyzed individual variables using:
Histograms for numerical features
Count plots for categorical features
Observed distribution patterns and data spread

✅ 4. Bivariate Analysis
Studied relationships between variables:
Scatter plots (numerical vs target)
Box plots (categorical vs target)
Identified key factors influencing student performance

✅ 5. Correlation Analysis
Generated correlation matrix and heatmap
Identified:
Strong positive correlations
Negative relationships between variables

✅ 6. Insights Generated
Found most positively and negatively correlated features
Calculated:
Average score
Maximum and minimum values
Compared performance across categories
Detected outliers using IQR method

✅ 7. Feature Engineering
Created a new feature Total by summing numerical columns
Enhanced dataset for better model performance

✅ 8. Machine Learning Model
Used Linear Regression for prediction
Steps:
Converted categorical data using one-hot encoding
Split dataset into training and testing sets
Trained model using training data
Predicted results on test data

✅ 9. Model Evaluation
Evaluated performance using:
Mean Absolute Error (MAE)
R² Score (Coefficient of Determination)
Measured how well the model predicts student scores

🔹 Conclusion
Student performance is influenced by multiple factors such as parent literacy, infrastructure, and teacher-student ratio
Data preprocessing significantly improves analysis quality
Linear Regression provides a basic understanding of prediction, though performance can be improved using advanced models

🔹 Future Scope
Apply advanced algorithms (Decision Tree, Random Forest)
Perform feature selection for better accuracy
Use larger and more diverse datasets
Deploy model as a web application
