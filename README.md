# Summary
This project focused on creating monthly retention cohorts of The Look E-Commerce (fictitious clothing site in Google Bigquery) in 2019 - 2022. I created monthly retention cohorts based on the date that a user purchased a product and then analyze how many of them (%) coming back for the following month. After that, I created hypotheses of the analysis and suggested a business recommendation based upon that.
# Dataset
The dataset used is The Look E-Commerce (fictitious clothing site in Google Bigquery) in 2019 - 2022.
https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce?q=search&referrer=search&project=sincere-torch-350709
# Project Goals
Creating monthly retention cohorts of The Look E-Commerce and analyzing how many of them was coming back for the following month in 2019 - 2022.
# Methodology
## Data Preparation & Cleaning
Query process was done on Google BigQuery,
https://console.cloud.google.com/bigquery?sq=630202522940:859477d072be46839e0d7c85dc88f56f

![image](https://user-images.githubusercontent.com/123222363/216256566-457396d8-1d54-4f37-9912-d60a0dba3ce4.png)
![image](https://user-images.githubusercontent.com/123222363/216256731-55c53ec0-1d77-4367-afe8-793884a23f88.png)
![image](https://user-images.githubusercontent.com/123222363/216256798-eab3a2ae-b752-4931-9721-a78228421627.png)
![image](https://user-images.githubusercontent.com/123222363/216256878-539adb76-2f27-4531-9a82-b2480c42e4ab.png)

## Data Analysis & Visualization
The result of the query was being processed on Google Sheet for further analysis https://docs.google.com/spreadsheets/d/12KKWA1zgr-6FSK8dLNrhgOQG6Xv_yECMdqzlCNpDmZQ/edit?usp=sharing

The query resulted a monthly retention cohorts based upon the first date of a user’s purchase and the following months in 2019 - 2022. However for the further analysis I analyzed the time frame of the latest 1 year (2021-2022) to measure their latest user engagement for the next marketing strategy.

![image](https://user-images.githubusercontent.com/123222363/216259045-7bb00db2-4352-4008-95f0-e895c26c9038.png)

The total user in each cohort month showed an upward trend in a year (number of user increasing over time).

![image](https://user-images.githubusercontent.com/123222363/216259245-ac89c716-43b2-4caf-9d3a-705c6cd16937.png)

The retention curve showed the retention of the cohorts over time, out of all new users during the time range (48131 users), 10.18% were retained on 1 month after, 5.66% on 6 months after, and 2.44% on 12 months after.

![image](https://user-images.githubusercontent.com/123222363/216259360-68d2fea0-c54f-4c4d-84c1-a654a3a2d271.png)


