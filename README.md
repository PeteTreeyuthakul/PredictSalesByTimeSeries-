# PredictSalesByTimeSeries-
Use time series technic to predict sales. The sales database in 2013-2017 and data for predict is Q1 for 2018. The database has attribute store(1-10 stores), item(1-50 items).

Before running this code, make sure you have the following dependencies installed:

Python 3.x (preferably Python 3.8 or higher)
Libraries:
tensorflow
torch
pandas
numpy
darts (for handle Timeseries data and Model)
sklearn (for Kmean Model)
matplotlib (for visualizing data)
seaborn (for visualizing data)
json (for handling structured data)

How to Run the Code
1. Set up your environment:
First, make sure you have installed all the required dependencies (as mentioned above).
2. Use Listings Data:
The application expects a list of dataset, which can be tranform to timeseries dataset.
3. Input Number of Clusters:
Input number of clusters that identify by Elbow Method, this example is 2.
![image](https://github.com/user-attachments/assets/3bc9d049-9884-4793-b3c9-924ed5a52833)
5. Data Preparation step:
Find missing value and outliers by IQR Method. Find correlation between column item and store.
![image](https://github.com/user-attachments/assets/b77dafbb-3c63-46fe-92de-14815cc1f33b)
6. Tuning Model TFT and NBeats: Evalute and tuning model.
   ![image](https://github.com/user-attachments/assets/4bc2db0e-0122-4185-97a2-b9755487678e)
