# Linear Regression on 50 Startups in the USA

## Who
This project analyzes **50 startups** in the USA, focusing on how different expenses impact their **profitability**. The dataset includes financial information from various industries.

## What
The goal is to use **Multiple Linear Regression** to predict **profit** based on three independent variables:
- **R&D Spend ($)**: Investment in research and development.
- **Administration ($)**: Costs associated with administrative functions.
- **Marketing Spend ($)**: Budget allocated to marketing strategies.

## When
This dataset represents a snapshot of **startup financials**, making it relevant for business decision-making today. The project follows a structured approach, from **data preprocessing to model evaluation**.

## Where
The dataset comprises startups **based in the USA**, allowing us to gain insights into the American startup ecosystem and financial trends.

## Why
Understanding the **key drivers of profit** helps businesses make informed investment decisions. This project highlights the most impactful expenses, assisting **entrepreneurs and investors** in optimizing financial strategies.

## How
### 1. Data Preprocessing
- Load the dataset using Pandas.
- Handle missing values and encode categorical data (if applicable).
- Split the data into training and testing sets (80%-20%).

### 2. Applying Multiple Linear Regression
The **Multiple Linear Regression** formula:

![image](https://github.com/user-attachments/assets/b00088bd-5456-479b-a83f-a1c7276afd07)

- **Y** = Profit (dependent variable)
- **X1, X2, X3** = R&D Spend, Administration, and Marketing Spend (independent variables)
- **β0** = Intercept
- **β1, β2, β3** = Coefficients (impact of each variable)
- **ε** = Error term

### 3. Model Training and Evaluation
- Train the model on the training set.
- Evaluate performance using **R-squared (R²) score** and **Mean Squared Error (MSE)**.
- Interpret coefficients to understand variable impact.

![image](https://github.com/user-attachments/assets/4071566c-61ab-4d3a-afb5-a98578701958)
![image](https://github.com/user-attachments/assets/f059ba3c-ddda-49c0-af62-ee28eb5a48b7)

## Results and Insights
- **R&D Spend** has the most significant impact on profit.
- **Marketing Spend** contributes positively but with lower significance.
- **Administration costs** have minimal or negligible impact.
- A high **R² value** indicates that the model effectively explains profit variations.

## Conclusion
This project demonstrates the application of **Multiple Linear Regression** in business analytics, helping startups and investors understand **profit-driving factors**. The results suggest that prioritizing **R&D investment** leads to **higher profitability**.

## Future Improvements
- Experiment with **feature engineering** to improve model accuracy.
- Explore **advanced regression techniques** like **Polynomial Regression** or **Decision Trees**.
- Incorporate **additional business factors** like market trends and competition.

### Keywords: Linear Regression, Machine Learning, Business Analytics, Profit Prediction, Python

