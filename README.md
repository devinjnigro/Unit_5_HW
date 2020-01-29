# Unit_5_HW
Unit 5: API Homework
# Financial Report
## Budget Analysis
The client's expense and income data were imported and compiled from a Plaid API in order to produce a sample transaction history starting on 10/31/2019 and ending on 1/29/2020, as seen below.

![](images/expense_chart.png)

The transactions were grouped into categories to demonstrate spending per type of transaction as well as the number of transactions per category.

![](images/spending_per_cat.png)

![](images/trans_per_cat.png)

The client's income data was extracted from Plaid in order to determine the gross annual income for 2019, projected income for 2020, and current monthly income.

![](images/income_data.png)

Finally, the expense data was grouped by month to determine monthly expenditures.

![](images/monthly_expenses.png)

![](images/monthly_expenses_bar.png)

Based on the current projected annual income of $7,389, the average monthly expense of $10,645.24 far exceeds the recommended budget for this particular client.

## Retirement Planning

Closing prices for the SPDR S&P 500 ETF Trust (SPY) and iShares Barclays Aggregate Bond Fund (AGG) were imported using the IEX Finance API in order to generate the daily return on investment for the previous year's worth of data.

![](images/historical_data.png)

![](images/daily_roi.png)

Based on the previous year's returns, a Monte Carlo simulation was used to calculate 500 randomized simulated cumululative returns over the next 30 years of a portfolio consisting of SPY and AGG given a 60/40 stock bond allocation.

![](images/monte_carlo.png)

![](images/monte_carlo_plot.png)

![](images/cum_confidence_returns.png)

The cumulative return performing at the 50th percentile is found to be 12,608.22%. The 10th percentile return is projected at 7,295.51%, and the 90th percentile return at 20,830.95%. Given an initial investment of $20,000, the cumulative returns were calculated to be the following:

10th Percentile: $1,459,102.00\
50th Percentile: $2,521,644.98\
90th Percentile: $4,166,190.19

Assuming the initial $20,000 investment and a 4% annual withdrawal rate from the 10th percentile portfolio upon retirement, the annual retirement income would be $58,364.08, which far exceeds the client's projected annual income of $7,389.
