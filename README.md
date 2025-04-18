# Therapeutics Sales Analysis and Future Projections
A machine learning project aimed at predicting therapeutic sales for future projections using machine learning models. The project processes, analyzes, and visualizes sales data to uncover trends and insights, enabling better decision-making in the healthcare and pharmaceutical industries.

## Table of Contents
- Overview
- Features
- Dataset
- Workflow
- Technologies Used
- Usage
- Results
- Future Work

## Overview
This project focuses on analyzing and predicting sales data of therapeutics. The workflow includes:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA) to visualize trends.
- Grouping and summarizing sales by month and year.
- Visualizing top-selling medicines for each month.

## Features 

- #### Data Cleaning and Transformation:
   
  ◦ Handling missing values.  
  ◦ Dropping unnecessary columns.  
  ◦ Converting dates to appropriate datetime formats.

- #### Exploratory Data Analysis:
    
  ◦ Visualization of null values using heatmaps.  
  ◦ Understanding sales trends over time.
  
- #### Sales Insights:
    
  ◦ Identification of top-selling products by month and year.  
  ◦ Grouped analysis of sales data.

- #### Data Visualization:
    
  ◦ Graphical representation of sales trends and top-selling items.  
## Dataset
The dataset consists of therapeutic sales data with the following columns:

- SALE_INVOICE_NO, ITEM_NAME, ITEM_CODE, ITEM_BATCH, ITEM_SALE_PRICE, QTY_IN_UNITS, TOTAL_COST, INVOICE_DATE, and more.
- Includes sales, inventory, and transactional details.
 
## Workflow
The notebook follows a systematic workflow:

**1. Import Libraries:** Load essential Python libraries like pandas, numpy, matplotlib, and seaborn.  

**2. Load Data:** Read the dataset from an Excel file.  

**3. Data Cleaning:**  
     ◦ Drop unnecessary columns.  
     ◦ Handle missing values.  
     ◦ Convert date columns to proper datetime formats.  
     
**4. EDA:**  
     ◦ Check and visualize null values.  
     ◦ Summarize data using value_counts and group by operations.
     
**5. Data Transformation:**  
     ◦ Extract year and month from dates.  
     ◦ Aggregate sales data by grouping.  
     
**6. Visualization:**   
     ◦ Plot trends for top-selling items by month and year.  
     
## Technologies Used
- **Programming Language:** Python
- **Libraries:**  
    ◦ **Data Handling:** pandas, numpy  
    ◦ **Data Visualization:** matplotlib, seaborn, exploratory data analysis (EDA)  
    ◦ **Datetime Processing:** datetime, calendar

## Usage  
**1. Clone the repository:**  
   ``` git clone https://github.com/abhinay1249/therapeutics-projection.git ```

**2. Install required Python libraries:**  
    ``` pip install pandas numpy matplotlib seaborn ```
    
**3. Open and execute the Project.ipynb notebook:**  
    ◦ Load the dataset by specifying the correct path.  
    ◦ Follow the notebook steps to preprocess and analyze the data.  


    ```markdown
**📌 Key Features**  
&nbsp;&nbsp;&nbsp;&nbsp;1. Data cleaning and preprocessing  
&nbsp;&nbsp;&nbsp;&nbsp;2. Feature engineering  
&nbsp;&nbsp;&nbsp;&nbsp;3. Model training (Linear Regression, Random Forest)  
&nbsp;&nbsp;&nbsp;&nbsp;4. Evaluation using MAE, RMSE  
&nbsp;&nbsp;&nbsp;&nbsp;5. Visualizations with Matplotlib & Seaborn  
```

