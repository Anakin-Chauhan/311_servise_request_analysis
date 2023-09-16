# 311_servise_request_analysis
Analysis and hypothesis testing of 311 service request data

Data set https://github.com/Simplilearn-Edu/Data-Science-with-Python-Project-2-

Process-
1) Data import
2) Pre-processing
a. Cleaning
b. Removing null values
3) Data mining
5) Feature engineering
6) Data preparation
7) Hypothesis Testing


There was a lot of ambiguous data with a lot of null values.
After cleaning the data did some data mining and feature engineering to better analyse the data.
Plotted some graphs to understand data distribution better and did hypothesis testing later on.


Conclusion 
1) Whether the average response time across complaint types is similar or not (overall)?
    a. H0 = The average response time across Complaint types is similar
    b. H1 = The average response time across Complaint types is not similar
    c. Since our p value <0.05 we can reject our null hypothesis i.e. there is statistical similarity in the means of request closing time of all Location type and accept alternate hypothesis i.e. there is significant statistical difference in means of request closing time of different Location types
   
3) Are the type of complaint or service requested and location related?
     a. p value > 0.05 for complaint type so we cannot reject that complaint type do not have effect on request closing time.
     b. Whereas p value < 0.05 for location type so we can reject null hypothesis that location type do not have effect on request closing time.
     c. Now we can say that we cannot reject or null hypothesis completely.


Few interesting plots

![image](https://github.com/Anakin-Chauhan/311_servise_request_analysis/assets/71073104/ba9ca72b-d0f8-4a0a-a2d5-6eac9445a7fe)

![image](https://github.com/Anakin-Chauhan/311_servise_request_analysis/assets/71073104/27efcda8-1554-401a-a971-3b28dba65060)

