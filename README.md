So this is the first task of my internship.
Data Cleaning in the file [Data_cleaning.ipynb]
I have chosen one of the csv file mentioned,[netflix_titles.csv] from Kaggle.
At first using Pandas, I have read file. There were some null values specially in catagorical data. 
I use seaborn to visualize the null values.
The maximum amount of null values were present in catagorical datas, which is not possible to replace with any assumption(We can't replace director's name with mean value or any other).
So better we drop the null values.
In the 'date_added' column, the format was like example september 21, 2021. We don't want that . So we change the format to 21-09-2021. And also change the datatype from object to datetime64.
Finally we save all updates to a new csv file ([after_clearing_file.csv])
