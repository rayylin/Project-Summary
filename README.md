# Project-Summary
This is the table of contents of all projects
1. PO Management System
2. Discrete event simulation of a factory
3. Sales Performance Tracking Dashboard
4. Store Items Demand Forecast
5. Sales Performance Analysis
6. Material Planning
7. Route Optimization & Warehouse Picking Operations Optimization
8. Firm Collapse Prediction
9. Survival Analysis
10. Distribution Center Optimization
11. Shipment/Transportation Tracking Dashboard
12. Route Optimization with A*, Dijkstra, and BFS

# PO Management System
|Tools Used|Project Description|
|---|---|
|MS Access for data management|Purchase order management system plays an essential role in business operation. It helps companies effectively manage purchase orders (POs)  and reconciles supplier invoices to POs, contracts, and more. I use MS Access to create a PO management system.  The system divides PO data into four tables, ensuring data consistency and avoiding duplicating data. Also, the system allows users to manage  PO data through a friendly user interface instead of SQL.|

![image](https://user-images.githubusercontent.com/58899897/198490039-edc62e2b-c41b-4cd9-ad7f-d9b1134d0e0e.png)

more details: https://github.com/rayylin/MS_Access-Purchase_Order_Management_System


# Discrete event simulation of a factory
|Tools Used|Project Description|
|---|---|
|Python and Simpy for Discrete event simulation|Discrete Event Simulation can help businesses use computer modeling to virtually test manufacturing methods and procedures, reducing the time and costs that physical testing of a manufacturing system would incur.  In this project, I use Simpy to carry out a discrete event simulation and allow users to test different scenarios before buying tooling, reserving capacity, or coordinating other expensive production resources. Simulation can help users determine exactly is needed to achieve their goals, such as inventory levels, replenishment rates, batch sizes, production planning, etc.|

![image](https://user-images.githubusercontent.com/58899897/198489024-c7c0a83f-71dd-4b97-8885-275331c54e9e.png)

![image](https://user-images.githubusercontent.com/58899897/198489226-5b62aa8a-f2b3-432d-8174-0cfc0347edd5.png)

more details: https://github.com/rayylin/Python_Simpy-Discrete_Event_Simulation

# Sales Performance Tracking Dashboard
|Tools Used|Project Description|
|---|---|
|Power BI for Data Visualization and Performance Tracking|In this project, I build a dashboard to track and analyze KPIs and visualize information across the organization to improve decision-making processes. I have the actual sales and expected sales for salespersons, transaction data, and store data. I visualize the data with a Power BI dashboard. It can help us identify trends or components impacting a company's sales operations. The dashboard is interactive, and we could drill down the data to a more detailed and granular view, understanding the impacts of each product, salesperson, and store.|

![image](https://user-images.githubusercontent.com/58899897/198494543-5d30d4c9-e25f-4b71-8a9c-ad74be991add.png)

more details: https://github.com/rayylin/Power-BI_Purchase_order_analysis
# Store Items Demand Forecast
|Tools Used|Project Description|
|---|---|
|Python for Time Series Demand Forecast (ARIMA) and Sales Data Analytics|This project is about demand forecast. I have the sales data for the past five years, 930,000 in total. The raw data includes four columns, date, store, item, and quantity. First, I perform an EDA to have a basic understanding of the data. Then we could see the sales performance on different products and stores to help us better manage our inventory. Before applying the ARIMA model, we need to ensure that the data is stationary and use the Augmented Dickey-Fuller test. After the test shows that the sales data is stationary, we could use the Time Series analysis (TSA) of Statsmodels to build a model. To improve the accuracy, I include the holiday data.|

![image](https://user-images.githubusercontent.com/58899897/198486749-7e3cc2ca-32ec-4d7d-8d59-871857bb01ad.png)

![image](https://user-images.githubusercontent.com/58899897/198487347-ec0bfc2a-c8d9-43bc-a482-97c97009d031.png)

![image](https://user-images.githubusercontent.com/58899897/198487436-c7324b5d-c15c-4144-ab1e-0e6383c5a3ea.png)

more details: https://github.com/rayylin/Python-Store_Item_Demand_Forecast_with_Time_Series


# Sales Performance Analysis
|Tools Used|Project Description|
|---|---|
|Tableau for sales performance visualization and root cause analysis|In this project, I build an interactive dashboard to track and analyze KPIs and visualize information. The dashboard uses different plots to show the performance and trends of each product. The dashboard can also help users find abnormalities by drilling down the data to get more information. We find that the increasing costs affect the profit in Italy.|

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

![image](https://user-images.githubusercontent.com/58899897/198861609-be539de7-6603-4d9c-a6bd-be7e6c36ac18.png)

![image](https://user-images.githubusercontent.com/58899897/198861620-ecf2f5d7-f4e2-4687-9dec-606689bc8210.png)

# Factory Production Planning Optimization
|Tools Used|Project Description|
|---|---|
|Gurobi (Python) for Optimization with |When facing a production planning challenge, people usually don’t know which production scenario is the best. In this project, we use Python and Gurobi to build an optimization model that could help users achieve their goals, such as maximizing profit or minimizing holding costs. The objective of this project is to maximize our profit and schedule the production of seven products. Resource constraints are a crucial issue, as it’s impractical to have unlimited resources. Constraints could include labor, storage space, machines, etc. We need to meet all the constraints so that the model is meaningful. This model can also help people determine when to start production and when to perform machine maintenance.|

![image](https://user-images.githubusercontent.com/58899897/199109464-f6e425e2-5429-4366-acdf-9e9171781f9e.png)

The maximal profit is $399,226, and the production schedule is shown below.

![image](https://user-images.githubusercontent.com/58899897/199110966-1926caf3-fa38-42df-9c45-7dc131791122.png)





