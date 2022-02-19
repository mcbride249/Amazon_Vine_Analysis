# Amazon_Vine_Analysis

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Project Overview**

The purpose of this project was to use "big data" to help a client, $ellby, optimize their marketing efforts through. $ellby is about to release a large catalogue of products on a leading retail website and would like to know how the reviews of their products compare to the reviews of similar products sold by their competitors. They are also interested in enrolling in a programme that gives out free products to select reviewers but would like us to determine based on our analysis of "big data", if it is worth the cost. As there are thousands of reviews, which are in mostly in text and are not numbers, it is our job to translate them in order to analyze them for our client $ellby. This analysis was to be done using "Google Colab" to run the code, mainly using PySpark, a big data tool that was used for all data processing, Amazon Web Services (AWS) to store the data in the cloud, and pgAdmin to perform queries of the data locally.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Resources**

-Data Source: challenge_schema; Amazon_Reviews_ETL_starter_code

-Software: Python 3.7.10, Visual Studio Code, 1.38.1, pgAdmin 4, colab.research.google.com, aws.amazon.com.

-Resources: https://colab.research.google.com/notebooks/welcome.ipynb, stackoverflow.com, https://spark.apache.org/docs/latest/api/python/.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Module 16 - Challenge** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Deliverable 1 – Perform ETL on Amazon Product Reviews

A snapshot of the code completed dataframes that were imported into their repsective tables on pgAdmin 4 can be found below.


 ## **Customers Dataframe and Table**


## **Customers Dataframe**

![Deliverable 1 - customers_df](https://user-images.githubusercontent.com/92111396/154816334-2ab99334-1bdf-4b5a-91e6-045320176ba4.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20customers_df.png


## **Customers Table**

![Deliverable 1 - customers_table](https://user-images.githubusercontent.com/92111396/154816343-cb486276-eba8-4154-84cf-7eee2383989f.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20customers_table.png



## **Products Dataframe and Table**
 
## **Products Dataframe**

![Deliverable 1 - products_df](https://user-images.githubusercontent.com/92111396/154816397-72586f4f-f232-4f0c-8910-a6ba81add951.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20products_df.png


## **Products Table**

![Deliverable 1 - products_table](https://user-images.githubusercontent.com/92111396/154816400-4840bde1-af51-4311-84f2-bc97cbdff912.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20products_table.png



## **Review ID Dataframe and Table**
 
## **Review ID Dataframe**
 
![Deliverable 1 - review_id_df](https://user-images.githubusercontent.com/92111396/154816406-5cc77055-ccb2-4a16-ac14-aec9cdf34107.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20review_id_df.png


## **Review ID Table**

![Deliverable 1 - review_id_table](https://user-images.githubusercontent.com/92111396/154816410-748fd994-4844-485e-9b26-b855884a4520.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20review_id_table.png



## **Vine Dataframe and Table**

## **Vine Dataframe**

![Deliverable 1 - vine_df](https://user-images.githubusercontent.com/92111396/154816415-620523e4-67f3-4a0e-8b69-b62501b3c109.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20vine_df.png


## **Vine Table**

![Deliverable 1 - vine_table](https://user-images.githubusercontent.com/92111396/154816418-598340ea-757b-4124-bd6f-a1b2d2e7c9ee.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%201%20-%20vine_table.png


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Deliverable 2 - Determine Bias of Vine Reviews

## **Total Vount Count Equal To or Greater Than 20**

![Deliverable 2 - Votes Greater Than 20](https://user-images.githubusercontent.com/92111396/154816890-aee9d886-d006-4e6c-80ff-edd0b87c6712.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%202%20-%20Votes%20Greater%20Than%2020.png


## **Percentage of Helpful Votes Greater Than 50%**

![Deliverable 2 - Percentage of Helpful Votes Greater Than 50%](https://user-images.githubusercontent.com/92111396/154816947-11a4d0c0-9159-43a0-a5c6-77a8c8d30372.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%202%20-%20Percentage%20of%20Helpful%20Votes%20Greater%20Than%2050%25.png


## **Number Of Reviews Part of Vine (Paid) Programme**

![Deliverable 2 - Review Part of Vine (Paid) Programme](https://user-images.githubusercontent.com/92111396/154816950-de1eeb18-f38d-4bc5-8283-900fe65b7ba7.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%202%20-%20Review%20Part%20of%20Vine%20(Paid)%20Programme.png


## **Number Of Reviews Not Part of Vine (Unpaid) Programme**

![Deliverable 2 - Review Not Part of Vine (Unpaid) Programme](https://user-images.githubusercontent.com/92111396/154816953-057a6c90-8522-45e9-94dc-205df2a3ce52.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%202%20-%20Review%20Not%20Part%20of%20Vine%20(Unpaid)%20Programme.png


## **Analysis of Paid & Unpaid Reviews**

![Deliverable 2 - Analysis of Paid   Unpaid Reviews](https://user-images.githubusercontent.com/92111396/154816957-ada6f424-a81a-4ac5-af64-24f11088d678.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%202%20-%20Analysis%20of%20Paid%20%26%20Unpaid%20Reviews.png


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Deliverable 3 - A Written Report on the Analysis

 ## **Purpose**

The purpose of this challenge was to analayze Amazon reviews written by members of the paid Amazon Vine programme. The dataset that was selected for anlaysis was the "Outdoors" dataset. The analysis involved using PySpark to perform the extract, transform, load (ETL) process to extract the data the dataset, transform the data and then connect to an AWS RDS instance, and load the transformed data into pgAdmin. Once the ETL process had been completed, PySPark was continued to be used for analysis to determine if there is any bias toward favorable reviews from Vine members in the "Outdoors" dataset. 


The anlysis focussed on answering the following questions:

1. How many Vine reviews and non-Vine reviews were there?
2. How many Vine reviews were 5 stars? 
3. How many non-Vine reviews were 5 stars?
4. What percentage of Vine reviews were 5 stars?
5. What percentage of non-Vine reviews were 5 stars


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 ## **Results**

1. How many Vine reviews and non-Vine reviews were there?

There were a total of 39,976 reviews consisting of both Vine and non-Vine reviews. There was a total of 107 Vine (paid) reeview and a toal of 39,869 non-Vine (unpaid reviews).

![Deliverable 3 - Total Paid Reviews](https://user-images.githubusercontent.com/92111396/154817755-e9906df7-b7fa-4b15-b8e8-bd5603441eda.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Paid%20Reviews.png


![Deliverable 3 - Total Unpaid Reviews](https://user-images.githubusercontent.com/92111396/154817759-6abf20e4-84b8-40e0-82d0-af76423dcd09.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Unpaid%20Reviews.png


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

1. A linear regression analysis identified ground clearance and vehicle length and to a lesser extent vehicle weight as the variables that are statistically unlikely to provide random amounts of variance to the linear model, meaning that all three coefficients have a significant impact on miles per gallon (mpg) for the MechaCar protypes.

2. Summary statistics of the PSI of the suspension coils from the manufacturing lots stated Lot 1 to have  a variance of 0.9795918 and Lot 2 to have  a variance of 7.4693878 respectively, which both fall within the variance tolerance of 100-psi. Lot 3 however, had a variance of 170.2861224, which exceeds the variance toleration dictated in the design specifications

3. The t-tests determined that there is no statistical difference between the sample of Lot 1 and the population mean, there was a strong correlation between the sample of Lot 2 and the population mean, and that there is a very weak correlation between the sample PSI of Lot 3 and the population mean.

4. A number of variables were identified as possible indicators of vehicle performance of the MechaCar against vehicles from other manufacturers such as acceleration speed, cost, and fuel efficiency. In designing our own statistical test, it was decided that t-test would be used to test the hypothesis and would be measured against the normal correlation with a p-value of 0.05.













