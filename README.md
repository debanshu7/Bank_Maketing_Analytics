# Bank_Maketing_Analytics

Overview:

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit. The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be subscribed or not.

Dataset:

Dataset can be downloaded from: https://archive.ics.uci.edu/ml/machine-learning-databases/00222/

Data Description:

Title: Bank Marketing (with social/economic context)

Sources Created by: Sérgio Moro (ISCTE-IUL), Paulo Cortez (Univ. Minho) and Paulo Rita (ISCTE-IUL) @ 2014


Relevant Information:

The zip file includes 4 datasets:

1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date
(from May 2008 to November 2010)
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this
dataset with fewer inputs).
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older
version of this dataset with fewer inputs).
The binary classification goal is to predict if the client will subscribe a bank term deposit (variable y).

Total count of leads are 45211 but, y is 'Yes' only for 5289 values of these.


FINAL INSIGHTS,

Insight 1 : Out of 45211, only 5289 people are SUBSCRIBERS
Insight 2: 37.04% Subscribers are in the age group of (29 to 39)
Insight 3: The conversion rate lies mostly between 40 and 50 %, with rising above 80% for people of age 80 and above.
Insight 4: The count vs conversion rate is best for age group = 62 and least for age group = 73 years
Insight 5: In the age (60-90), the Leads conversion rate is 5X as compared to age group (25-55).
Insight 6: Mean conversion rate for all the age groups is 10.102%
Insight 7: Last two graphs and insight show that people in the age group of 37 - 45 are targeted the most as the leads
Insight 8: People who work in Managment, Technician, and Blue-collor jobs are approached (as a lead) the most 
Insight 9: People who are Self-employed, entrepreneur, and housemaid are approached (as a lead) the least . 
Insight 10: Students, services people and Self-Employed people are easiest to convert, whereas technician, blue-collar and Entrepreneur are difficult to convert.
Insight 11: Single people tend to subscribe term deposit the most. 
Insight 12: Well Educated people who have atleast secondary secondary education are more likely to subscribe 
Insight 13: Approximately 63% of the customers have a home loan on them.
Insight 14: Only 9% of customers have personal loan on them.
Insight 15: Of all the customers subscribed, nearly 9% have defaulted the credit risk
Insight 16: Average duration per call for customers who subscribe to term deposit is 8.9 minutes, maximum call duration is 64 mins and minimum is 0.133 mins. 
Insight 17: 48% of the customers subscribed within 1 contact and 87% of customers subscribed within 3 contacts during the campaign.

CONCLUSIONS,

CONCLUSIONS,

 Conclusion 1 : From insight 5,6, and 7, it is observed that people in the age group of 35 - 45 are most approached than others and have a good conversion rate.
 But, the older people above 60, although are approached less have conversion nearing to 80 %. 
 Thus, we should do consider increasing the leads to people above 60 years.

 Conclusion 2 : From Insights 8,9 ,and 10, it can be observed that Students, services people and Self-Employed people are easiest to convert but these are approached the least.
 Similarly,people being Technician or having Blue-collor jobs are approached the most but have the least conversion.
 So, here we can bring some changes in this approach.

 Conclusion 3 : Single people tend to subscribe term deposit the most but are approached less than married individuals.
 Thus, new leads and conversions should be generated from single leads.

 Conclusion 4 : Approaches can be biased based on the Education level of the lead or on the type of loan owned by the lead as given in Insights 12, 13, 14, and 15.

 Conclusion 5 : Insights 16 and 17 tells about the duration of call for customers and average number of contacts required to convert a lead to a customer. 
