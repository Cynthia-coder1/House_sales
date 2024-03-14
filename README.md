# House sales analysis

## Table of Contents 

- [Project Overview](#project-overview)
- [Exploratory data analysis](#exploratory-data-analysis)
- [Recommendations](#recommendations)
- [DataSource](#data-source)

### Project Overview
This data analysis project provides insight into house sales performance of nashville housing company over the past year. By analysing various aspects of the sales , we gain deeper understanding of the company's performance and make decisions to improve company sales .

### Data Source 
Sales data : This dataset used for this analysis is "Nashville Housing.csv"  file which contains detailed information about each sales made by the company.

### Tools
- Python - Utilized python for data cleaning demonstrating proficiency in extracting insights.
- Excel - Data visualisation. 

### Data cleaning/ Preparation 
In the data preparation phase , we performed the following tasks :

1. Data handling and inspection.
2. Handling missing values. 
3. Data cleaning and formatting. 

### Exploratory data analysis 
EDA involved exploring the sales data to answer key question such as  :

- Which PropertyType is sold the most?
- Which tax district is generating more
    Revenue?
- Which city is generating the highest revenue and which city is generatingbthe lowest revenue?

### Data analysis
Includes some interesting codes/ features worked with 

```Python
df.dropna(inplace = True)
```
```Python
df.sort_values(inplace = True)
```
###  Results/Findings
The analysis results are summarised as follows :

- Single family Property_Type was sold the most.
- Urban services district was generating more revenue. 
-  Nashville is generating the highest revenue while Joelton is generatingthe lowest.

### Recommendations 

Based on the analysis , we recommend the following actions :
- Focus on cities generating lower revenue and study the reason why the revenue from the city is low and improve the house sales to make it more suitable for the cities.


### Limitations
I had to remove all null and zero values  from the BuildingValue because they would have affected the accuracy of the analysis. I also renamed landuse to Property_Type.
