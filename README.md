# Google_Capstone_Project

## Introduction
 - This is a case study stimulates a business-related scenario where I am a junior data analyst helping a bike rental company conducting a research into their customers behaviour.
 - The case study is to answer the question  “In what ways do members and casual riders use Divvy bikes differently?” for futher detail about the context of the case study please visit this link [Google Cyclistic Case Study](https://d3c33hcgiwev3.cloudfront.net/aacF81H_TsWnBfNR_x7FIg_36299b28fa0c4a5aba836111daad12f1_DAC8-Case-Study-1.pdf?Expires=1650067200&Signature=EXlwGbfl6f9eLneN0YSKR4B2WHPfKM8THQlw7RVA-elH9Qvrj0STLiIqWGyRlu0FEV94388fnxuF5XI30Ukwdbu2U9-Qs1w0AR~ywdKHem9STC9ZxTJwYiNy1wJvgCqVYno5f9B2dej3wRMswlh0-FRv2eWwOo0qXf7VDUAl9bA_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Problems
 - As stated above the case study is to analyze the company customer behaviour on bike renting which means the most important point for this case study is to understand the difference of bahaviour between casual users and member users.
 - The data required for the project can be download via this [link](https://divvy-tripdata.s3.amazonaws.com/index.html). My project focus on four files which are:
   + [Divv_Trips_2019_Q2](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q2.zip)
   + [Divv_Trips_2019_Q3](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q2.zip)
   + [Divv_Trips_2019_Q4](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q2.zip)
   + [Divv_Trips_2021_Q1](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q2.zip) 
 - All of the datasets contain basic information about the starting and ending time of a trip and user types that made that trip.
 - The tool I use in this project is R programming language, an open-source, efficient language for data analytics
 - The processing phase of the project has solved many issues with the data frames such as different column numbers, names; combining all data source into one **consistent** data frame; extracting utilizable data; removing unwanted data.
 ## Solutions
  - R programming language offers a wide range of data manipulating libraries so that I could use and tackling the aforementioned problems
  - I also utilize some librares to analyze data (calculating mean, number of rides for each type of users) and then visualize the result for further analysis about customers' behaviour.
  - My detailed data cleaning and analyzing processes are stored in [this R script](https://github.com/thaison2309/Google_Capstone_Project/blob/cb9df24418f067efd3feed45eb680ab6bc140ad7/R-anlysis-case-study.R)
  ## Conclusion
   - After a lot of data cleaning and analyzing, I could finally create some data visualizations out of the dataset:
   
   ![Number of rides](https://github.com/thaison2309/Google_Capstone_Project/blob/main/Number%20of%20rides%20by%20rider%20types.png?raw=true)
   ![Average duration](https://github.com/thaison2309/Google_Capstone_Project/blob/95bfdbdc9750984bf29aa4f8436d864d588e4832/Average%20trip%20duration%20by%20riger%20types.png)
  
   - Looking at the bar chart we could easily notice that number of rides made by member users exceeded that of casual users on every weekday which could be understandable as number of member users is threefold larger than that of the casual users. However, when it comes to average trip duration, casual users completely outstrip the member users. This could imply that casual users are mostly first-time users or visitors who only want to experience the service and rent a a bike to take on a trip to visit the city while frequent users are those who refer to this service commuting to work.
