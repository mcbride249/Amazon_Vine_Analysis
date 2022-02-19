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

A snapshot of the code completed dataframes that were imported into their respective tables on pgAdmin 4 can be found below.


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

![Deliverable 2 - Votes Greater Than 20](https://user-images.githubusercontent.com/92111396/154819291-c72f2863-b201-41fd-9073-4badb6d25497.png)
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

The purpose of this challenge was to analyze Amazon reviews written by members of the paid Amazon Vine programme. The dataset that was selected for analysis was the "Outdoors" dataset. The analysis involved using PySpark to perform the extract, transform, load (ETL) process to extract the data the dataset, transform the data and then connect to an AWS RDS instance, and load the transformed data into pgAdmin. Once the ETL process had been completed, PySPark was continued to be used for analysis to determine if there is any bias toward favorable reviews from Vine members in the "Outdoors" dataset. 


The analysis focussed on answering the following questions:

1. How many Vine reviews and non-Vine reviews were there?
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
3. What percentage of Vine reviews were 5 stars?. What percentage of non-Vine reviews were 5 stars?



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Results**

##**1. How many Vine reviews and non-Vine reviews were there?**

-There was a total of 39,976 reviews consisting of both Vine and non-Vine reviews. 
-There was a total of 107 Vine (paid) reviews. 
-There was a total of 39,869 non-Vine (unpaid) reviews.

![Deliverable 3 - Total Paid Reviews](https://user-images.githubusercontent.com/92111396/154817755-e9906df7-b7fa-4b15-b8e8-bd5603441eda.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Paid%20Reviews.png


![Deliverable 3 - Total Unpaid Reviews](https://user-images.githubusercontent.com/92111396/154817759-6abf20e4-84b8-40e0-82d0-af76423dcd09.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Unpaid%20Reviews.png


##**2. How many Vine reviews were 5 stars?**

-There was a total of 21,061, 5 star reviews consisting of both Vine and non-Vine 5 star reviews. 
-There was a total of 56 Vine (paid) 5 star reviews. 
-There was a total of 21,061 non-Vine (unpaid) 5 star reviews.

![Deliverable 3 - Total Paid 5 Star Reviews](https://user-images.githubusercontent.com/92111396/154817980-8586f7d7-b472-4aa1-8b7c-d24e087ee34a.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Paid%205%20Star%20Reviews.png


![Deliverable 3 - Total Unpaid 5 Star Reviews](https://user-images.githubusercontent.com/92111396/154817985-89681e65-cc18-45d0-84a8-120269f5f23e.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Total%20Unpaid%205%20Star%20Reviews.png


##**3. What percentage of Vine reviews were 5 stars?. What percentage of non-Vine reviews were 5 stars?**

-The percentage 5 star reviews for Vine (paid) participants was 52.3364 percent. 
-The percentage of 5 star reviews of non-Vine (unpaid) participants was 52.6850 percent.

![Deliverable 3 - Percentage of Paid 5 Star Reviews](https://user-images.githubusercontent.com/92111396/154818114-caaf0356-37da-4284-90f4-2d9b72478436.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Percentage%20of%20Paid%205%20Star%20Reviews.png


![Deliverable 3 - Percentage of Unpaid 5 Star Reviews](https://user-images.githubusercontent.com/92111396/154818123-9a5a7b60-d1f3-4711-8c11-5af2d8527ae2.png)
https://github.com/mcbride249/Amazon_Vine_Analysis/blob/main/Images/Deliverable%203%20-%20Percentage%20of%20Unpaid%205%20Star%20Reviews.png


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

1. Based on the results, we can conclude that there does not appear to be any positivity bias as to whether the paid Vine participants are producing more positive reviews of products compared to the non-Vine (unpaid) participants. A similar percentage of both paid and unpaid groups reviewed the products as 5 stars; in fact, a slightly greater portion of unpaid reviewers (52.68%), rated the products as 5 stars compared to only 52.33% of Vine members. Excluding statistical testing that could be done to determine if the sample sizes were large enough based on overall Vine participation, we can conclude that there does not appear to be any statistical positivity bias for Vine participants when it comes to providing 5 star reviews for the Outdoor products as there is a similar percentage of of paid and unpaid reviewers who gave the products a 5 star review.

2. To further gain clarity on the data and ensure there is in fact no positivity bias, we should expand our analysis to include 4 star reviews, as this also shows positivity towards a product. Additionally, we could compare the total number Vine participants who reviewed products for this dataset to the total membership in the Vine programme and determine what the overall percentage of those 5 star reviews is for Vine members for all products compared to non-Vine members. Additionally, we could calculate the mean, median, and mode of 5 star reviews within our own data set for both groups (paid vs unpaid) to more accurately visualize the distribution of the two groups and any discrepancies between them.










