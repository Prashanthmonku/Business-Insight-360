## Project Overview

AtliQ Hardwares is a company specializing in consumer electronics and hardware products, selling through various channels including brick-and-mortar stores like Croma and Best Buy, online platforms such as Amazon and Flipkart, and through direct sales and distributors. Despite its rapid expansion, AtliQ faces challenges in competing with data-driven companies as most of its reports are still in Excel. My objective is to introduce an advanced analytics solution using Power BI, empowering AtliQ to gain actionable insights and enhance decision-making capabilities.

### Project Goal

The goal of this project is to create a unified report that caters to stakeholders from sales, marketing, finance, and the executive team. The focus is on:

- Robust Data Modeling: Ensure data accuracy and analysis ease.
- User-Empathetic Design: Cater to each stakeholder group's needs.
- Drillable Insights: Allow for deep dives into granular data.
- Benefits: Empower decision-making across all levels.

#### Dashboard Overview

- **Finance:** Analyze profitability and track sales performance through P&L and sales trends.

  **<img width="578" alt="Finance View" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/1c5195ba-de1c-48ae-95b6-16d93dc0cbca">**

- **Sales:** Identify customer buying patterns and optimize product offerings through in-depth metrics.

  **<img width="577" alt="Sales View" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/247cef27-eeb7-4075-9988-54e202bfdad7">**

- **Marketing:** Develop targeted marketing campaigns based on data-driven insights from market research and customer analysis.

  **<img width="574" alt="Market View" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/708f7bc4-3431-43a8-a8d9-ee7b12b25bfb">**

- **Supply Chain:** Improve forecast accuracy and optimize logistics for efficient inventory management.

  **<img width="581" alt="Supply Chain View" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/4295de9e-c03e-4fa9-8090-88bced96c7c1">**

- **Executive:** Gain a holistic view of business performance with key metrics and KPIs for strategic decision-making.

  **<img width="579" alt="Exective View" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/69e04d42-e853-4f2e-a127-3ca34283437b">**

### Business Related Terms

- **Gross price**
- **Pre-invoice deductions**
- **Post-Invoice deductions**
- **Net Invoice sale**
- **Gross Margin**
- **Net sales**
- **Net profit**
- **COGC - cost of goods sold**
- **YTD - Year to Date**
- **YTG - Year to Go**
- **Direct**
- **Retailer**
- **Distributors**
- **Consumer**

### Exploring the Dataset: Understanding Available Data

Analyze before you dive! Exploring the data first helps identify available dimensions (static data like customer details) and facts (transactional data like sales figures). This ensures analysis uses the most relevant information.

**gdb041:**

**dim_customer**
- 27 distinct markets (e.g., India, USA, Spain)
- 75 distinct customers throughout the market
- 2 types of platforms
  - Brick & Motors: Physical/offline store
  - E-commerce: Online Store (Amazon, Flipkart)
- Three channels
  - Retailer
  - Direct
  - Distributors

**dim_market**
- 27 distinct markets (e.g., India, USA, Spain)
- 7 sub-zones
- 4 regions
  - APAC
  - EU
  - NAN
  - LATAM

**dim_product**
- Divisions:
  - P & A (Peripherals & Accessories)
  - PC (Personal Computer)
  - Notebook
  - Desktop
  - N & S (Networking & Storage)
- 14 different categories (e.g., Internal HDD, keyboard)
- Different variants available for the same product

**fact_forecast_monthly**
- Used to forecast customer needs in advance
- Benefits:
  - Higher customer satisfaction
  - Reduced storage costs in warehouses
- Data denormalized for analytical work
- Date of the month replaced by start date of the month
- Includes forecast quantity needed by customers

**fact_sales_monthly**
- Similar to fact_forecast_monthly but with actual sold quantity instead of forecasted value

**gdb056:**

**freight_cost**
- Details of travel and other costs for each market with fiscal year

**gross_price**
- Details of gross prices with product code

**manufacturing_cost**
- Details of manufacturing costs with product code and year

**Pre_invoice_deductions**
- Details of pre-invoice deductions percentage for each customer with year

**Post_invoice_deductions**
- Details of post-invoice and other deductions

### Data Modeling

**<img width="720" alt="Data Modelling" src="https://github.com/Prashanthmonku/Business-Insight-360/assets/66664885/0f4149b1-fabb-405a-8384-0fab29c97a56">**

Data modeling is crucial and forms the foundation of a report. All visuals are built upon the data model, making it a critical component for accurate insights. Poor data modeling can significantly impact the overall performance of the report.

Adhering to best practices in data modeling is essential for optimal performance.

please find the live Dashboard link [here](https://app.powerbi.com/view?r=eyJrIjoiMGNmYjhlYmYtZTNhOC00MTUxLTlkZTEtNjMwNDU3MmExNDIyIiwidCI6IjFhNjI4ZjEzLTEyYTUtNGI0OS05YWRjLTY5NGFkNzI2ZmU1MyJ9)

### Tech Skills Acquired:

- SQL
- PowerBI Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

### Key Learnings:

- **Power Query:** Data cleaning and transformation through an intuitive graphical interface.
- **Data Modeling:** Established relationships between tables and creating tables, calculated columns, measures using DAX.
- **DAX (Data Analysis Expressions):** Writing and using DAX formulas for calculations and aggregations.
- **Visualization Tools:** Created interactive charts, graphs, and KPI indicators for effective data presentation. Utilized Bookmarks to switch between visuals and navigated pages using buttons.
- **Choosing Visuals and Formatting:** Learned to choose the right visuals and formatting techniques for impactful data presentation.
- **Power BI Service:** Gained proficiency in publishing, sharing, and collaborating on reports and dashboards through the cloud-based Power BI service.
- **Integration with Microsoft Tools:** Explored how Power BI integrates seamlessly with other Microsoft tools like Excel, SharePoint, Teams, and Azure.

