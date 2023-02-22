# ITI-Graduation-Project (E-commerce-System)
Implemented a database for e-commerce from scratch,Created data pipelines to load the data into the data warehouse, extracted useful information by applying different business intelligence solutions, and deployed machine learning models to predict profits.
## Project Steps
-Database Design
--> Designed and created an Entity-Relationship (ER) Diagram and mapping to model the database.
--> Implemented a database using Microsoft SQL Server and added stored procedures, views, functions, and triggers to ensure data consistency and integrity.
-Stored Procedures
--> created 24 stored procedures that allow customers to view and search for products, place orders, and perform other actions. Additionally, business analysts can use the procedures to view key performance indicators (KPIs) such as sales and profits.
-Data warehouse Design
Designed and Implemented a star schema data warehouse in sql server
Created data pipelines to load the data into the data warehouse
designed Ad hoc reports to make it easy to garner insights on the fly.
created interactive dashboards
Developed a Python-based desktop application to allow users to register, log in, view products, place orders, and more.
deployed a machine learning model on a small website
## Technical Details
The database and data warehouse were developed on SQL Server
The data pipelines for ETL were implemented using SSIS.
The dashboards of all aspects of the database entities are created using power bi
The desktop application uses two libraries:
one to connect to the SQL Server called pyodbc
the other to create the GUI called PyQt5.
Through the app, customers can register, log in, place orders, view and search for products, and access their order history.
implemented machine learning models( LinearRegression - KNeighborsRegressor - SVR - DecisionTreeRegressor - RandomForestRegressor ) using scikit learn
The Streamlit library was used to deploy the machine learning model.
## Demo
