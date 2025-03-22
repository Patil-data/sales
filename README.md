# Sales Data Prediction

## Background
Sales forecasting is crucial for businesses to optimize inventory, manage resources, and improve profitability. By leveraging data analytics and machine learning, companies can predict future sales trends based on historical data.

This project applies SQL and data analytics techniques to analyze historical sales data and build predictive models for future sales performance.

### Accomplishes Three Main Tasks:
1. **Data Modeling:** Define a structured database to store sales transactions and customer data.
2. **Data Engineering:** Create a PostgreSQL database schema and populate it with historical sales data.
3. **Data Analysis & Prediction:** Use SQL and machine learning models to analyze sales patterns and forecast future sales.

## Files
### Query Files:
- `schema.sql`
- `seed.sql`

### CSV Files:
- `sales_data.csv`
- `customers.csv`
- `products.csv`
- `transactions.csv`

## Data Modeling
- Designed an **Entity Relationship Diagram (ERD)** to structure the sales database.
- Defined relationships between customers, transactions, and products.
- Used **Quick Database Diagrams** to create the database schema.

## Data Engineering
- Developed a PostgreSQL schema with appropriate data types, primary keys, and foreign keys.
- Imported sales data from CSV files into the database.

## Data Analysis & Prediction
With the structured sales database, SQL queries and machine learning models were used to analyze past sales trends and predict future performance.

### Key Analyses:
1. **Top 100 Highest Sales Transactions:**
   - Identified high-value transactions to analyze customer spending habits.

2. **Seasonal Sales Trends:**
   - Examined sales performance over time to detect seasonal demand fluctuations.
   - Used time-series analysis techniques to forecast future sales.

3. **Customer Purchasing Behavior:**
   - Segmented customers based on their spending patterns and purchase frequency.
   - Identified top customers contributing to revenue growth.

4. **Product Performance Analysis:**
   - Evaluated which products generate the most revenue.
   - Recommended inventory optimization strategies based on sales performance.

5. **Predicting Future Sales:**
   - Applied machine learning models (e.g., **Linear Regression, Random Forest, ARIMA**) to forecast future sales trends.
   - Evaluated model accuracy using performance metrics.

## Sales Forecasting Challenge
### Methods Used for Prediction:
1. **Time Series Analysis:**
   - Used historical data to identify trends and seasonality in sales.
2. **Regression Models:**
   - Built predictive models to estimate future sales based on past performance.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Patil-data/sales.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sales
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Set up your PostgreSQL database using `schema.sql` and import data using `seed.sql`.
2. Run SQL queries to analyze sales trends.
3. Use Python scripts to train machine learning models and generate sales forecasts.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.


