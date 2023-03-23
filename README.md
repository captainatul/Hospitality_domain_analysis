# Hospitality_domain_analysis
**Data analysis in hospitality domain** 

Project details -  

Atliq Grands is an imaginary hotel chain company which operates in various cities in India (Delhi , Mumbai , Chennai, Hyderabad).

## Types of hotels that Atliq Grands provides -
<ul>
  <li>Atliq Seasons</li>
  <li>Atliq Exotica </li>
  <li>Atliq Bay </li>
  <li>Atliq Palace</li>
</ul>

## Types of rooms provided by Atliq Grands - 
<ul>
  <li>Standard</li>
  <li>Elite </li>
  <li>Premium </li>
  <li>Presidential</li>
</ul>

#### Bookings can be done via offline and online modes.

#### Atliq Grands is facing major competition and decrease in revenue . Data analysts are hired to make data driven dicision and look for the problems. 
#### All the informations regarding booking such as  transaction id , bookings, cancellation, and revenue generated are stored inside the Bookings Database .


# Data Analysis
 
<details>
  <summary>ETL</summary>
  
  ### ETL
  Created a copy of Bookings Database . All the analytics will be performed in the replicated version of Database. Data can either be loaded directly or after performing some transformations like normalisatio , aggregation . This process is called **ETL.** This Transformed Database is called Data Warehouse . A data analyst performs his query on this Data Warehouse.

This Data can be pulled in Python(Jupyter notebook) or SQL server to further analyze and perform queries.
</details>
<details>
<summary>Data loading and EDA</summary>
   
  ### Data loading and EDA
  Data was taken from csv files which are attached along with the project. EDA was performed for *Data Cleaning* , *Data Exploration* , *Data Transformation* and 
  *Data Visualisation*
  
</details>
<details>
<summary>Insights Generation</summary>
   
  ### Insights Generation
 After performing data analysis on the given dataset , various insights were found . 
 These includes *month by month revenue*, *month by month Ocuupancy percentage*, *Cities with most booking*, *Hotel type with most booking*. *Average revenue generated per hotel*
</details>
