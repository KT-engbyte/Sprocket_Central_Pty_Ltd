# Sprocket_Central_Pty_Ltd
![](sprocket.png)

## Introduction
Dataset provided online from the KPMG Australia internship site through the Forage platform. Dataset provided presented a real-life data set as a quick preview shows unclean and irrelevant columns, inconsistent data etc. 
The data exposed me to the concept of Data Quality review and adoption of the Industry Standard Data Quality Dimension (ISDQD) for Data assessment.

## Problem Statement: 
To identify the profitable product of the business and high net worth customers to focus on and the kind of product to possibly push. This would be achieved through the following:
-	Review of Sprocket Central Pty ltd, dataset; identify and resolve data quality issues.
-	Data exploration and model development
-	Visualization and interpretation.

## Skills/Concepts Demonstrated
- Removal of null values.
- Filters
- Changing Data types.
- Modelling
- Removing inconsistencies in datasets e.g. replacing F & Femal with Female etc.

  
## Data Sourcing:
Data provided is excel workbook which was downloaded from the forage site. It contains 4 sheets/tables:
1.	Transactions
2.	NewCustomerlist
3.	CustomerDemographics
4.	CustomerAddress
   
## Data Transformation/Cleaning
Data was cleaned and transformed with the power query editor. Data cleaning dne by adopting the Industry Standard Data Quality Dimensions.

## Data Modelling: 
PowerBI automatically create realtionships but sometimes these relationships may have to be removed or re-created if not meeting purpose e.g. 2 dimension tables automatically connected.
Adjusted Model               |           Auto Model
:---------------------------:|:--------------------------:
![](Adjusted.PNG)           | ![](Auto.png)

The model is a star schema as depicted above. There are 2-dimensional tables and a transaction table. The dimension tables are all joined to the transaction table with 1-to-many relationships.

## Visualization
The report comprises of 2 pages.
1. Total no of customers with profit generated based on product line/class/gender & state. The page also showed the job industry & their various demands for different brands.
2. Total product on offer

You can interact with the report [here](https://app.powerbi.com/groups/me/reports/d9f5f39f-6f80-4dbb-b8ca-90ce9d5ac050/ReportSection?experience=power-bi)
