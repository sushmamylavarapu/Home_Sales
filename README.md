# Home_Sales Data Analysis with PySpark
This repository contains a Python script for analyzing home sales data using PySpark. The script performs various data analysis tasks, including calculating average prices, filtering data based on specific criteria, and measuring query runtimes. It uses PySpark, a powerful tool for processing large-scale data sets in a distributed manner.

## Table of Contents
Prerequisites

Setup

Usage

Queries

Caching

Parquet File

## Prerequisites
Before you run the script, make sure you have the following prerequisites installed on your system:

Apache Spark: You'll need to install Spark on your machine or use a cloud-based Spark cluster.

## Setup
pip install findspark

## Usage
You can run the Home_sales_colab to perform various data analysis tasks on home sales data. Here are the main functionalities:

### Queries
The script includes several SQL queries to answer specific questions about the data. These queries include:

Calculating the average price of homes for each year.
Finding the average price of homes with specific criteria (e.g., bedrooms, bathrooms, floors, and square footage).
Analyzing the relationship between the "view" rating and the average price of homes.
## Caching
This demonstrates the use of caching to improve query performance. It caches the DataFrame after loading the data, and you can compare the runtime of queries with and without caching.

## Parquet File
The file also includes an example of saving the DataFrame to a Parquet file and loading it back for analysis. This can be useful for storing and retrieving large datasets efficiently.

https://colab.research.google.com/drive/1_NE2RSZTrIjKG9egFJh-9WCdYHH4IKau?usp=sharing