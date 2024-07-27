Capstone Project: Capstone Project: Student Study Performance Analysis

Author: Bhavik Jikadara

Executive Summary: The aim of this study is to demonstrate and understand how student health, family involvement, and ethnicity influences academic performance. Key variables that influenced students’ test results were identified using a massive dataset and many machine learning models.

Rationale: To develop focused interventions and policies for improving education outcomes, understanding factors such as health, parental involvement, and ethnicity that influence academic achievement are important. By identifying key elements that affect student performances, educators and policymakers can maximize the use of available resources and create educational initiatives that will enable each child to achieve their highest potential.

Research Question: How does ethnicity, parental involvement, and student health impact the academic performance in terms of their information processing abilities as well as achieving higher test scores?

Data Sources: Analysis was conducted using Kaggle’s “Student Performance Linear Regression” dataset. Link to Dataset: https://www.kaggle.com/datasets/bhavikjikadara/student-study-performance/code

Methodology:
1. Data Preprocessing:
   - Handling missing values
   - Encoding categorical variables
2. Exploratory Data Analysis (EDA):
   - Data visualization and interpretation
3. Modeling:
   - Implemented Decision Trees, k-Nearest Neighbors (kNN), Support Vector Machines (SVM), and Linear Regression
4. Model Evaluation:
   - Accuracy, Mean Squared Error (MSE), R-squared
   - Cross-validation for robustness
5. Hyperparameter Tuning:
   - Grid Search for optimizing model parameters

Results:
- Best Performing Model: The Support Vector Machine (SVM) model achieved an accuracy of 0.215 for math test and 0.21 for the reading test. Whereas for the writing test the Logistic Regression Model with an accuracy of 0.095.
- Important Features: Significant predictors of student performance included parental level of education, lunch type, and test preparation courses.
- Ethnic Differences: Academic performance varied across different ethnic groups.
- Health Impact: Students with better health indicators generally scored higher on tests.
- Parental Involvement: When there is more parental involvement was linked to improved academic outcomes.

Next steps:
1. Further Research: To be able to find out additional factors that influences student performance, including socio-economic status, school infrastructure, and teacher quality.
2. Intervention Programs: To be able to design and test programs that enhance student health and family participation.
3. Policy Recommendations: To be able to offer data-driven insights to help decision-makers make educated choices.

Outline of project

- http://localhost:8890/notebooks/Arshiyaan%20Final%20Report%20and%20Exploratory%20Data%20Analysis%20(EDA).ipynb

Contact and Further Information
For any questions or further information, please contact arsh.pabrai@gmail.com
