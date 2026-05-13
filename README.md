🩺 Heart Disease Risk Prediction: From Raw Data to Clinical Insights

📋 Project Overview :

This project was developed as a final graduation requirement for the NTI Data Analysis Program. Our goal was to analyze 70,000 patient records 
to identify the most significant drivers of heart disease and build a predictive model to categorize patient risk levels.

👥 Team Collaboration & Workflow :

This was a multi-stage collaborative project. We divided the data pipeline into three main phases to ensure comprehensive analysis:

Stage 1: 🥇 Descriptive Distribution (Excel) 🟢 📊  – Handled by Esraa Fathy : 

Focused on data cleaning and initial frequency distribution of patient demographics.

Stage 2: 🥈 Prevalence Dashboards (Power BI) 🟡 📈  – Handled by Aya El-Mowafy : 

Focused on interactive visualizations to map out the prevalence of risk factors.

Stage 3: 🥉 Statistical Modeling & Predictive Insights (Python) 🐍 – My Role:

Conducted advanced statistical testing (Correlation & Multicollinearity/VIF).

Developed a Binary Logistic Regression model achieving 99% accuracy.

Interpreted Odds Ratios to translate statistical weights into clinical logic.

Identified the "Tipping Point" where risk escalates based on factor accumulation.

#########################################################################################

Statistical Foundation 🧠 : 

What's the statistical model and how it works :

Here is a simple breakdown of how it works for non-statisticians:
A statistical model is a mathematical "translator." It takes silent, raw data and converts it into meaningful predictions. By analyzing patterns from the past
, the model creates a map to predict future outcomes, helping us make decisions based on facts rather than intuition.

Categorical Data & Model Selection :

When dealing with categorical outcomes, traditional linear models are insufficient. Since our study aims to predict a Binary Outcome (Target: 1 for Heart Disease Risk, 0 for No Risk)
, the Binary Logistic Regression Model (BLRM) was selected as the most appropriate tool for this classification task.

Data Testing:

We performed Multicollinearity checks (VIF) and correlation analysis
to ensure variable independence and prevent model instability before training.

Model Diagnosis:

The model achieved 99% accuracy, validated through a classification matrix and Odds Ratio analysis
to ensure clinical reliability and precise risk-factor interpretation.

#########################################################################################
To predict heart disease risk, I used a Binary Logistic Regression model. 

1. The Goal (Probability) 🎯 :
   
Instead of just saying 'Yes' or 'No', this model calculates the Probability (from 0% to 100%) that a patient might have heart disease
based on their health data.

2. The Impact (Odds Ratio):
   
Think of the model as a judge that weighs different pieces of evidence (like blood pressure, smoking, and age).
We use a metric called the 'Odds Ratio' to understand the strength of each piece of evidence.

Example: If Age has an Odds Ratio of 1.1, it means that for every year a person gets older
, their risk 'odds' increase by 10%, assuming everything else stays the same.

3. Isolation of Factors:
   
The beauty of this statistical model is that it looks at each factor individually while 'freezing' the others. This means it can tell us the danger of smoking regardless of the patient's age or weight.

4. The Final Classification:
   
Once the model weighs all 8 factors, it gives a final score. Based on this score, we categorized patients into:

Low Risk: Very few factors present.

Medium Risk: Reaching the 'Tipping Point'⚠️.

High Risk: Multiple factors (5 to 8) working together to increase the danger."
Comorbidity Heatmap: Visualized the synergy between 8 clinical variables.

Risk Categorization: Built an algorithm to classify patients into Low, Medium, and High-risk profiles.

## 🔗 Connect & Discuss
Feel free to check out the **project announcement and discussion** on LinkedIn:
[👉 View LinkedIn Post]([رابط_البوست_هن](https://www.linkedin.com/posts/dai-elashry-04a31a27a_heart-disease-risk-prediction-ugcPost-7459671080044134400-l9QZ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEQI2LoBccDjmnZX1MgmyCuhrSGYC7Amg2Y))
