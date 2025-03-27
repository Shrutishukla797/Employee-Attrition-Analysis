# Employee Attrition Analysis
<hr>

## Project Overview
Employee attrition poses significant challenges for organizations, leading to increased recruitment costs and potential loss of talent. This project analyzes employee turnover trends and identifies key factors contributing to attrition using machine learning techniques. The insights derived can assist HR teams in making data-driven decisions to improve employee retention.

## Objectives
* Analyze attrition trends across different employee demographics.
* Identify key factors influencing employee turnover.
* Develop predictive models to assess attrition risk.
* Provide data-driven recommendations to improve retention strategies.

## Dataset Summary
* Source: IBM (Synthetic dataset for research and analytical purposes)
* Size: 1,470 records, 35 features
* Key Variables:
Demographics: Age, Gender, Marital Status
Job-Related: Job Role, Department, Work Experience
Compensation: Monthly Income, Salary Hike Percentage
Work-Life Balance: Overtime, Job Satisfaction, Distance from Home

## Methodology
**1. Data Preprocessing**
* Cleaned and handled missing values.
* Encoded categorical variables for modeling.

**2. Exploratory Data Analysis (EDA)**
* Visualized attrition patterns using statistical and graphical analysis.
* Examined correlations between employee attributes and attrition.

**3. Machine Learning Model**
* Algorithm Used: Decision Tree Classifier
* Handling Imbalance: Stratified sampling to improve model generalization.

## Model Evaluation:
* K-Fold Cross-Validation
* ROC Curve Analysis
* F1 Score and Confusion Matrix

## Key Insights & Findings
* Age Factor: Employees under 40 have a higher attrition rate.
* Compensation: Lower salaries and fewer salary hikes significantly contribute to attrition.
* Work-Life Balance: Employees working overtime frequently are more likely to leave.
* Departmental Trends: Higher turnover observed in Sales and HR roles.
* Distance from Home: Employees commuting long distances have a higher probability of leaving.

## Model Performance
* ROC-AUC Score: 0.6128
* F1 Score: 0.81
* Confusion Matrix: Indicates class imbalance affecting model accuracy.

## Recommendations
* Enhance Compensation & Benefits: Competitive salary structures can reduce attrition.
* Flexible Work Policies: Introducing remote work and flexible schedules to improve work-life balance.
* Career Growth Opportunities: Regular performance evaluations and structured promotions.
* Employee Engagement Initiatives: Training programs and mentorship can boost job satisfaction.

## Technologies & Tools
* Programming Language: Python
* Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* Platform: Jupyter Notebook
* Machine Learning Model: Decision Tree Classifier
