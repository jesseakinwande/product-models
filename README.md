Title: Exploring the Likelihood of Default Payments through Logistic Regression 
Analysis

Can the likelihood of default payments be effectively determined by analyzing 
specific customer characteristics and repayment history using logistic regression?

## Dataset

The dataset used in this project can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients).

1. Visit the [dataset page](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients).
2. Download the dataset files from the provided links.

Dataset Description

The research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. The study reviewed the literature and used the following 23 variables as explanatory variables:
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. 
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

## Getting Started

To utilize this project effectively, follow the steps outlined below:

1. Download the Dataset:
   - Visit the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients).
   - Download the dataset files from the provided links.
   - convert from xls format to csv, remove the descriptive row and load the dataset or simply download from github 

2. Run the Jupyter Notebooks:
   - Open the Jupyter Notebooks containing the analysis and modeling code.
   - Ensure that you have the required dependencies installed.

3. Exploratory Data Analysis (EDA):
   - Explore the dataset using visualizations and statistical analysis.
   - Gain insights into the distribution of features and their relationships.

4. Build Logistic Regression Model:
   - Execute the Jupyter Notebook containing the logistic regression model.
   - Observe the model's accuracy, precision, recall, and other relevant metrics.

5. Feature Importance Analysis:
   - Review the feature importance analysis to understand the factors influencing the likelihood of default.

6. Create Visualizations:
   - Use Matplotlib or other visualization tools to generate insightful graphs and charts.


