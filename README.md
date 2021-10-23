# Starbucks-Capstone-Challenge

## Table of Contents
* [About Project](https://github.com/Razanaziz0/Disaster-Response-Pipeline-Project/blob/main/README.md#about-project) 
* [Data description](https://github.com/Razanaziz0/Disaster-Response-Pipeline-Project/blob/main/README.md#installation)
* [Result](https://github.com/Razanaziz0/Disaster-Response-Pipeline-Project/blob/main/README.md#instructions-to-run-the-code)
* [Licensing](https://github.com/Razanaziz0/Disaster-Response-Pipeline-Project/blob/main/README.md#licensing)
## About Project
#### This is the project of Udacity's data scientist nanodegree program 
In this project I use data analytics power to see customer behavior on the Starbucks shops and predicts whats the main features can  advertis the Starbucks customers by sending offers to users to get discount, or buy one get on free (BOGO).

the data set used in this project is contains simulated data that mimics customer behavior on the Starbucks this project helps to build a ML models predicts ifsomeone will respond to an offer or not.

## Data description

portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

## Result
![dashboard_e](https://user-images.githubusercontent.com/58987879/138563528-909896ba-eddd-4fb3-9bce-bf478d8dd4f3.jpg)

## Licensing
The dataset is provided by in Udacity data scientist nanodegree program.
