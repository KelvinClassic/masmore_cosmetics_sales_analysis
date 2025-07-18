# Mas-More Ventures Cosmetics Sales Data Analysis and Visualization
Mas More Ventures is a cosmetic company operating in Nigeria with dedicated team of 25 staff members, the company specialize in producing and distributing a wide range of cosmetic products, including skincare, makeup and frangrance. Mas-More has a reputation for offering high-quality, locally-sourced products that cater to the diverse beauty needs of its customers. The company operates three branches strategically located in different regions of Nigeria, serving as hubs for product distribution and customer engagement.

In just 2 years in business, Mas_more Ventures has continually expanded its product range to meet the evolving beauty needs of its customers. The company invests in research and development to stay at the forefront of cosmetic innovation. This commitment has allowed Mas-More to offere a diverse portfolio that includes skincare items like eyeshadow, as well as array of frangrances and fashion accessories.

### Problem Statement
Mas-More Ventures faces a significant business challenges in effectively monitoring and optimizing its sales performance across its branches. The key obstacles the company encounters include:
    - Data Fragmentation: Sales data is collected manually across the two branches, leading to fragmentated, error-prone records.

    - Limited Data Analysis: The lack of data analysis tools hinders the company's ability to gain insights into product performance, customer preferences, and regional trends.

    - Resources Allocation: MAS-MORE Ventures Cosmetics struggles to allocate resources efficiently, leading to stockouts or overstock situations.

### Project Objectives
The project aims to achieve the following specific objectives:
- Develop a centralized data repository for sales data from all three branches, ensuring data consistency and accuracy.
- Implement basic data analysis techniques to gain insights into sales trends, product performance, and customer preferences.
- Create user-friendly dashboards for easy access to sales data and insights.
- Carry out basic data analysis, and dashboard utilization to enhance decision-making capabilities.

### Tech Stark
- Microsoft Excel (built in features)
    - pivot tables 
    - charts

### Data Analysis Scope
- Data Gathering. 
- Data analysis (in MS Excel).
- Dashboard Development (in MS Excel).

Visit the [data description page](data_description.md) to get detailed information about the data used in this project.

### Procedures
- Data Transformation
    - Load all three dataset into a single excel workspace 
    - Combine all three dataset in a single sheet (Data -> New Query -> Combine Queries -> Append -> Add the datasets)
    - Ensure all monetary columns are in Currency format (to 2 decimal places) in Nigeria Naira (NGN)
- Data Analysis
    - Add 'Profit per product' column (Revenue * ProfitMargin)
    - Calculate the following:
        - Total revenue.
        - Total cost.
        - Total profit.
        - Average age.
        - Total sold.
        - Average Purchace frequency.
    - Add 'Age Range' column (18-27, 28-38, 39-48, 49-59, 60 and Above)
    - Create pivot tables and charts to display the following in a new sheet (Pivot Table):
        - Sum of Revenue by Year.
        - Sum of Revenue by Month.
        - Total Revenue by product Category.
        - Total Revnue by Product name.
        - Total Revenue and Purchase Frequency by Gender.
        - Total Quantity Sold by Product Category.
        - Total Quantity Sold by Location.
        - Total Product Sold by Location and by Product Category.
        - Marketing Strategy Vs Revenue by Branch.
    - Create dashboard in a new sheet to display these insights.

### Insights and Recommendations
Follow the [Insight and recommendation link](insights_and_recommendations.md) for information regarding this section.


