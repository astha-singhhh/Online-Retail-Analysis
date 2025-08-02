Dataset
- Source: UCI Machine Learning Repository - Online Retail Dataset
- Time Period: 2011 transactions
- Sample Size: 19,794 transactions after preprocessing
- Countries: United Kingdom, Germany, France, Ireland (EIRE), Belgium, and Spain
- Note: UK dominates the dataset with 18,285 transactions (92.4% of total)

Original Variables
- InvoiceNo: Transaction identifier
- StockCode: Product code
- Description: Product description
- Quantity: Number of items purchased
- InvoiceDate: Transaction date and time
- UnitPrice: Price per unit
- CustomerID: Customer identifier
- Country: Country of customer

Derived Variables
- TotalQuantity: Sum of items purchased per transaction
- TotalSpend: Total value of each transaction (Quantity × UnitPrice)
- UniqueItems: Number of distinct products in each transaction
- IsWeekend: Whether the transaction occurred on a weekend
- IsHighValue: Whether the transaction value is above the mean

Statistical Methods Used
- Two-Sample t-Tests with Welch's Adjustment (unequal variances)
- Chi-Square Goodness of Fit tests for proportion comparisons
- ANOVA with Welch's Adjustment for multi-group comparisons
- Multiple Linear Regression with stepwise model selection
- Pairwise t-tests with Holm adjustment for multiple comparisons
