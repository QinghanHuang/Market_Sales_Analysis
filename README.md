# Retail Sales Analysis with Spark

## Introduction

This repository contains a Spark Notebook for the analysis of sales data from a retail company that specializes in various types of cash registers. With a nationwide deployment, their machines are connected to the internet, uploading transaction data to the company's backend with each sale. The objective of this analysis is to provide statistical insights into sales across different provinces.

## Requirements

The analysis covers four key requirements:

1. **Sales Indicators by Province**: To calculate total sales revenue for each province.
2. **Top 3 Provinces - Stores with Daily Sales Over 1000**: To identify the number of stores in the top three selling provinces with an average daily sale greater than 1000.
3. **Average Unit Price in Top 3 Provinces**: To determine the average price per order in each of the top three selling provinces.
4. **Payment Type Ratios in Top 3 Provinces**: To analyze the proportion of each payment type used in each of the top three provinces.

## Operations

Two operations are to be performed with the results:

1. **Write Results to MySQL**: The analysis output for the requirements should be written to a MySQL database.
2. **Data Ingestion to Spark on Hive**: The data should also be ingested into Spark on Hive.

## Field Descriptions

While there are many fields available, the analysis will focus on the following key fields:

- `storeDistrict`: Administrative district of the store
- `storeProvince`: Province where the store is located
- `storeID`: Unique identifier of the store
- `storeName`: Name of the store
- `dateTS`: Date of the transaction
- `orderID`: Unique identifier of the order
- `receivable`: Amount receivable from the sale
- `payType`: Type of payment used

Only the above-mentioned fields, highlighted in red, will be used for this analysis.

## How to Use

To replicate this analysis, ensure that Apache Spark is properly set up and that the necessary dependencies are included in your environment. Data should be placed in the appropriate directories for processing with Hive.


## Contact

If you have any questions or comments about this analysis, please open an issue in the repository, and we will get back to you.


