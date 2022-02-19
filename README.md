# Amazon_Vine_Analysis

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Project Overview**

The purpose of this project was to use "big data" to help a client, $ellby, optimize their marketing efforts through. $ellby is about to release a large catalogue of products on a leading retail website and would like to know how the reviews of their products compare to the reviews of similar products sold by their competitors. They are also interested in enrolling in a programme that gives out free products to select reviewers but would like us to determine based on our analysis of "big data", if it is worth the cost. As there are thousands of reviews, which are in mostly in text and are not numbers, it is our job to translate them in order to analyze them for our client $ellby. This analysis was to be done using "Google Colab" to run the code, mainly using PySpark, a big data tool that was used for all data processing, Amazon Web Services to store the data in the cloud, and pgAdmin to perform queries of the data locally.



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


![Deliverable 1 - customers_df](https://user-images.githubusercontent.com/92111396/154816334-2ab99334-1bdf-4b5a-91e6-045320176ba4.png)



![Deliverable 1 - customers_table](https://user-images.githubusercontent.com/92111396/154816343-cb486276-eba8-4154-84cf-7eee2383989f.png)



 ## **Products Dataframe and Table**
 

![Deliverable 1 - products_df](https://user-images.githubusercontent.com/92111396/154816397-72586f4f-f232-4f0c-8910-a6ba81add951.png)



![Deliverable 1 - products_table](https://user-images.githubusercontent.com/92111396/154816400-4840bde1-af51-4311-84f2-bc97cbdff912.png)



 ## **Review ID Dataframe and Table**
 
 
![Deliverable 1 - review_id_df](https://user-images.githubusercontent.com/92111396/154816406-5cc77055-ccb2-4a16-ac14-aec9cdf34107.png)
 


![Deliverable 1 - review_id_table](https://user-images.githubusercontent.com/92111396/154816410-748fd994-4844-485e-9b26-b855884a4520.png)



# **Vine Dataframe and Table**


![Deliverable 1 - vine_df](https://user-images.githubusercontent.com/92111396/154816415-620523e4-67f3-4a0e-8b69-b62501b3c109.png)



![Deliverable 1 - vine_table](https://user-images.githubusercontent.com/92111396/154816418-598340ea-757b-4124-bd6f-a1b2d2e7c9ee.png)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



## Deliverable 2 - Determine Bias of Vine Reviews


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Deliverable 3 - A Written Report on the Analysis

 ## **Purpose**

The purpose of this challenge  was to help Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team in production of AutosRUs’ newest prototype, the MechaCar. The MechaCar is currently suffering from production troubles that are blocking the manufacturing team’s progress, and upper management has directed Jeremy and his team to assist. 

In this challenge, we were tasked to assist Jeremy and the data analytics team do the following:

1. Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
2. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
3. Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
4. Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a    summary interpretation of the findings.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 ## **Results**




---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

1. A linear regression analysis identified ground clearance and vehicle length and to a lesser extent vehicle weight as the variables that are statistically unlikely to provide random amounts of variance to the linear model, meaning that all three coefficients have a significant impact on miles per gallon (mpg) for the MechaCar protypes.

2. Summary statistics of the PSI of the suspension coils from the manufacturing lots stated Lot 1 to have  a variance of 0.9795918 and Lot 2 to have  a variance of 7.4693878 respectively, which both fall within the variance tolerance of 100-psi. Lot 3 however, had a variance of 170.2861224, which exceeds the variance toleration dictated in the design specifications

3. The t-tests determined that there is no statistical difference between the sample of Lot 1 and the population mean, there was a strong correlation between the sample of Lot 2 and the population mean, and that there is a very weak correlation between the sample PSI of Lot 3 and the population mean.

4. A number of variables were identified as possible indicators of vehicle performance of the MechaCar against vehicles from other manufacturers such as acceleration speed, cost, and fuel efficiency. In designing our own statistical test, it was decided that t-test would be used to test the hypothesis and would be measured against the normal correlation with a p-value of 0.05.













