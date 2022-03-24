# BAIT 580A Database Applications Final Project

This reprotority contains the final group project for the course BAIT 580A: Database Applications in Business Systems.

The topic of this project is COVID-19 Response and Public Satisafaction.

## Purpose

COVID-19 Omicron is fast becoming a health emergency. Canada is seeing a rapid rise in people testing positive. There is increasing stress in the healthcare system in terms of people tested, hospitalizations, and ICUs. The social costs can be enormous and the government wants to understand both the real costs and sentiments in order to address public needs as they emerge. The government needs to address the negative sentiments through concrete steps before the sentiments are expressed and they catch on.

Through the timeline of pandemic, we all experienced various emotions. They were shaped by the rises and falls of various COVID cases and variants. The government responded with a variety of measures including restrictions, vaccinations, and healthcare measure. All of these measure were received by the public with a mixed response. We would like to see how public responded so we can understand and investigate the roll out more effectively in the future.

The purpose of this project is to get a sense about how people react to certain government initiatives and life during Covid. Our problem statement is: What is the public sentiment towards government initiatives to confront COVID? So specifically, we would combine the covid cases growing trend with how people’s emotions change across time, identifying the points in time when Canadian authorities brought in new laws or changed laws and knowing how the public sentiment was reflected during those times.

## Methodology

Initially, we did data preprocessing by collaborating the Twitter dataset with the Covid dataset and did table normalization separately. After doing background research for key events (e.g. travel restictions, mandatory use of masks and vaccination), we selected a few key dates on which these events happened, and imported the twitter data related to these specific dates to AWS.

For the analysis part, we used functions such as groupby for different columns in different cases, counted the number of tweets posted on each date, and created line charts to answer general questions we brought up at the begining of our project, such as "What is the the general trend of the public's attention to COVID?", and the event timeline of governement initiatives.

We also applied data visualization to figure out tweet sentiment varying trend around the key dates, getting people's positive and negative reactions to government initiatives towards COVID.

## Contents in the Repository

+ Jupyter notebook containing the codes
+ Slide deck presentation

## Contact

Lige Liu<br>
University of British Columbia – Sauder School of Business<br>
Master of Business Analytics in progress<br>
Email: [ligeliu2@gmail.com](mailto:ligeliu2@gmail.com)

## Contributors

+ Lige Liu, UBC Sauder School of Business, ligeliu2@gmail.com
+ Amit Chalka, UBC Sauder School of Business, chalka.amit@gmail.com
+ Hammad Habib Qazi, UBC Sauder School of Business, hammad.h.qazi@gmail.com
+ Yanlei Chen, UBC Sauder School of Business, yanleich@student.ubc.ca
+ Yiwen Kuang, UBC Sauder School of Business, eva.kuang@foxmail.com
