# A/B Testing Analysis

## Project Overview

The goal of this project was to analyze the results of four A/B tests and understand how changes affected user behavior and conversion rates.

## Tools & Technologies

- SQL (Google BigQuery)
- Python
- Pandas
- NumPy
- Matplotlib
- Statistical methods (Z-test)
- Tableau

## Project Tasks

- Collected and prepared data using SQL and Python.
- Calculated four conversion metrics:
  - `add_payment_info / session`
  - `add_shipping_info / session`
  - `begin_checkout / session`
  - `new_accounts / session`
- Compared Control and Test groups using the Z-test.
- Analyzed results by device, continent, and traffic channel.
- Prepared the results for visualization in Tableau.

## Key Results

- Test 1 showed a statistically significant increase in `add_shipping_info` and `begin_checkout` conversion rates.
- Test 4 showed a statistically significant decrease in the `new_accounts` conversion rate.
- No statistically significant changes were found for the other metrics at the overall level.

## Tableau Dashboard

[View the interactive A/B Testing Dashboard](https://public.tableau.com/app/profile/.32455230/viz/PortfolioProject2_17940407236070/ABtest)

## Conclusion

The project helped identify positive and negative results of the A/B tests. It also showed the importance of statistical testing when making data-driven product decisions.
