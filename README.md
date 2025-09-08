# Predictive-modeling-for-healthcare-costs-using-Machine-Learning
## Project Objective

## Dataset used
  - <a href="https://github.com/CHBLESSY/Predictive-modeling-for-healthcare-costs-using-Machine-Learning/blob/main/hospital%20dataset.csv">Data set</a>

## Questions (KPIs)
   - Percentage of predictions within an acceptable error margin (e.g., ±10%).
   - Changes in average healthcare costs across age groups, BMI levels, and regions.
   - Breakdown of predicted costs by demographic categories (gender, smoker/non-smoker, dependents, etc.).
   - Top factors influencing healthcare costs and their relative importance scores.
   - Relationship between healthcare costs and lifestyle factors (BMI, smoking, exercise).
   - Comparison of model performance (MAE, RMSE, R²) across different machine learning algorithms.
   - Predicted vs. actual cost trends (daily, monthly, or yearly, depending on data).
   - Identification of high-risk patient groups likely to incur higher costs.
## Process
  ### Data Collection
  - Gather healthcare cost dataset (e.g., age, BMI, smoking status, region, dependents, charges).
  ### Data Preprocessing
  - Handle missing values and outliers
  - Encode categorical variables (e.g., gender, smoker, region)
  - Normalize/standardize numerical features
  ### Exploratory Data Analysis (EDA)
  - Visualize distributions and correlations
  - Identify key cost drivers (age, BMI, smoking, etc.)
  - Detect demographic and regional trends
  ### Feature Engineering
  - Create new features (e.g., age groups, BMI categories)
  - Perform feature selection using correlation and importance metrics
  ### Model Building
  - Train multiple ML models:
  - Linear Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine
  - Artificial Neural Network
  ### Model Evaluation
  - Evaluate models using MAE, RMSE, and R²
  - Compare performance to select the best model
  ### Prediction & Insights
  - Predict healthcare costs for new patients
  - Analyze model results and feature importance
  - Provide actionable insights (e.g., high-risk patient groups)
  ### Visualization & Dashboard
  - Build charts/plots for cost trends and model performance


## Project insight
  - Healthcare costs are strongly influenced by lifestyle factors such as smoking and BMI, making them critical predictors.
  - Smokers consistently show higher predicted costs compared to non-smokers, regardless of age or region.
  -  BMI is positively correlated with healthcare costs – individuals with obesity are more likely to incur higher charges.
  -  age is a significant driver – older patients generally have higher costs, but lifestyle factors amplify this further.
  -  Model comparison shows that ensemble methods (e.g., Random Forest, Gradient Boosting) provide better accuracy than simple regression models.
  -  Demographic breakdown (region, gender, dependents) reveals subtle differences in cost patterns, useful for policy and insurance planning.
  -  High-risk groups can be identified for preventive interventions, reducing long-term healthcare expenses.
  -  The predictive model can support insurance companies and hospitals in optimizing cost estimation and resource allocation.
  -  Create interactive dashboard (Power BI / Matplotlib / Seaborn)

## Conclusion
   This project demonstrates how machine learning can be effectively applied to predict healthcare costs with high accuracy. By analyzing demographic, lifestyle, and medical-related features, the models provide valuable insights into cost drivers such as age, BMI, and smoking status. Among the tested algorithms, ensemble methods showed superior performance, highlighting their ability to handle complex, non-linear relationships in healthcare data.
