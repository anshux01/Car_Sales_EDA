# Business and Statistical Insights

## Summary of Data Quality

- Duplicate rows removed, ensuring clean data integrity.
- Missing values in Price, Units Sold, Customer Rating, and Fuel Type managed via group-wise median imputation and introduction of "Unknown" category for missing Fuel Type.

## Descriptive Statistics

- Average Price ~ ₹4.1M, median close to mean, indicating mild skew.
- Units Sold average ~258 units; median 274, mode 302.
- Customer Ratings mostly between 3 and 5; mode at 4.4.
- Most common brand identified as BMW; ModelF is the top-selling model.

## Sales Trends

- Sales exhibit cyclical behavior with peaks around 2015 and 2022.
- Yearly fluctuations suggest external market or product launch impacts.

## Brand & Segment Analysis

- Mahindra leads total units sold, followed by BMW, Toyota, Hyundai.
- Sales spread across various cities reflecting geographic diversity.
- Premium brands had substantial but variable sales shares.

## Correlation Findings

- Minimal linear correlation between Price, Units Sold, Customer Rating, and Year.
- Implies need for complex modeling strategies using categorical interactions and non-linear approaches.

## Recommendations

- Leverage detailed brand and city-level sales trends for stocking and promotional decisions.
- Monitor customer ratings and tie in marketing or quality initiatives.
- Use findings to enrich dashboard metrics for real-time monitoring.
