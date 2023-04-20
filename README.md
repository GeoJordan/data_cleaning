# data_cleaning

# Customer Transaction Dataset Data Cleaning
I created an ecommerce customer transaction dataset using multiple datasets on an eCommerce platform. This company wants to use the new dataset to analyze products and customers to support their marketing campaigns. After creating the dataset, I am comfronted with cleaning the data to make it more useful for the maketing team's ad campaigns.

As a demonstration, I use the [Brazilian E-Commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). These dataset were selected because like the Olist is an eCommerce platform that connects small business with customers from all over Brazil hence has similar characteristis as the platform I carried out the task for. 

Baring in mind that I have already merged all the datasets on the platform into one dataset (customer transaction dataset), I proceed to clean tha data to make sure it is more useful for the marketing teams ad campaigns. So I considered the following:
- working with a large datasets usually create problems including PC memory issues. Hence, these memory utilization issues must be avoided.
- some of the data in the the dataset (e.g. dates) could be 
    
    (a) in the wrong format 
    
    (b) duplicates, 
    
    (c) empty/missing values present
    
- use Pandas `map()` function to map the values in a column of the dataframe to fill out missing values in another column. 

In this simple tutorial, we will look at how to use the map() function to map values in a series to another set of values, both using a custom function and using a mapping from a Python dictionary.
#### Prerequisites
- jupyter notebook,
- the eCommerce dataset,
- python.

#### The Datasets
The dataframe consist of 91,472 entries, with 34 columns. The dataframe is stored in as a pickle file to speed up the storage/retrival and use i.e. merging the datasets into a larger dataset without memory utilization issues.

#### Technology 
Anaconda 

#### Required packages
Numpy, Pandas, Datetime, and Pickle for memory utilization when handling large files without memory utilization issues.

#### Outcome
- Duplicate data were removed keeping the first of the duplicate records,
- Dates were converted to datetime objects, 
- Empty or missing values were filled out based on value of the records in another column using the`.map()` function. 
#### Status:
- complete.
