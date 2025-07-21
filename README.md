# DSN 8th Place Hackathon 2025 solution (Excellent Store Sales Prediction Challenge)

## Notebook for The Excellent Store Prediction Challenge 
The notebook addresses __`The Excellent Store Sales Prediction Challenge`__ on Zindi. It covers the fundamental steps of loading the dataset, performing Exploratory Data Analysis (EDA), preprocessing the data, and building a baseline machine learning model to predict sales returns. This submission serves as a foundational approach to the competition.


## Store Sales Dataset Variable Descriptions
The dataset includes 13 variables, consisting of 5 numeric variables and 8 categorical variables. Below are the definitions and descriptions of each variable:

| Variable Name         | Type        | Description                                                                                                                              |
| :-------------------- | :---------- | :--------------------------------------------------------------------------------------------------------------------------------------- |
| **Item_ID** | Categorical | Unique product ID.                                                                                                                       |
| **Item_Weight** | Numeric     | Weight of the product.                                                                                                                   |
| **Item_Sugar_Content**| Categorical | Sugar content of the product.                                                                                                            |
| **Item_Visibility** | Numeric     | The percentage of total display area of all products in Chief Babatunji’s supermarket allocated to the particular product.                 |
| **Item_Type** | Categorical | The category to which the product belongs.                                                                                               |
| **Item_Price** | Numeric     | Retail price of the product.                                                                                                             |
| **Store_ID** | Categorical | Unique store ID.                                                                                                                         |
| **Store_Start_Year** | Numeric     | The year in which store was opened.                                                                                                      |
| **Store_Size** | Categorical | The size of the store in terms of total ground area covered.                                                                             |
| **Store_Location_Type**| Categorical | The type of city in which the store is located.                                                                                          |
| **Store_Type** | Categorical | Description of the store based on category of items sold.                                                                                |
| **Item_Store_ID** | Categorical | Unique identifier of each product type per supermarket.                                                                                  |
| **Item_Store_Returns**| Numeric     | Profit returns on the product in the particular store. This is the outcome variable to be predicted.                                     |
