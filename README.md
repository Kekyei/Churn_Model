# PowerCo Churn Prediction
## Background
PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

![output](https://user-images.githubusercontent.com/115629197/200139179-17a17aa2-5ed2-4a65-8bea-ee9546dbbf6b.png)
## Objectives
The main objectives of this project are:

1. Formulate the hypothesis of price sensitivity as a data science problem and lay out the major steps needed to test this hypothesis.
2. Perform exploratory data analysis on the provided customer and pricing data to gain a holistic understanding of the dataset and verify the hypothesis of price sensitivity being correlated with churn.
3. Develop a predictive model to accurately identify which SME customers are at risk of churning based on their price sensitivity and other relevant factors.
4. Provide recommendations to the client on how to use the model to offer targeted discounts and reduce churn in the SME segment.
## Data
The data provided for this project includes historical customer data such as usage, sign up date, forecasted usage, and a churn indicator. It also includes historical pricing data, including variable and fixed pricing. The data is provided in a structured format (e.g. CSV files) and includes a combination of numerical and categorical variables.

## Methodology
The following steps will be taken to complete this project:

1. Data exploration: Understanding the data types, statistics, and variable distributions in the customer and pricing data.
2. Price sensitivity calculation: Defining and calculating price sensitivity as a measure of the impact of price on customer churn.
3. Model development: Selecting an appropriate machine learning algorithm and training a model on the cleaned and transformed data to predict churn based on price sensitivity and other relevant factors.
4. Model evaluation: Testing the model on a holdout dataset and evaluating its performance using relevant evaluation metrics.
5. Results and recommendations: Summarizing the findings and providing recommendations to the client on how to use the model to offer targeted discounts and reduce churn in the SME segment.
## Tools and Technologies
The following tools and technologies will be used in this project:

1. Python programming language
2. Pandas and NumPy libraries for data manipulation and analysis
2. Matplotlib and Seaborn libraries for data visualization
3. scikit-learn library for machine learning
## Results and Recommendations
Based on the analysis and modeling results, we have identified the following recommendations for PowerCo to reduce churn in the SME segment:

1. Offer targeted discounts to customers who are identified as high risk for churn based on the predictions of the churn prediction model.
2. Monitor the effectiveness of the discounts in reducing churn and make adjustments as necessary.
3. Consider other factors that may impact churn
