# Summary
This project focused on creating monthly retention cohorts of The Look E-Commerce (fictitious clothing site in Google BigQuery) in 2019 - 2022. I created monthly retention cohorts based on the date that a user purchased a product and then analyze how many of them (%) came back for the following month. After that, I created hypotheses for the analysis and suggested a business recommendation based on that.
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

Overall, in the time frame of 6 months, the user who came back to purchase in the marketplace was decreasing around 50%.

### Hypothesis 1 Decreasing activity in Active users in the same cohort within a year

![image](https://user-images.githubusercontent.com/123222363/216260141-8abb18ca-4108-4112-abb5-3ae423f47cd4.png)
![image](https://user-images.githubusercontent.com/123222363/216260178-53dcd688-4261-4a6d-99da-68d6fea5e96a.png)
![image](https://user-images.githubusercontent.com/123222363/216260225-a5edf285-d4f2-4e77-af04-d553fe4cf894.png)

The result of the query was being processed on Google Sheet for further analysis https://docs.google.com/spreadsheets/d/1d15bXXdxKLDDqXZuK9tfsokh5YXADQ6Yt1Sov6FqPKc/edit?usp=sharing

![image](https://user-images.githubusercontent.com/123222363/216260630-74924df5-6bb1-43f6-90da-59b4f8cf5917.png)
![image](https://user-images.githubusercontent.com/123222363/216260741-d0f8a832-21c2-47cf-a27b-208bb629f0af.png)
![image](https://user-images.githubusercontent.com/123222363/216260783-f913cb96-e1eb-40de-8985-e747c0046882.png)

The total of active users in each cohort month showed an upward exponential trend in a year because of the high rise up in the 12 months after.
The retention curve showed the retention of the cohorts over time, out of all new active users during the time range (6549 users), 21.33% were retained on 1 month after, 9.70% on 6 months after, and 4.26% on 12 months after.
In summary, in the time frame of 6 months, the active user who came back to purchase in the marketplace is decreasing around 50% (the same as our main cohort analysis)

### Hypothesis 2 Decreasing activity in non-active users in the same cohort within a year

![image](https://user-images.githubusercontent.com/123222363/216261187-769039a1-5761-471c-ab38-569ff972a068.png)
![image](https://user-images.githubusercontent.com/123222363/216261254-fbeb7029-e1ce-4d8f-acb1-71bbbb52ba47.png)
![image](https://user-images.githubusercontent.com/123222363/216261297-8a749786-f222-48d9-b776-79b7bfe13b18.png)

The result of the query was being processed on Google Sheet for further analysis https://docs.google.com/spreadsheets/d/1_W1xcYUbOR_nML_cMExZgb0c5htS-VZ4AbhT8t9DegA/edit?usp=sharing

![image](https://user-images.githubusercontent.com/123222363/216261522-1545b717-2f96-4fa9-9879-47c9796295d1.png)
![image](https://user-images.githubusercontent.com/123222363/216261748-e6cf1c16-8c75-4036-ba9c-caab7f6cef0d.png)
![image](https://user-images.githubusercontent.com/123222363/216261795-4eb685cc-1fe1-42ee-9077-2bdb2459cceb.png)

The total of non-active users in each cohort month showed an upward trend until 11 months after and a large drop occurs in the 12 months after. The retention curve showed the retention of the cohorts over time, out of all new non-active users during the time range (41582 users), 8.97% were retained on 1 month after, 5.42% on 6 months after, and 2.37% on 12 months after.

### Hypothesis 3 The total user who completed their orders has decreased within a year

![image](https://user-images.githubusercontent.com/123222363/216262433-8fe178ec-7c4d-4b4f-a0c9-9a46ad6c3a97.png)

The result of the query was being processed on Google Sheet for further analysis https://docs.google.com/spreadsheets/d/1P2FocJl-1IyWNqWgXBsx_AyUxFAjpb8Y8z90g5rCIGI/edit?usp=sharing
The percentage of total user who completed their orders within a year showed stationary trend and tend to slightly showing an uptrend in 2022.
So, the total user who completed their order hasn’t decreased in a year.

![image](https://user-images.githubusercontent.com/123222363/216262605-5f69860a-e1fa-42ed-a86c-b1668ad6a9ff.png)

## Insight & Recommendation
As the overall of total user in each cohort month was increasing over time within the year, we can conclude that they had a good onboarding experience. However, as the retention curve indicates that users weren't getting quickly engaged to the marketplace, resulting in drop-offs.
TheLook eCommerce needed to improve the user’s engagement as quickly as possible, so it could boost the retention.
