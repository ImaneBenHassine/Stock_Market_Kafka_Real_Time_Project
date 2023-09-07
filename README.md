# Stock Market Kafka Real Time Project

## Introduction
In this project, we will execute a Data Engineering Project by building data pipeline for **Real-Time** Stock Market Data using Kafka.

We will take some stock market data using Python to produce that data and put it onto **Kafka cluster**. After that we will consume that data and store it onto **Amazon S3 Crawl** to build a **Glue catalog** and analyze that data using **Amazon Athena** using **SQL**.

## Technologies 

Python, Amazon Web Services (AWS), Apache Kafka, Glue Crawler, Glue Catalog, Athena, and SQL.

## Steps

- write a python code that will simulate the real-time stock market application 
- read data from the data set and produce the application that simulates the stock market 
- add a producer code that will push those events into the Kafka broker 
- write a consumer code that will consume that data and put that data onto Amazon S3
- run a Glue Crawler 
- query real-time data in Amazon Athena

## Architecture 

![Architecture](https://github.com/ImaneBenHassine/Stock_Market_Kafka_Real_Time_Project/assets/26963240/c63774fe-fcc9-49fb-b9bc-ef8a4751fafb)
