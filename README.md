# Understanding Factors Influencing Bike Purchases

### Project Overview
---
This data analysis project aims to investigate the factors that influence whether a customer purchases a bike or not. The dataset includes information about customer characterists and purchase decisions.


### **ASK**
---
This phase involves defining the issue to be solved, identifying stakeholders and what their expectations from the project are.

Three questions will guide the future marketing program:

1. What Demographic Factors Influence Bike Purchases?
   
    - Explore the relationship between age, gender, and income levels of customers and their likelihood to purchase a bike.
  
    - Analyze if certain demographics are more inclined to make bike purchases and if there are specific preferences within different demographic segments.
  
3. How Does Customer Commute Distance Impact Bike Purchase Decisions?

   - Is there a correlation between the length of the customer commute and the likelihood of making a bike purchase?
     
   - Do customers with shorter commutes show a higher tendency to purchase bikes compared to those with longer commutes?

#### Business Task
Identify and understand the key factors influencing bike purchases to optimize marketing strategies.

#### Key Stakeholders
- **Marketting Analytics Team**: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.
  
- **Executive Team**: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.
  

### **PREPARE**
---
Involves collecting data and information and ensuring it satisfies necessary parameters.

#### Data Location, Licensing, and Privacy
The data has been made available on Github at this [link](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx) under this [license](). 

For privacy purposes, the rider’s personally identifiable information has been excluded from the data.

#### Data Organization
The data used for this analysis is the past 12 months from November 2020 to October 2021. Each month contains hundreds of thousands of rows and 13 columns.

#### Bias and Credibility
The data satisfies the ROCCC standard which means that it is reliable, original, comprehensive, current, and cited.

#### Data Limitations
The dataset contained one null value that was deleted and hence not used in the analysis.


### PROCESS
---
This phase of the analysis process includes cleaning the data and making sure it is fit for purpose. As well as making any modifications necessary.

Exel was used for the data processing phase of this project.

A summary of the cleaning and manipulation done to the data is presented below:

#### Changes
1. Found and removed one blank row (Used Conditional formatting, countblank function and Find&Select tool on the menu bar for this task).
2. Checked and verified the length of characters in the Ride_id column (Used the Len() function for this task).
4. Trimed Coumns to remove whitespaces and replaced entire columns by pasting only values (Use Trim() function for this task).

#### New
1. Created a new column to calculate ride_length (ended_at - started_at) and changed datatype to Time datatype.
2. Created a new column to extract day_of_week (1 = Sunday and 7 = Saturday) and changed datatype to General (Used the weekday() function for this task).
3. Created a new column to extract the date start_date from date-time datatype (Used the int() function for this task).


### **ANALYZE**
---
In this phase we analyze the data using statistical methods to find patterns, relationships, and trends.

Excel was used for the data analysis phase of this project.

Outlined below are the key takeaways derived from the analysis of the data:






### Objectives
---
- Analyze customer data to understand factors influencing bike purchases.
- Identify key features contributing to bike purchases.
- Provide actionable insights for improving marketting strategies.

### Data Collection
---
The dataset used in this analysis contains records of customer interactions, including details about marketting touchpoints and whether a customer made abike purchase.

### Data Sources
---
- **Customer Characteristics**: Demographics, Preferences
- **Purchases Decision**: Yes, No

### Data Preprocessing
---
- Handled missing data and inconsistencies
- Extracted relevant features for analysis

![Dashboard](Dashboard_Image.PNG)

![Dashaboard_Image](https://github.com/ziraefrimpong1/Excel_Project_1/assets/154938134/fa59d23a-f5bf-4943-951c-17d7c6c4eada)





