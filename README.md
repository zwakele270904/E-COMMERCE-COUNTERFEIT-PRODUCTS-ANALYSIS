# E-COMMERCE-COUNTERFEIT-PRODUCTS-ANALYSIS
An in depth analysis across different aspects of E-Commerce aiming to combat counterfeit products 

## Table of content
 - [Project overview](#project-overview)
 - [Data Source](#data-source)
 - [Tools used](#tools-used)
 - [Data Cleaning](#data-cleaning)
 - [Exploratory data analysis](#exploratory-data-analysis)
 - [Data analysis](#data-analysis)
 - [Findings](#findings)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
   


### Project overview

 <img width="921" height="498" alt="Screenshot 2025-11-08 123522" src="https://github.com/user-attachments/assets/40cfc1a2-9339-4219-adf1-34ce3188f8db" />


### Data Source
Product dataset: The primary dataset used for this analysis is "counterfeit_products 22.csv" it contains detailed product information 

### Tools used 
 - Excel - for data cleaning
 - Power BI - Analysis and reporting

### Data Cleaning 
In the initial Data cleaning phase ,we Perfomed the following tasks:
 - Data inspection and Loading
 - Checking for dupicates and nulls
 - Correcting Spelling errors


### Exploratory data analysis
 - Which brands perfomed the best in counterfeit and non counterfeit products
 - Which categoery perfomed the best in Counterfeit and Non counterfeit products
 - How long were the consumers willing to wait before their product arrive
 - Which origin shipped the most counterfeit products and non counterfeit products
 - What was the relationship between existence time of the origin and the revenue made
 - Which warranty duration was the most prefered on counterfeit products and non counterfeit products


### Data analysis
 - Calculated revenue by multipliying purchases and price
 - Grouped warranty duration using Power BI data transform and conditional columns
 - Grouped shipping time using transform and conditional columns to find accurate waiting times
 - Group domain ages using conditional columns for an accurate analysis in finding years and product purchase relationships

### Findings
 - Tech corp was the dominant brand among counterfeit and non counterfeit products making a total of  $7 million dollars
 - Luxury goods were the dominant category among the non  counterfeit products contributing more than 10 % of the total revenue combined while electronics were the dominant category for counterfeit
 - For counterfeit products customers were willing to wait 6 weeks to receive their products while for Non counterfeit customers could not wait more than 2 weeksto receive their products
 - CA was the dominant shipping origin for counterfeit products ,while KR was the dominant shipping origin for non counterfeit 
 - For non counterfeit consumers they trust and use the shipping origin that has years existing ,while the counterfeit uses mostly new existing origins for their products
 - Short term duration was the dominant duration for both counterfeit and non counterfeit each contributing 29% respectively on product purchase


### Recommendations
 - Partner with brands like Tech Corp  who doinated the non counterfeit market to increase the purchases of non counterfeit
 - Provide discounts for luxury goods so that they increase in purchases as they are the category that mostly deal with non counterfeit


### Limitations
 - The brands column had many spelling errors I had to firstly fix the errors before moving further with my analysis
 - The shipping times were to many for a proper analysis I had to bucket and group it into weeks
 - The warranty durations were many for a proper analysis I had to group it into 4 groups 


