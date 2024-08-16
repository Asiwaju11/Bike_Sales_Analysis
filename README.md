#  Bike_Sales_Analysis

##  Table of Content
-  [Project  Overview](#project-overview)
-  [Data  Source](#data-source)
-  [Tools](#tools)
-  [Data Cleaning and Preparation](#data-cleaning-and-preparation)
-  [Exploratory Data Analysis](#exploratory-data-analysis)
-  [Data Analysis](#data-analysis)
-  [Results / Findings](#results-/-findings)
-  [Limitations](#limitations)
-  [References](#references)


##  Analysis of Bike Sales relative to buyer's socio economic status

###  Project Overview

Overview This data analysis project aims to provide insights into the socio-economic status of  Biker buyers  across The Pacific, Europe and North America . By analyzing various aspects of the  data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding for bike retail companies and also understand how socio-economics determines or affects bike purchase across different groups

![Dash2](https://github.com/user-attachments/assets/09fe2fd4-2f08-4207-a4e7-abae946ae27f)


###  Data Source
  The primary dataset used for this analysis is the "bikes_buyer.csv" file, containing detailed information about the the buyers of bikes across the three regions listed above

###  Tools

-  Excel  - Data Cleaning, Analysis and Visualization
    -  [Download here](www.microsoft.com)
 

###  Data Cleaning & Preparation
In the initial data preparation phase, I performed the following tasks: 
1.  Data loading and inspection.
2.  Handling missing values.
3.  Data cleaning and formatting

###  Exploratory Data Analysis (EDA)

EDA involved exploring the sales data to answer key questions, such as :

-   What  gender of the average customer?
-   What is the marital status of an average customer
-   What is the average income per purchase of a customer?
-   What is the customer's age bracket?
-   What is average education level of the customers?
-   Which region has the most customers

###  Data Analysis
```Excel functions
Replace Ms and Fs with Male and Female , Using Ctrl+H
Replace Ms  and Fs  with Married and Single using Ctrl+H
Create age brackets using "If" "=IF(L2>54,"Old",IF(L2>=31,"Middle age",IF(L2<31,"Adolescent","Invalid")))" Function
```


###  Results / Findings

The analysis results are summarized as follows:
1.  There are more male buyers of bikes
2.  On average , there are more married customers than singles
3.  The average monthly income of buyers varies across the three regions, but North American buyers earn slightly more than others at $56k
4.  There are more married Middle aged customers who are married than other demographics
5.  An average cuaatomer is either with a bachelor's or partially educated froma college
6.  North America is the residence of most customers


###  Limitations

The data is solely focused on the customers and didn't provide information about the sales company(ies) it is therefore hard to correlate the analysis directly with the company's  revenue


###  References 
-  Alex the Analyst
-  Excel for data analysis 

📊
