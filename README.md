# Customer Demographics and Shopping Behavior Analysis

## Project Overview
This project focuses on analyzing customer data to better understand shopping behaviors, particularly for the age group 18-25. The analysis is conducted in two phases:

- **Phase 1**: Exploratory Data Analysis (EDA) – Uncovering initial insights and patterns in the data.
- **Phase 2**: Statistical Analysis – Conducting deeper analysis to validate and quantify the patterns observed in Phase 1.

## Dataset
The dataset consists of customer demographic information and transaction details, including payment methods and shopping categories.


## Phases

### Phase 1: Exploratory Data Analysis (EDA)
In this phase, we explored the dataset to derive insights into the behavior of customers, focusing on the age group 18-25.

#### Key Findings:
1. **Customer Base**: Customers aged 18-25 account for ~26% of the total customer base.
2. **Annual Income**: The average annual income for this group is less than $50,000, suggesting they are generally in the early stages of their careers or education.
3. **Credit History**: This age group has limited credit history, reflected by lower credit scores and credit limits compared to older age groups.
4. **Payment Methods**: The use of credit cards is relatively low in this group, which may be due to limited credit access or a preference for other payment methods like debit cards or digital wallets.
5. **Top Shopping Categories**:
   - **Electronics**: Popular for gadgets and tech purchases.
   - **Fashion & Apparel**: Reflects the trend-driven nature of this age group.
   - **Beauty & Personal Care**: Indicates an interest in self-care products.

Visualizations were created to represent these insights using **Matplotlib** and **Seaborn**.

### Phase 2: Statistical Analysis
In this phase, we perform a detailed statistical analysis to confirm the trends observed in the EDA and to draw meaningful conclusions. The analysis involves:

- **Hypothesis Testing**: We conduct hypothesis tests to verify assumptions, such as whether the average income of customers aged 18-25 is significantly lower than other age groups.
  - Null Hypothesis (H₀): There is **no significant difference** in the income of the age group 18-25 compared to others.
  - Alternative Hypothesis (H₁): There is a **significant difference** in income.
  
- **Correlation Analysis**: We explore the relationship between different variables, such as income and credit score or payment methods and spending patterns.
  
- **Regression Analysis**: We use regression models to predict purchase amounts based on demographics like income, credit score, and age.

### Tools and Technologies
- **Python**: Primary language used for the analysis.
- **Pandas**: For data manipulation, cleaning, and aggregation.
- **Matplotlib & Seaborn**: For generating insightful data visualizations.
- **NumPy & SciPy**: For performing statistical tests and mathematical calculations.
- **Jupyter Notebooks**: For interactive and iterative data exploration.

