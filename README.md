# Business-Intelligence-Solution-for-Sales-Process-of-AdventureWorks

**I. Scope and objective of the project**

1. Scope of the project:
   
The scope of the project is the application of BI solutions to analyze the dataset of AdventureWorks company. It involves approaching and studying datasets not only related to the Sales department but also related to customers, product categories, and promotional programs.

2. Objective of the project:

- Clarify the role of BI in business, focusing on the sales process: Investigate and specify the specific contributions and application processes of Business Intelligence (BI) in understanding various aspects of business operations, emphasizing their impact on the sales process. Explore how factors such as demographics, cash flow, etc., influence sales performance.
- Design and deploy a data warehouse: Design and construct a Data Warehouse using Microsoft's SQL Server solution to support data analysis and querying.
- Enhance business performance evaluation methods, and identify metrics to provide a comprehensive understanding of AdventureWorks' operational efficiency.
- Visualization through Dashboards: Research and implement dashboard design to create reports that offer clear insights into business issues.
By achieving these project objectives, the aim is to seamlessly integrate database activities with the business processes at AdventureWorks, harnessing the power of BI solutions to improve decision-making capabilities, enhance efficiency, and promote business growth.
  
**II. Requirement of problems**

![image](https://github.com/tuuyen13/Business-Intelligence-Solution-for-Sales-Process-of-AdventureWorks/assets/94332486/94f5a1c1-e925-4ca9-9e9a-dbc8fd312cda)

**III. DataWarehouse**
1. Data source:
   
The AdventureWorks Data Warehouse 2019 <a href="https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms">AdventureWorksDW2019.bak</a> comprises a total of 30 Fact and Dimension tables. 

3. Design data warehouse:
   
The objective of project is to implement BI Solution for the Sales Process of AdventureWorks, therefore selecting relevant tables related to sales performance from the data source to design the AdventureWorksSales data warehouse.

| Table                  | Description                                                   |
|------------------------|---------------------------------------------------------------|
| DimCustomer            | Table detailing customer information.                          |
| DimDate                | Contains information about dates in the past and future.       |
| DimGeography           | Table containing geographical information.                    |
| DimProduct             | Table containing detailed information about products.         |
| DimProductCategory     | Contains information about product categories.                 |
| DimProductSubcategory  | Sub-table of DimProductCategory, providing more detailed information about product categories. |
| DimPromotion           | Stores information about promotional programs.                |
| FactInternetSales      | Table containing information about online sales figures.      |

4. Data Warehouse model 
  
![image](https://github.com/tuuyen13/Business-Intelligence-Solution-for-Sales-Process-of-AdventureWorks/assets/94332486/76321528-8e01-4e25-bb25-37a570240fd7)


 **IV. Experimental results and analysis**
 1. Report and dashboard system
![image](https://github.com/tuuyen13/Business-Intelligence-Solution-for-Sales-Process-of-AdventureWorks/assets/94332486/8aa60837-7cf0-4b76-b7cb-244675214701)

2. Recommendation
- Boost the sales of high-demand items during growth periods while optimizing costs to ensure profitability increases
- Improve and adapt the frequency, intensity, and timing of promotional programs.
- Consider allocating more resources, marketing efforts, and product development towards the United States and Australia
- Implement cross-selling for Clothing, focus on Accessories for high volume and profit, and intensify promotion efforts for Bikes.
- Customer long-term relationship building, focus on CRM topic (targeting Professional, Management, and Clerical customer group).


