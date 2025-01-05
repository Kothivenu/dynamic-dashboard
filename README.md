# Dynamic Retail Dashboard

## Objective

The primary objective of the **Dynamic Retail Dashboard** is to provide a comprehensive, interactive tool for analyzing retail data, uncovering key insights, and making informed business decisions. The dashboard is designed to integrate various datasets, visualize KPIs (Key Performance Indicators), and offer a user-friendly interface for tracking performance across multiple dimensions such as sales, profit, discounts, and orders.

## Significance

1. **Data-Driven Decision Making**: By consolidating and analyzing data from multiple sources, the dashboard enables stakeholders to make informed decisions.
2. **Real-Time Insights**: Dynamic features allow real-time monitoring of retail operations, enabling businesses to respond quickly to changes.
3. **Improved Efficiency**: Automating data visualization and analysis reduces manual effort and improves operational efficiency.
4. **Enhanced Understanding of Trends**: The dashboard helps in identifying trends and patterns in sales, returns, and customer behavior.

## Datasets Used

1. **Order Table**:

   - **Columns**: Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, City, State, Country, Postal Code, Market, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost, Order Priority.
   - **Purpose**: Tracks all orders placed, including customer details, product information, and sales metrics.

2. **People Table**:

   - **Columns**: Person, Region.
   - **Purpose**: Maps individuals to specific regions, enabling regional performance analysis.

3. **Return Table**:

   - **Columns**: Returned, Order ID, Market.
   - **Purpose**: Captures data about returned orders for understanding customer dissatisfaction and product issues.

4. **KPI Table**:

   - **Columns**: Names, Metrics, Symbols.
   - **Purpose**: Defines the key performance indicators (KPIs) for the dashboard and associates them with meaningful metrics and symbols for visualization.

## KPIs Defined

| **Name**       | **Metric**              | **Symbol** |
| -------------- | ----------------------- | ---------- |
| Order ID       | Count of Order ID       | 💰         |
| Profit         | Sum of Profit           | 📈         |
| Product ID     | Count of Product ID     | 🔘         |
| Sales          | Sum of Sales            | 💬         |
| Discount       | Sum of Discount         | 📉         |
| Quantity       | Sum of Quantity         | 🔍         |
| Order Priority | Count of Order Priority | 💩         |

problem statements:

Charts showing Segment, Categoty and Markets Analysis	
![image](https://github.com/user-attachments/assets/199e44ed-38da-459d-ad5c-91b9c766a266)

Top 5 and bottom 5 charts for Sales, Profits, Order Quantity
![image](https://github.com/user-attachments/assets/81297397-f25c-4701-928c-5ad460641407)

World map showing the top 10 countries by Sales	
![image](https://github.com/user-attachments/assets/c24e8ae8-3af1-4f7a-b5d9-6877b00fd22d)

Top Sub-Category and their contribution to the overall Sales
![image](https://github.com/user-attachments/assets/6dcc769b-8fd5-4d0b-812f-0551f0ed6c05)

Charts showing the Market Share of Regions
![image](https://github.com/user-attachments/assets/957e1b5d-6637-4e32-b02d-7d1ed147a3d2)



## Steps to Create the Dashboard

### 1. Data Preparation

- Consolidate data from the Order, Return, and People tables.
- Ensure data integrity by removing duplicates and handling missing values.
- Establish relationships between tables based on common keys like `Order ID` and `Region`.

### 2. Designing KPIs

- Define KPIs using the KPI table, ensuring alignment with business goals.
- Assign meaningful symbols to KPIs for enhanced visualization.

### 3. Data Visualization

- Use a tool like Power BI, Tableau, or Excel to create dynamic visualizations.
- Create charts for each KPI, such as:
  - **Bar Charts**: For sales and profit comparisons.
  - **Pie Charts**: For order priorities or market shares.
  - **Line Graphs**: For analyzing profit trends over time.

### 4. Integration of Filters and Interactivity

- Add filters for dimensions like Region, Segment, Category, and Market.
- Enable interactivity to allow users to drill down into specific data points.

### 5. Testing and Validation

- Test the dashboard for accuracy and ensure it meets business requirements.
- Validate the insights generated with stakeholders to confirm usability.

### 6. Deployment

- Publish the dashboard to a platform like Power BI Service or Tableau Server.
- Share access with relevant stakeholders.

## Conclusion

The **Dynamic Retail Dashboard** serves as a powerful tool for retail data analysis. By integrating multiple datasets and visualizing key metrics, it empowers businesses to understand their performance comprehensively. The dynamic and interactive nature of the dashboard allows for flexible exploration of data, ensuring that insights are actionable and relevant. This project highlights the importance of combining robust data preparation, meaningful KPIs, and intuitive visualizations to create impactful analytical tools.


![image](https://github.com/user-attachments/assets/85f044f4-c553-4211-b2f9-9f6b2db7f091)
