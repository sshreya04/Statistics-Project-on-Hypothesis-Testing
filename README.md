# Statistics-Project-on-Hypothesis-Testing
Link to get the dataset: https://data.world/vizwiz/nyc-taxi-jan-2020/workspace/file?filename=yellow_tripdata_2020-01.csv

*Maximizing Revenue for Taxi Cab Drivers- Through Payment Type Analysis*

In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness. Our goal is to use data-driven insights to maximize revenue streams for taxi drivers in order to meet this need. Our research aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type and fare amount.

*Objective*

This project's main goal is to run an A/B test to examine the relationship between the total fare and the method of payment. We use Python hypothesis testing and descriptive statistics to extract useful information that can help taxi drivers generate more cash. In particular, we want to find out if there is a significant difference in the fares to those who pay with credit cards versus those who pay with cash.

*Exploratory Data Analysis*

1. Data Loading- We load the dataset using pandas library in Python. The dataset contains information about taxi trips, including payment type, fare amount, and trip distance.
2. Data Cleaning- We clean the data by removing missing values and duplicates. We also convert data types to ensure consistency and accuracy.
3. Feature Extraction- We extract relevant features from the dataset, such as passenger count, payment type, fare amount, trip distance, and duration.

*Data Overview*

For this analysis, we utilized the comprehensive dataset of NYC Taxi Trip records, used data cleaning and feature engineering procedures to concentrate solely on the relevant columns essential for our investigation.

Relevant columns used for this research:

1. passenger_count (1 to 5)
2. payment_type (card or cash)
3. fare_amount
4. trip_distance (miles)
5. duration (minutes)

*Methodology*

1. Descriptive Analysis- Performed statistical analysis to summarize key aspects of the data, focusing on fare amounts and payment types.
2. Hypothesis Testing- Conducted a T-test to evaluate the relationship between payment type and fare amount, testing the hypothesis that different payment methods influence fare amounts.

*Distribution of Fare Amount*

We visualize the distribution of fare amounts for both credit card and cash payments using histograms. This helps us understand the overall trends in fare amounts for each payment type.

*Distribution of Trip Distance*

We also visualize the distribution of trip distances for both credit card and cash payments. This helps us understand if there is a correlation between trip distance and payment type.

*Preferences of Payment Types*

The proportion of customers paying with cards is significantly higher than those paying with cash, with card payments accounting for 67.5% of all transactions compared to cash payments at 32.5%. This indicates a strong preference among customers for using card payments over cash, potentially due to convenience, security, or incentives offered for card transactions.

*Passenger Count Analysis*

Among card payments, rides with a single passenger (passenger_count = 1) comprise the largest proportion, comprising 40.08% of all card transactions. Similarly, cash payments are predominantly associated with single-passenger rides, making up 20.04% of all cash transactions.

*Hypothesis Testing*

Null Hypothesis: There is no difference in average fare between customers who use credit cards and customers who use cash.

Alternate Hypothesis: There is a difference in average fare between customers who use credit cards and customers who use cash.

*Results*

The T-test results show a significant difference in average fare between customers who use credit cards and customers who use cash. The T-statistic value is 169.2 and the P-value is less than 0.05. This means we reject the null hypothesis and accept the alternative hypothesis.

*Recommendations*

1. Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi cab drivers.
2. Implement strategies such as offering incentives or discounts for credit card transactions to incentivize customers to choose this payment method.
3. Provide seamless and secure credit card payment options to enhance customer convenience and encourage the adoption of this preferred payment method.
