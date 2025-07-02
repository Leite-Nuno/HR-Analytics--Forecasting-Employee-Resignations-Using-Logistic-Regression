# HR Analytics: Forecasting Employee Resignations Using Logistic Regression

Predict employee resignations using HR data and logistic regression. This project includes feature engineering, data visualization, and a pipeline for preprocessing and modeling to understand and forecast voluntary employee turnover.

## Project Overview

This project aims to analyze and predict employee resignations within an Indian company using HR data. The dataset includes features such as Education, Joining Year, City, Payment Tier, Age, Gender, Ever Benched, Experience in Current Domain, and the target variable LeaveOrNot (0 for staying, 1 for leaving).

The goal is to understand the factors influencing voluntary resignations and build a predictive model to identify employees likely to leave.

## Dataset

The dataset contains the following variables:

- **Education:** Employee's education level  
- **JoiningYear:** The year the employee joined the company  
- **City:** City where the employee is located  
- **PaymentTier:** Salary tier of the employee  
- **Age:** Employee's age  
- **Gender:** Employee's gender  
- **EverBenched:** Whether the employee was ever benched (yes/no)  
- **ExperienceInCurrentDomain:** Years of experience in the current domain  
- **LeaveOrNot:** Target variable indicating if the employee left (1) or stayed (0)  

## Methodology

1. **Feature Engineering:**  
   - Derived new features to better capture employee characteristics and behaviors.

2. **Exploratory Data Analysis (EDA):**  
   - Created 7 visualizations to understand distributions, correlations, and trends within the data.

3. **Data Preprocessing Pipeline:**  
   - Built a data transformation pipeline to prepare features for modeling, including encoding categorical variables and scaling numerical features.

4. **Modeling:**  
   - Used Logistic Regression to predict the LeaveOrNot variable and analyze factors affecting employee turnover.

## Results

- The logistic regression model provides insights into the key drivers of employee resignation.  
- Feature importance and coefficients were analyzed to interpret the model’s decisions.

## How to Use

1. Clone the repository:  
```bash
git clone https://github.com/Leite-Nuno/HR-Analytics--Forecasting-Employee-Resignations-Using-Logistic-Regression.git
```

## Install dependencies

Install the necessary Python packages with:  
```bash
pip install -r requirements.txt
```

## Technologies Used

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- Jupyter Notebook  

## Author

Nuno Leite  
[LinkedIn Profile](https://www.linkedin.com/in/nuno-leite-mkt/)

