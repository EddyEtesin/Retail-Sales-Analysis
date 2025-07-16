
# Retail Data Analysis Using Python and Pandas

This project explores a retail dataset to uncover patterns in customer behavior and product performance. Using Python and the Pandas library, the analysis answers key business questions and provides actionable insights for retail decision-making.

## Dataset Overview

The dataset contains transactional records from a retail business with the following fields:

* **Transaction ID**: Unique identifier for each transaction
* **Date**: Date of purchase
* **Customer ID**: Unique identifier for each customer
* **Gender**: Customer gender
* **Age**: Customer age
* **Product Category**: Category of purchased product
* **Quantity**: Number of items purchased per transaction
* **Price per Unit**: Unit price of each product
* **Total Amount**: Total value of the transaction

## Objectives

The analysis focuses on deriving insights to answer the following business questions:

1. How do customer age and gender influence purchasing behavior?
2. Are there discernible patterns in sales across different time periods?
3. Which product categories hold the highest appeal among customers?
4. What are the relationships between age, spending, and product preferences?
5. How do customers adapt their shopping habits during seasonal trends?
6. Are there distinct purchasing behaviors based on items bought per transaction?
7. What insights can be gleaned from the distribution of product prices within each category?

## Key Insights

### Customer Age and Gender Influence

* Women spend slightly more per transaction (\$456.55) than men (\$455.43).
* Customers aged 15–24 represent the most profitable demographic with the highest total spending.

**Recommendations:**

* Focus marketing on younger customers (15–24).
* Design campaigns targeting female customers who slightly outspend their male counterparts.

### Sales Patterns Across Time

* May 2023 recorded the highest sales (\$53,150), followed by October and December.
* Saturdays drive the highest average sales (\$525.43).

**Recommendations:**

* Boost inventory and staffing on Saturdays to meet demand.
* Implement promotions on slower days (Wednesdays and Sundays) to increase sales.

### Product Category Preferences

* Clothing, Electronics, and Beauty are the most popular categories.
* Beauty products show higher engagement from female customers.
* Clothing and Electronics have balanced popularity across genders.

**Recommendations:**

* Target Beauty product marketing toward female customers.
* Use gender-neutral strategies for Clothing and Electronics.

### Age, Spending, and Product Relationships

* Younger customers (15–24) prefer Beauty products.
* Middle-aged customers (25–44) prefer Clothing.
* Older customers (45–54) spend more on Electronics.
* Weak negative correlation (-0.0605) between age and transaction amount.

**Recommendations:**

* Target Beauty promotions to younger demographics.
* Offer loyalty programs for Clothing and Electronics tailored to age groups.

### Seasonal Shopping Trends

* Sales peak in May, October, and December, driven by holidays and seasonal events.
* September shows the lowest sales and average spend.

**Recommendations:**

* Implement targeted promotions to counteract the September slump.
* Focus Electronics campaigns during year-end holidays.

### Basket Size and Purchasing Behavior

* Medium baskets (3–4 items) generate higher revenue.
* Few transactions involve large baskets.

**Recommendations:**

* Encourage upselling and cross-selling to grow basket size.
* Offer bundle discounts to incentivize larger purchases.

### Product Pricing Insights

* 50% of products are priced at \$50 or below.
* Premium products (\$300–\$500) exist in all categories but represent a smaller share.

**Recommendations:**

* Bundle low-priced items to increase overall basket size.
* Target premium product marketing to customers with higher average spend.

## Tools and Libraries

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**


## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/EddyEtesin/Retail-Sales-Analysis.git
   cd Retail-Sales-Analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to reproduce the analysis.

## Author

**Ediomo Etesin**
*Data Analyst | Python | SQL | Pandas | Data Visualization*
[GitHub](https://github.com/Edyetesin) | [LinkedIn](https://www.linkedin.com/in/ediomo-etesin)

