# -Data_Analysis--Covid-19_Dataset

The commands that we used in this project :

import pandas as pd -- To import Pandas library
pd.read_csv - To import the CSV file in Jupyter notebook
df.count() - It counts the no. of non-null values of each column.
df.isnull().sum() - It detects the missing values from the dataframe.
import seaborn as sns - To import the Seaborn library.
import matplotlib.pyplot as plt - To import the Matplotlib library.
sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
plt.show() - To show the plot.
df.groupby(‘Col_name’) - To form groups of all unique values of the column.
df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.     
df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.

.......................................................................

Q. 1) Show the number of Confirmed, Deaths and Recovered cases in each Region.
Q. 2) Remove all the records where the Confirmed Cases is Less Than 10.
Q. 3) In which Region, maximum number of Confirmed cases were recorded ?
Q. 4) In which Region, minimum number of Deaths cases were recorded ?
Q. 5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020 ?
Q. 6-A ) Sort the entire data wrt No. of Confirmed cases in ascending order.
Q. 6-B ) Sort the entire data wrt No. of Recovered cases in descending order.
