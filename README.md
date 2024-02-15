# AdventureWorks Sales Performance Report
This project was under taken at the end of my Excel learning journey. Some unused data has been removed from the original dataset. The aim of the project is to create a dashboard delivering analytical insights about AdventureWorks' monthly sales trend and evaluate sales performance in 2002 and 2003. 

## Datasource description
The Excel file includes 4 worksheets:  
- ***AdventureWorks.SalesOrderHeader***: contains 31465 records for all orders' information, including order IDs, online order flags, order dates, shipping dates, customer IDs, salesperson IDs, territory IDs, order values, and sales reasons. Note: there are some blank rows for sales reasons because only sales reasons for online orders are recorded
- ***AdventureWorks.SalesTerritory***: contains information about the sales regions (continents, countries, countries' regions)
- ***AdventureWorks.Employee***: contains information of all employees of AdventureWorks, including employee IDs, employees' manager IDs, and their demographic information
- ***AdventureWorks.SalesReason***: contains reason IDs, reason names and categorized reason types

## Steps taken when working with the datasource
- **Data preparation**: created an Orders table to gather all information needed to create the dashboard, utlized multiple IFs and VLOOKUP functions to gather data from different worksheets
<img width="919" alt="Screenshot 2024-02-15 123100" src="https://github.com/ericbui273/Excel-Projects/assets/147421713/a0857c3d-b94f-4be2-847d-dd522a5e23d5">


- **Creating pivot tables**: to break down the data by relevant dimensions, such as monthly sales and order count, order count by sales reasons, top best salespeople by sales volume, etc., with the aim of efficiently summarizing and analyzing the large dataset

<img width="432" alt="Screenshot 2024-02-15 124053" src="https://github.com/ericbui273/Excel-Projects/assets/147421713/c6addc4f-4394-444d-8740-8af43de381e3"> <img width="328" alt="Screenshot 2024-02-15 124121" src="https://github.com/ericbui273/Excel-Projects/assets/147421713/b6ad4362-3d54-44f1-b357-c349d520141b">  

- **Creating pivot charts**: effectively visualized the insights from pivot tables by various types of pivot charts

![image](https://github.com/ericbui273/Excel-Projects/assets/147421713/36d956d2-2273-4eef-982c-005b2f388258) ![image](https://github.com/ericbui273/Excel-Projects/assets/147421713/10e31f93-942c-4576-b328-67ea20ed57e9) ![image](https://github.com/ericbui273/Excel-Projects/assets/147421713/11046d00-d3c8-428a-bfae-402626aa4a18)  

- **Finalizing dashboard**: gathered all of the charts to create an interactive dashboard with timeline and slicers to filter data

<img width="661" alt="image" src="https://github.com/ericbui273/Excel-Projects/assets/147421713/4d83912c-507e-4f4b-9b21-ca66ef505021">






 
