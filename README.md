# CAR SALES EXPLORATORY DATA ANALYSIS WITH PYTHON
## Introduction
The analysis done was to compare and correlate manufacturers of cars and other variables that would determine the rate of purchase and the choice of brand to purchase.
The analysis seeks to proffer inference to why some brands are more purchased than others and some factors that would influence the purchase of those products.
The analysis was done using the PYTHON PROGRAMMING LANGUAGE and the jupyter notebook

## Data Sourcing
The dataset was sent to an email from the facilitator Mr Joseph Elijah, the email contains two files; which was the dataset and the other was questions and guide used in analyzing and answering the questions relating to the dataset.

## Data Preprocessing
The code for importing data libraries and file was imputed to prepare the python workspace
Numpy is imputed to work with numbers/integers, Pandas; to work on Series or Dataframe and also to alter data, Matplotlib and Seaborn are used for data visualization
The file was saved in a csv format and was uploaded as such.
And the dataset was displayed as shown below;
![image](https://github.com/user-attachments/assets/fcd2ebb0-7fec-4658-8ba2-6d1e0c15d3a3)

## DATA EXPLORATION
1.	 How many rows and columns are present in the dataset?
 There are 157 rows and 16 columns from the dataset presented above
![image](https://github.com/user-attachments/assets/34e49998-94c9-4d93-a814-665925799c9e)

2. What are the data types of each column? Are the data types for each column
appropriate? If not change the data types of some columns to what they are
supposed to be
Using the “data.dtypes” code, all columns with string values are classified as ‘objects’ and columns with decimals or integers are classified as ‘float’ data types.
![image](https://github.com/user-attachments/assets/7c476337-6a4d-4435-8393-3da17ca4d01e)


## DATA CLEANING
3. Are there any missing values in the dataset? If so, how many and in which
columns? Fill the missing values in the year_resale_value with the average
year_resale_value, then drop all other rows with missing values in the dataset
![image](https://github.com/user-attachments/assets/5191309d-f9f2-435d-890a-c4a2a830b2d2)

Data was cleaned by checking for and counting missing values using the data.isna().sum() and these were replaced by finding the average of the column affected and replacing the null values with them, afterwhich all other rows with missing values were dropped using the data.dropna()

4a. Clean the name of the __year_resale_value column by removing the leading
underscore 
![image](https://github.com/user-attachments/assets/69083a3e-0812-44a0-9574-98cd918adeb7)

4b. Check if the dataset has any duplicates. If there are, drop them
![image](https://github.com/user-attachments/assets/b1dd54c0-1101-4527-9023-31d7134e7572)


## DESCRIPTIVE STATISTICS
5. Do descriptive statistics (mean, median, standard deviation) of
the numerical columns. What do you notice?
![image](https://github.com/user-attachments/assets/70d532d7-6a4e-4a9f-a237-516765687ad5)


## EXPLORATORY DATA ANALYSIS
6. Which manufacturer has the highest and lowest average sales volume?
   
The ‘Manufacturer’ and ‘Sales_in_thousands’ are grouped using the function group_by and the mean is also imputed and idmax()/idmin() is used to determine the highest and lowest sales volume

![image](https://github.com/user-attachments/assets/261cac34-52c4-4081-8ea2-8ec68e2bd024)

![image](https://github.com/user-attachments/assets/2de31de2-72c5-4d74-9334-6c98f06f246b)

7. What is the distribution of car prices in the dataset?

![image](https://github.com/user-attachments/assets/7016438f-143b-44cd-8798-3d11707e13f9)

![image](https://github.com/user-attachments/assets/f6a52647-ac6e-43d6-ac64-e1efd516cbb4)

8. Plot a correlation matrix to see if different numerical variables in the dataset
correlate with each other.

Before plotting the matrix, a code to first create the correlation is imputed
![image](https://github.com/user-attachments/assets/c0b468ec-3897-4d6b-af93-edf6021186fb)

Then the matrix is plotted
![image](https://github.com/user-attachments/assets/6f26b33b-9007-49c7-820c-8ac8846f2f08)


9. Plot the relationship between price and latest launch year.
    
To plot the relationship between price and launch year, the data type of latest launch had to be changed first

![image](https://github.com/user-attachments/assets/c24775b5-6203-448c-96a4-94afab104b27)

![image](https://github.com/user-attachments/assets/d09b8fb5-6d4c-4801-af5f-7e52ddb1fc54)

10. Group cars by manufacturers and analyze their average price and fuel
efficiency.

![image](https://github.com/user-attachments/assets/f2b14ac7-6b8a-4778-87b6-928b5c199f97)

 
11. Can you identify and visualize the most popular car brands?

![image](https://github.com/user-attachments/assets/54c9b80a-5bf7-4154-947d-5f3e14f58e46)

![image](https://github.com/user-attachments/assets/dd61982b-b32f-4c51-b8aa-eb4510256039) 
From the analysis, the F-series from the Ford company is the most popular car brand


12. Which car model has the highest resale value compared to its initial price?

![image](https://github.com/user-attachments/assets/a4bfcfc8-9afe-43ac-a38e-b739b2259d37)

13. Find the top 3 fuel-efficient cars with an engine size above 2.5 liters.
![image](https://github.com/user-attachments/assets/fc7d5d01-f0aa-453c-9d5f-9e56d3bcfd4e)
The top 3 fuel-efficient cars with engine above 2.5 litres are Chevrolet Impala, Chevrolet Monte Carlo and Mercedes-B CLK Coupe


14. Which Lexus model has the highest horsepower?

 ![image](https://github.com/user-attachments/assets/057f0b34-4db8-41e3-bdfc-3b76aa03b39f)

## CONCLUSION
The analysis of this data has provided applicable solutions to business inquiries and it is recommended that measures are taken to implement it. More visualizations tools can also be applied and other advanced analytical tools.

