Data Analyst porfolio

# [Project 1: Store Sales Analysis](https://github.com/MrKome/Store_Sales_Analysis)

### Project Overview 

This project walks through the process of conducting in-depth sales analysis on a dataset using NumPy. It covers the intricacies of data handling, including uploading and storing a Sales dataset, and delving into data cleaning and normalisation techniques. 

This project covers concepts like statistical analysis, exploring concepts like mean, median, and standard deviation.

Overview: 

- Upload the csv file into google colab virtual memory
- Read file using NumPy and store it into an array 
- Perform data cleaning
- Perform data normalisation
- Perfom statistical analysis
- Perform sales analysis such as: best selling product, or product category
- Display data and analysis on charts using matplotlib 


### Data Source

The csv file used 'Sales_Numpy.csv' has been added to the repository. 


### Tools 

- Python

### Results/Findings

- Best selling product in January 2023 is Nightgowns
- Best selling category in January 2023 is Accessories
- The overall Average sales: 1502.42
- Average Sales based on product (Nightgowns): 1583.3870967741937


### Scatter plot showing the relationship between Advertisment Expenses and Sales for January 2023
![](./images/SnA%20Plot%201.png)

### Bar chart showing the total sales by Product for January 2023
![](./images/T_sales_by_Product.png)

### Bar chart showing the total sales by Product Category for January 2023
![](./images/T_sales_by_Product_Cat.png)


---


# [Project 2: Displaying Live System Performance using Power BI, SQL and Python ](https://github.com/MrKome/System_info_performance_Monitor)

### Project Overview 

This project Shows the subsequent steps following the development of a new database in Microsoft SQL Server Importing Python system. It covers using Python to get system performance informationand, Testing Application, Connertiing Power BI to SQL Server, Creating Power BI Dashboard and Testing the final results.

### Data Source

Python script is used to read system performance information such as: 
- cpu_usage
- memory_usgae
- cpu_interrupts
- cpu_calls
- memory_used
- memory_free
- bytes_sent
- bytes_received
- disk_usage

### Tools 

- Python, Microsoft SQL Server, Power BI

### Preview of Live Power BI Dashboard

![](./images/Sys_Info_Perf_Mon%20Snapshot.jpg)


---

# [Project 3: Telco Customer Churn Prediction](https://github.com/MrKome/DS_Churn_Project/tree/main)

### Project Overview 

This project aims to predict Telco customer churn and provide insight into the performance of a company. By analysing various aspects of the data, we seek to identify trends and gain an understanding of the company's performance. 

### Data Source

Customer Churn Data: The primary dataset used for this analysis is the "WA_Fn-UseC_-Telco-Customer-Churn" file, containing detailed information about each customer. 

### Tools 

- Python 

### Exploratory Data Analysis

EDA involved exploring the customer churn data to answer key questions, such as: 

- How many people are churning vs how many people are returning?
- What is the percentage of customers that are leaving?
- Can we visualise the churn count for both male and females to see a correlation?
- Can we visualise the churn count for the internet service to see a correlation?

#### We explored the distribution of data and the value count for the both male and females
![](./images/Customer%20Churn%20Count.png)



#### We also looked at the distribution of data and the value count for the internet service
![](./images/Churn%20count%20for%20Internet%20Service.png)


### Data Cleaning

In the intial data preparation phase, we performed the following tasks:

- Data Loading and inspection
- Handling misssing Values
- Data Cleaning and formatting

### Prediction, Training and Testing

- Split the data into training and testing
- Create and train the model 
- Create the predictions on the test data

### Results/Findings

The prediction results are summarised as follows:
- We can see our model has a 91% recall,
- We can see our model has a 85% precsion
- We can see our model has a 88% f1-score
- We can see our model has an accuracy of 81% 
