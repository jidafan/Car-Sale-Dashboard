# Car Supply Chain Sales Dashboard

## Table of Contents
* [Introduction](#introduction)
* [Data Review](#data-review)
* [Data Cleaning](#data-cleaning)
* [Dashboard](#dashboard)

### Introduction

There is a lot of information that needs to be stored after a company makes a sale, this includes the price of the sale, the product sold, the location of the purchase and much more. The dashboard tracks information on vehicle sales made by a company from all over the US. The dashboard contains a detailed view of the orders, sales and customers. 

### Data Review

The information in the datasets contains information on 1000 car sales from a fictitious company. The data was sourced from [Kaggle](https://www.kaggle.com/datasets/prashantk93/supply-chain-management-for-car/data) and downloaded using the Kaggle API. The code for downloading the data can be accessed [here](https://github.com/jidafan/Car-Sale-Dashboard/blob/main/Download.ipynb). 

### Data Cleaning

Before we begin analyzing the data and creating a dashboard we must clean and prepare the data. To do so, we load the data into powerBI and use the power PowerQuery Editor to clean the data.

#### Removed Unnecessary Columns

First, we removed unnecessary columns that we did not need to visualize or analyze

#### Fixed data types

Secondly, we fixed the data types of certain variables, as they were categorized under the wrong values.

### Dashboard

The dashboard contains three different views that a user can interact with. Firstly, the orders view where users can look at the details of orders and see a general overview of the orders. Secondly, the sales view, where a user can see the sales trends for the quarters or the month. Lastly, a customer overview, where a user can see the relation of customers to sales.

The dashboard can be downloaded [here](https://github.com/jidafan/Car-Sale-Dashboard/blob/main/Car%20Dashboard.pbix)

