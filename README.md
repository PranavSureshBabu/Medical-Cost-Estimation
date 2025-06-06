# Medical-Cost-Estimation

![image](https://github.com/user-attachments/assets/38175693-13cb-4446-86ae-a52bfc107883)


**🩺Overview:**

Predicting medical expenses has become increasingly critical in the healthcare and insurance industries. This project explores how demographic and lifestyle variables influence individual medical costs, enabling stakeholders to make informed decisions around pricing and risk. Using a dataset of over 2,700 records, we develop a predictive regression model that estimates insurance charges based on attributes such as age, BMI, smoking status, and more.

By identifying patterns and quantifying their impact on charges, the model aids insurers in risk stratification and cost forecasting while providing interpretability into healthcare cost drivers.

**📊 Dataset Overview**
The medical insurance dataset encompasses a variety of features known to affect healthcare expenditures. These include:

* Age

* Sex

* BMI (Body Mass Index)

* Number of Children

* Smoking Status

* Region

* Charges (Target variable)

This dataset contains approximately 2,700 rows and 7 columns. It serves as a foundation for building machine learning models capable of forecasting future expenses for new insurance applicants, thereby supporting data-driven pricing and policy design.

**🎯 Objectives**

* Explore and analyze key features influencing insurance charges

* Visualize correlations and distributions among variables

* Build and evaluate a regression model to predict medical expenses

* Interpret feature importance for actionable business insights


![image](https://github.com/user-attachments/assets/73aeaf43-5fe3-42da-8d56-70455e506a4f)

**📌 Key Steps & Methodology**

1. Data Cleaning & Preprocessing

* Converted categorical variables using Label Encoding

* Checked for null values and ensured data integrity

2. Exploratory Data Analysis (EDA)

* Visualized distributions (e.g., charges by smoking status)

* Created correlation heatmaps to identify feature relationships

* Detected outliers and variable trends

3. Feature Selection

* Analyzed the importance of features such as age, BMI, and smoker

* Removed less impactful features for model optimization

4. Model Building

* Trained a Linear Regression model using scikit-learn

* Split the data into training and testing sets (80:20 ratio)

* Evaluated performance using R² and MAE metrics

5. Insights

* Smoking and BMI significantly influence charges

* Older individuals and those with higher BMI face higher premiums

* Regional and gender differences were less impactful

**🚀 How to Run the Notebook**

* Clone the repository or download the notebook

Install the required packages:
* pip install pandas numpy matplotlib seaborn scikit-learn
  
* Launch Jupyter Notebook and open Medical_expense_prediction.ipynb

* Run each cell in order to preprocess data, train the model, and view results
