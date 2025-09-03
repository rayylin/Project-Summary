# Project-Summary
This is the table of contents of all projects
1. Demand Forecasting Example- Service Parts in the Eletric Vehicle Industry(Python (Random Forest), MySQL, html)
2. ABC-XYZ Analysis for Inventory Management (Python)
3. Data Pipeline for Maintenance Management (Alterxy, SQL Server)
4. SAP Demand Forecasting (SAP)
5. Inventory Management System (C#, .Net, SQL Server)
6. Sales Performance Tracking Dashboard (Power BI)
7. Store Items Analytics and Demand Forecast (Python)
8. Sales Performance Analysis (Tableau)
9. Material Planning (Python)
10. Route Optimization & Warehouse Picking Operations Optimization (Python)
11. Firm Collapse Prediction (SAS EM)
12. Survival Analysis (R)
13. Churn Rate Analysis (Power BI)
14. Distribution Center Optimization (Python)
15. Shipment/Transportation Tracking Dashboard (Power BI)
16. Route Optimization with A*, Dijkstra, and BFS (Python)
17. Factory Production Planning Optimization (Python-Gurobi)
18. Discrete event simulation of a factory (Python-SimPy)
19. PO Management System (MS Access)
20. Production Monitoring Dashboard (MS SQL Server, Power BI)
21. Digital Marketing Performance Dashboard
22. AB Test for different website layouts
23. Online Shopping Website with Basket Analysis


# Demand Forecasting Example- Service Parts in the Eletric Vehicle Industry
|Tools Used|Project Description|
|---|---|
|Python, MySQL|Good demand forecasting could help businesses manage their inventory levels, arrange production schedules, improve ordering patterns of raw materials, and maintain healthier cash flow. I will use Time Series, XGBoost, and Lasso to forecast the demand for service parts in the Electric Vehicle Industry. Also, I will demonstrate how to perform location pooling for some expensive, rare-used parts. The risk pooling approach can put several supply-chain flows into one flow, thereby reducing demand variability. Furthermore, I will discuss how to improve forecasting accuracy and perform demand forecasting when you have no historical data; in other words, how to handle supersession or NPI projects.|

![image](https://user-images.githubusercontent.com/58899897/204398052-3ea0f4df-c4fe-4a88-866b-b311f682ee00.png)

![image](https://user-images.githubusercontent.com/58899897/204398099-9373e336-facf-4cad-a585-80676d1c7511.png)

![image](https://user-images.githubusercontent.com/58899897/204398453-dae67421-e60a-49fd-bfcd-f561fb6f96dd.png)

![image](https://user-images.githubusercontent.com/58899897/204398649-26a3b5a4-51b6-4aff-94ca-29c72712324c.png)

more details: https://github.com/rayylin/Demand-Forecasting-Example--Service-Parts-in-the-Eletric-Vehicle-Industry

# ABC-XYZ Analysis for Inventory Management
|Tools Used|Project Description|
|---|---|
|Python|The ABC-XYZ analysis can help people better manage products and optimize inventory levels. It considers the demand uncertainty of products, thereby defining different safety stock levels. With ABC-XYZ analysis, we can tailor our inventory policies. For example, we can afford to hold less safety stock of AX products than AZ products. In this project, we categorize products based on their Revenue and coefficient of variation. The top 20% of products are categorized as A, and the top 21% to 50% are categorized as B. For the coefficient of variation, we use the historical data of the past two years and apply the formula: standard deviation/mean.|

![image](https://user-images.githubusercontent.com/58899897/202921664-ce723633-ddf1-45b6-a102-f6aeaa0dbaba.png)

The color represents how many products are categorized as each type. For example, 89 products are categorized as CZ type.


# Data Pipeline for Maintenance Management
|Tools Used|Project Description|
|---|---|
|Alterxy, SQL Server|Vehicles consist of hundreds or even thousands of parts, and each may have a specific duration. It would be very time-consuming to manage the maintenance plan manually. A data pipeline could help up perform this task. In this project, I applied Alteryx to automate the process. The model extracts data from CSV files and SQL Server database and calculates how many vehicles need to be maintained. We can also compute how many vehicles need maintenance during the incoming months. The model could automatically execute itself every month to update the critical information.|

![image](https://user-images.githubusercontent.com/58899897/204888634-f44cbe76-ed4a-4e73-bb44-5037ce8f463e.png)
![image](https://user-images.githubusercontent.com/58899897/204888719-c1b19fc5-bc32-4db8-a887-56394e43f8d4.png)
![image](https://user-images.githubusercontent.com/58899897/204888811-fa578ad6-a412-4ae0-9fb1-69f4f77682e3.png)



# SAP Demand Forecasting
|Tools Used|Project Description|
|---|---|
|SAP|This project performs a demand forecast of an electronic part. Demand forecasting is an important issue that could help businesses better allocate resources and arrange their production schedule. We have the sales data for the past two years. The product is sold in 235 locations and has 223,769 transactions. We focus on the US only. The raw data includes six columns, Location, Code, Year, Day, Sales, and Continent. We use SAP to perform demand forecasting with the Time Series model. We use Mean absolute percentage error (MAPE) to evaluate the performance. The MAPE value is 3.46%
|

![image](https://user-images.githubusercontent.com/58899897/200234400-d77d2264-67ff-44bf-beef-3fe9d467d362.png)

![image](https://user-images.githubusercontent.com/58899897/200227843-9af02e93-e0cb-49fd-b6cc-fb840aaf5352.png)

# Inventory Management System
|Tools Used|Project Description|
|---|---|
|C#, .Net, SQL Server|An Inventory Management System can help companies manage their orders, inventory, and customers. In this project, we use C# and .net to write an inventory management system. The system uses SQL Server as its database.|

![image](https://user-images.githubusercontent.com/58899897/206274891-624b3764-9931-498b-816e-f39dae54e39e.png)
![image](https://user-images.githubusercontent.com/58899897/206275935-e02e52d3-7b1d-4a67-9fa2-9c67fc0ad09c.png)
![image](https://user-images.githubusercontent.com/58899897/206276458-4de93bd0-5a64-4740-bf79-63b9a766fe9c.png)




# Sales Performance Tracking Dashboard
|Tools Used|Project Description|
|---|---|
|Power BI for Data Visualization and Performance Tracking|In this project, I build a dashboard to track and analyze KPIs and visualize information across the organization to improve decision-making processes. I have the actual sales and expected sales for salespersons, transaction data, and store data. I visualize the data with a Power BI dashboard. It can help us identify trends or components impacting a company's sales operations. The dashboard is interactive, and we could drill down the data to a more detailed and granular view, understanding the impacts of each product, salesperson, and store.|

![image](https://user-images.githubusercontent.com/58899897/198494543-5d30d4c9-e25f-4b71-8a9c-ad74be991add.png)

more details: https://github.com/rayylin/Power-BI_Purchase_order_analysis
# Store Items Analytics and Demand Forecast
|Tools Used|Project Description|
|---|---|
|Python for Time Series Demand Forecast (ARIMA) and Sales Data Analytics|This project is about demand forecast. I have the sales data for the past five years, 930,000 in total. The raw data includes four columns, date, store, item, and quantity. First, I perform an EDA to have a basic understanding of the data. Then we could see the sales performance on different products and stores to help us better manage our inventory. Before applying the ARIMA model, we need to ensure that the data is stationary and use the Augmented Dickey-Fuller test. After the test shows that the sales data is stationary, we could use the Time Series analysis (TSA) of Statsmodels to build a model. To improve the accuracy, I include the holiday data.|

![image](https://user-images.githubusercontent.com/58899897/198486749-7e3cc2ca-32ec-4d7d-8d59-871857bb01ad.png)

![image](https://user-images.githubusercontent.com/58899897/199175506-2f23a0b6-fd2b-4a2b-a21c-5a1bf2a4378e.png)

![image](https://user-images.githubusercontent.com/58899897/198487347-ec0bfc2a-c8d9-43bc-a482-97c97009d031.png)

![image](https://user-images.githubusercontent.com/58899897/198487436-c7324b5d-c15c-4144-ab1e-0e6383c5a3ea.png)

more details: https://github.com/rayylin/Python-Store_Item_Demand_Forecast_with_Time_Series


# Sales Performance Analysis
|Tools Used|Project Description|
|---|---|
|Tableau for sales performance visualization and root cause analysis| <br/>In this project, I build an interactive dashboard to track and analyze KPIs and visualize information. The dashboard uses different plots to show the performance and trends of each product. The dashboard can also help users find abnormalities by drilling down the data to get more information. We find that the increasing costs affect the profit in Italy.|

![image](https://user-images.githubusercontent.com/58899897/198492186-ac4ab495-a73f-464f-89f6-54f7728dce8c.png)


more details: https://github.com/rayylin/Tableau_sales_analysis

# Material Planning
|Tools Used|Project Description|
|---|---|
|Python for Material Planning and Inventory Management|We cooperate with an animal food manufacturer, and they have limited storage space and are trying to maintain minimal inventory on hand. My task is to build a model for them to calculate when they should issue purchase orders. To achieve this goal, I use python to employ the Critical Path Method Algorithm to calculate the slack. The slack is how long we could delay without violating the deadline. We could order the raw materials for processes with slack later but would not delay the production schedule.|

![image](https://user-images.githubusercontent.com/58899897/198397952-f8d7628c-5fba-4472-adde-4bfcfd75fe73.png)

The 'SK' is how long we could delay without violating the deadline

![image](https://user-images.githubusercontent.com/58899897/198398056-53308649-d7c2-4df6-980d-dd4f3ed46152.png)

More details: https://github.com/rayylin/Python-Production_Planning
# Route Optimization & Warehouse Picking Operations Optimization 
|Tools Used|Project Description|
|---|---|
|Python for Traveling Salesperson Problem with Gene Algorithm|In this project, we use the Gene algorithm to solve the TSP problem and applied the solution to perform route optimization. Users enter the names or addresses they want to visit. The model turns the addresses into coordinates, calculates the distances among points, performs the Gene Algorithm, and returns the best route.|

![image](https://user-images.githubusercontent.com/58899897/198494737-98086751-75c6-4032-bbca-04643cfce432.png)

![image](https://user-images.githubusercontent.com/58899897/198494675-d93b9d9d-3075-462c-b048-75d69cc7053e.png)

This model can also be used to optimize warehouse picking operations. Only need to change the function to calculate distance.
![image](https://user-images.githubusercontent.com/58899897/198830483-28d04580-8731-42db-9fef-b002cf9f55e5.png)


more detail: https://github.com/rayylin/Python_Route_Optimization_TSP
# Firm Collapse Prediction
|Tools Used|Project Description|
|---|---|
|SAS Enterprise Miner for Data Preprocessing and Modeling|Firm collapse prediction has been a subject of interest for almost a century and it still ranks high among the hottest topics in economics. The aim of predicting financial distress is to develop a predictive model that combines various econometric measures and allows one to foresee a financial condition of a firm. The purpose of bankruptcy prediction is to assess the financial condition of a company and its future perspectives within the context of long-term operation on the market. We use SAS Enterprise Miner to perform data preprocessing and modeling.|

![image](https://user-images.githubusercontent.com/58899897/198482735-beca64ec-e577-41c0-9ead-b3eeb1a24032.png)
![image](https://user-images.githubusercontent.com/58899897/198482883-889aa32d-579c-49e9-88d8-a22d592c7363.png)
more details: https://github.com/rayylin/SAS_EM-Firm_collapse_prediction

# Survival Analysis
|Tools Used|Project Description|
|---|---|
|R for Survival Analysis|Survival analysis analyzes the expected duration of time until one event occurs. In this case, we try to identify the factors that would make customers stop subscribing to a service. Businesses could adjust their marketing strategy based on the result. In this project, we will review the credit status, rate plans, and payment terms. The result shows that credit status and rate plan would affect the duration, so the company can adjust its strategy to better serve those customers to gain a higher profit.|

![image](https://user-images.githubusercontent.com/58899897/198494258-0686016b-c8ad-478c-b50a-7b0427a6bcd7.png)

more details: https://github.com/rayylin/R_Survival_Analysis

# Churn Rate Analysis (Power BI)
![image](https://github.com/user-attachments/assets/a5ffd5e0-d3cf-4d08-b103-ac58389c4ccb)


# Distribution Center Optimization
|Tools Used|Project Description|
|---|---|
|Python for Location Selection and Power BI for Data Visualization|A company now has five distribution centers (DCs) and wants to build a new one. We intend to help the company choose a location to establish a new distribution center. We want to assign warehouses of each state an appropriate DF, thereby minimizing the total distance of the network, as a longer distance implies a higher transportation cost. We have the coordinates for warehouses of each state and distribution centers. Notice that we should not change the coordinates of five existing distribution centers. We applied the KNN algorithm to minimize the total distance of the network.|

![image](https://user-images.githubusercontent.com/58899897/198397457-d6ef88c9-6988-45b6-bfab-504ea69eea9b.png)

![image](https://user-images.githubusercontent.com/58899897/198397547-ba8ac0b0-af35-4a1a-bd77-da8d667da7e7.png)
More details: https://github.com/rayylin/Python-Route_Optimization_by_KNN

# Shipment/Transportation Tracking Dashboard
|Tools Used|Project Description|
|---|---|
|Power BI for Data Visualization Python for Data Processing|As shipping becomes increasingly complicated, shipment tracking has become an important issue. In this project, we will use Power BI to build an interactive dashboard to help users track the shipping status. We will analyze  macro trends, such as shipment quantity and freight costs, and specific shipping status. As the dataset is about a pharmaceutical company, we will also focus on product category, dosage form, brand, and vendor. For each specific shipping, we can track the starting point, destination, shipment mode, and progress.|

![image](https://user-images.githubusercontent.com/58899897/198813673-de2d9af6-8fdf-4c02-b542-941f9db17eb6.png)

![image](https://user-images.githubusercontent.com/58899897/198813693-cddff2e7-844c-46b9-8e15-e067438cba28.png)

# Route Optimization with A*, Dijkstra, and BFS
|Tools Used|Project Description|
|---|---|
|Python for optimization with different algorithms|We could have infinite routes if we want to travel to point B from point A. Therefore, it is impractical to use the method of exhaustion to solve this problem because of resource constraints. This project uses the Breadth First Search, Dijkstra, and A* algorithms to find the shortest path between two nodes. We can apply this concept to refine logistics and transportation operations.|


![image](https://user-images.githubusercontent.com/58899897/199117134-8e170c50-3dbf-4a2b-96e8-36ded7face17.png)

![image](https://user-images.githubusercontent.com/58899897/199117173-819c9327-3a74-4080-9099-8cd0b367ef40.png)


# Factory Production Planning Optimization
|Tools Used|Project Description|
|---|---|
|Gurobi (Python) for Optimization with |When facing a production planning challenge, people usually don’t know which production scenario is the best. In this project, we use Python and Gurobi to build an optimization model that could help users achieve their goals, such as maximizing profit or minimizing holding costs. The objective of this project is to maximize our profit and schedule the production of seven products. Resource constraints are a crucial issue, as it’s impractical to have unlimited resources. Constraints could include labor, storage space, machines, etc. We need to meet all the constraints so that the model is meaningful. This model can also help people determine when to start production and when to perform machine maintenance.|

![image](https://user-images.githubusercontent.com/58899897/199109464-f6e425e2-5429-4366-acdf-9e9171781f9e.png)

The maximal profit is $399,226, and the production schedule is shown below.

![image](https://user-images.githubusercontent.com/58899897/199110966-1926caf3-fa38-42df-9c45-7dc131791122.png)


# Discrete event simulation of a factory
|Tools Used|Project Description|
|---|---|
|Python and Simpy for Discrete event simulation|Discrete Event Simulation can help businesses use computer modeling to virtually test manufacturing methods and procedures, reducing the time and costs that physical testing of a manufacturing system would incur.  In this project, I use Simpy to carry out a discrete event simulation and allow users to test different scenarios before buying tooling, reserving capacity, or coordinating other expensive production resources. Simulation can help users determine exactly is needed to achieve their goals, such as inventory levels, replenishment rates, batch sizes, production planning, etc.|

![image](https://user-images.githubusercontent.com/58899897/198489024-c7c0a83f-71dd-4b97-8885-275331c54e9e.png)

![image](https://user-images.githubusercontent.com/58899897/198489226-5b62aa8a-f2b3-432d-8174-0cfc0347edd5.png)

more details: https://github.com/rayylin/Python_Simpy-Discrete_Event_Simulation

# PO Management System
|Tools Used|Project Description|
|---|---|
|MS Access for data management|Purchase order management system plays an essential role in business operation. It helps companies effectively manage purchase orders (POs)  and reconciles supplier invoices to POs, contracts, and more. I use MS Access to create a PO management system.  The system divides PO data into four tables, ensuring data consistency and avoiding duplicating data. Also, the system allows users to manage  PO data through a friendly user interface instead of SQL.|

![image](https://user-images.githubusercontent.com/58899897/198490039-edc62e2b-c41b-4cd9-ad7f-d9b1134d0e0e.png)

more details: https://github.com/rayylin/MS_Access-Purchase_Order_Management_System

# Production Monitoring Dashboard
|Tools Used|Project Description|
|---|---|
|MS SQL Server, Power BI|A production dashboard can help users monitor the KPIs of production processes on a real-time basis and use visualization techniques, such as graphs and tables, to make production KPIs easy to understand. In this project, we use SQL Server and Power BI to build an interactive dashboard that helps users monitor production processes. With the direct query function, we could monitor the performance and troubleshoot production issues, such as  downtime and cycle time. |


# 
![image](https://user-images.githubusercontent.com/58899897/205705669-bff07f00-47af-4c35-9117-a44b077758d0.png)

# Digital Marketing Performance Dashboard
|Tools Used|Project Description|
|---|---|
|Power BI, SQL Server|A marketing performance dashboard can provide users with a high-level perspective into key performance indicators, such as conversion rate and customer segmentation. In this project, we will use SQL Server and Power BI to build an interactive dashboard that helps us monitor digital marketing performance.|

![image](https://user-images.githubusercontent.com/58899897/207111744-6a96ebbe-c303-4ef4-8d1c-b3c61cbc8568.png)
![image](https://user-images.githubusercontent.com/58899897/207112034-2272b7d0-7aff-4182-8463-3e9375b2ccd3.png)

# AB Test for different website layouts
![image](https://github.com/rayylin/Project-Summary/assets/58899897/fc1a71b2-5c6a-462d-9c62-3d37ddde6265)

# [Online Shopping Website with Basket Analysis](https://github.com/rayylin/RecommendationSys)
|Tools Used|Project Description|
|---|---|
|Python (Flask), Sql Server, JavaScript|This project builds an online store using Python Flask, featuring product browsing, category filtering and a shopping cart. It integrates basket analysis with association rule mining to provide personalized product recommendations, enhancing user experience and boosting sales. The backend uses Flask with a relational database.|

[![image](https://github.com/user-attachments/assets/28002e3f-34a5-4949-bc8e-6f67f159d258)](https://github.com/rayylin/RecommendationSys)
![image](https://github.com/user-attachments/assets/b81eda1b-073e-41e3-847f-7be417ad4ae0)


