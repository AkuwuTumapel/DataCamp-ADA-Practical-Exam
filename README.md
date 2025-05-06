# DataCamp-ADA-Practical-Exam
My work for DataCamp's Associate Data Analyst timed practical exam. This project aims to clean, filter, and visualize data for a fictional grocery store. Here I was able to apply data cleaning techniques such as null value handling and data standardization.

## Description
FoodYum is a US grocery store chain that sells food items such as baked goods, snacks, and produce. Food costs are rising and FoodYum would like to stock products that cover various price ranges to appeal to a broad range of customers. The overall goal is to understand the range of price for different categories in the catalogue while ensuring that the data is usable by handling missing values and standardizing values in a column.

## Dataset
The dataset given is a table from FoodYum's database, containing various attributes for each product on the catalogue. <br><br>

![image](https://github.com/user-attachments/assets/fc1a68ba-cd15-44fd-bc1c-61940ec7086a)
<p align="center">Figure 1. Data dictionary of the 'products' table columns.</p>

![image](https://github.com/user-attachments/assets/88022f26-c605-46f0-a942-68be4f2af5d5)
<p align="center">Figure 2. Column names of the 'products' table and its criteria.</p>

## Walkthrough

### 1. Find Missing Values
An issue in 2022 caused some entries on the table to have missing values for the 'year_added' column. This step shows how many products were added in the year 2022 as records from that period have missing values. <br><br>

![image](https://github.com/user-attachments/assets/a70a7961-cc8e-4bfd-b912-74fe72bc9ecb)
<p align="center">Figure 3. Task 1 description.</p>

![image](https://github.com/user-attachments/assets/ac68f28c-0c71-40e4-add4-e70affd228ba)
<p align="center">Figure 4. Amount of records with missing values in the 'year_added' column.</p>

### 2. Data Cleaning
Furthermore, the data needs to conform to the set criteria. Asides from missing values in 'year_added', it is also possible for there to be missing or mismatched values in other columns on the table. This step transforms the data to conform with the established criteria earlier. <br><br>

![image](https://github.com/user-attachments/assets/0144d675-95ff-438d-a562-97a1fad706e9)
<p align="center">Figure 5. Task 2 description.</p>

![image](https://github.com/user-attachments/assets/2f465870-7dc7-4b48-bb9d-3f4072c0b6c9)
<p align="center">Figure 6. Data cleaning for various table columns.</p>

![image](https://github.com/user-attachments/assets/a8d0fe26-c9b0-457a-821f-41ade6592521)
<p align="center">Figure 7. Snapshot of the data before cleaning.</p>

![image](https://github.com/user-attachments/assets/2afa072b-550c-4a11-9fe6-b6ba17489333)
<p align="center">Figure 8. Snapshot of the data after cleaning.</p>

### 3. Data Exploration
After data cleaning, the next step is to gain insight regarding the range of prices for FoodYum products. The task is to return the minimum and maximum prices of each product category, and meat and dairy products with more than 10 units sold on average per month. <br><br>

![image](https://github.com/user-attachments/assets/e164440d-9173-4359-ad83-7fb94e4e7e04)
<p align="center">Figure 9. Task 3 description.</p>

![image](https://github.com/user-attachments/assets/82348795-7599-4014-8de3-207f81e2656b)
<p align="center">Figure 10. Returning minimum and maximum prices of rows in 'product_type'.</p>

![image](https://github.com/user-attachments/assets/a93f1222-842c-4e51-bc60-8c837d2dd229)
<p align="center">Figure 11. Task 4 description.</p>

![image](https://github.com/user-attachments/assets/574cf014-c78a-478c-adc4-06d3e4376242)
<p align="center">Figure 12. Returning 'product_id', 'price', and 'average_units_sold' of meat and dairy products with more than 10 units sold on average per month.</p>

## Conclusion
Through this project, I demonstrated my ability to perform comprehensive data cleaning to ensure the dataset was ready. Then I followed by applying SQL queries to explore and gain meaningful insights, particularly on the price range of FoodYum products. Overall, this project highlights my skills in preparing raw data and using SQL for data-driven decision-making.
