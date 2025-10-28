# Supermarket-Sales-Prediction-ML-Project
Developed a Machine Learning model to predict supermarket sales using Python. Performed data cleaning, EDA, and feature encoding, then trained Linear Regression and Random Forest models. Delivered insights on sales trends, customer behavior, and top-performing branches.

<img width="697" height="775" alt="Screenshot 2025-10-28 193928" src="https://github.com/user-attachments/assets/b9b395ab-0850-4045-b795-52b5c38f4252" />

<img width="738" height="783" alt="Screenshot 2025-10-28 194128" src="https://github.com/user-attachments/assets/487e9e7d-df7f-4cdb-9854-d8f5e3332dec" />

<img width="818" height="729" alt="Screenshot 2025-10-28 194143" src="https://github.com/user-attachments/assets/a2a5a16e-b7c6-4e52-99f3-e872d9aaffbe" />

### Project Overview

- The dataset contained details like:

- Branch, City, Customer Type, Gender

- Product Line, Unit Price, Quantity, Rating

- Payment Method and Total Sales

### Technical Workflow

#### Data Preprocessing

1) Handled missing and duplicate values

2) Removed outliers using IQR technique

3) Encoded categorical columns with Label Encoding

#### Exploratory Data Analysis (EDA)

1) Visualized sales trends by branch, gender, and product line

2) Analyzed payment method distribution and ratings

3) Generated correlation heatmaps and scatterplots to study relationships

#### Model Development

Split data into 80% training and 20% testing

Trained two regression models:
🔹 Linear Regression
🔹 Random Forest Regressor

#### Model Evaluation
Evaluated models using:
✅ Mean Squared Error (MSE)
✅ Mean Absolute Error (MAE)
✅ R² Score
✅ Root Mean Squared Error (RMSE)

### Result:
The Random Forest Regressor achieved higher accuracy and better generalization compared to Linear Regression.

### Key Insights

- Product line and Rating had strong influence on total sales

- E-wallet and Credit Card users showed higher transaction totals

- Branch-level comparison helped identify top-performing outlets


### Outcome

Built a predictive model to forecast sales trends, understand customer behavior, and support business decision-making in retail analytics.
