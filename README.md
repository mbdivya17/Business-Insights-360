# Business Insights 360 Project:

Problem Statement: AtliQ, a rapidly growing consumer goods electronics company had been rely on excel files for data analytics. Due to the lack of effective analytics using excel the company faced a major loss in Latin America.

Objective: To implement data analytics using Power BI to draw insights effectively across various aspects such as Finance, Sales, Marketing & Supply Chain.

Tools used:
•	MySQL
•	MS Excel
•	Power BI
•	DAX Studio

Following methods are undertaken to build interactive dashboard:

1.Data Collection:
-	Imported provided data to MySQL database.
-	Connected Power BI with MySQL, loaded data to Power BI.
-	Local excel files directly imported to Power BI.
-	Created date table in power Query.

2.Data Validation:
-	Validated data against benchmark numbers to ensure accuracy of data & eliminate data errors.

3.Data Transformation: using power query editor
-	Replaced the error values of related columns. 
-	Calculated appropriate columns & tables for analysis using power query m-language.
-	Disabled load for unused tables to reduce file size.
-	Normalized the de-normalized table by removing repeated columns.
  
4.Data Modelling: using model view
-	Connected dimension & fact tables by the method of snowflake schema.

5.Calculated columns, measures & tables outside power query editor: using DAX
-	Necessary columns, measures & tables are created using DAX in order to improve report performance.

6. Report Optimization: using DAX studio
- Optimized report size by performing instrumentation through a tool called DAX studio by removing unessential columns in tables to reduce file size.

7. Dashboard Development: using report view
-	Power BI Report is created based on the requirements given by stakeholders.

8.Power BI service:
-	Published report in power bi service.
-	Installed a personal gateway & connected a personal computer with Power BI service for automatic data refresh of MySQL database.
