## MALL CUSTOMER SEGREGATION

![alt text](https://asaransom.com/wp-content/uploads/2018/12/shopping-in-east-aurora-ny-1500x609.jpg "Localities Explore")


* It is very important for a business to identify its customers and target the right one of them to improve the business.
* I have used a dataset from kaggle which has details of about 200 customers from a mall.
* Details include
    * Age
    * Gender
    * Annual Income
    * Spending score
    * Customer ID
    
* Our aim is to design a model which can segregate for us the customers based on various features of our dataset so that the shop owners are able to form strategies to 
boost their sales by targeting the appropriate customers.

## RESOURCES USED
* Programming language - Python
* Tools used - Google colab
* Dataset - https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python
* Algorithm used - KMeans
* Modules used - Pandas, Matplotlib, Seaborn, Sklearn

## ABOUT THE DATASET
* The dataset contains 5 features about the customers and 200 observations.
* The features include Age, Gender, Annual Income, Spending Scores and Customer Id.

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/Columns.PNG "Localities Explore")



* The dataset contains no null values.

## EXPLORATORY DATA ANALYSIS
* The gender distribution is observed

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/Gender%20distribution.PNG "Localities Explore")



* The age distribution is observed among the customers of all genders

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/Age%20distribution.PNG "Localities Explore")



* Comparison between number of male and female customers in the all the ages is oberved.

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/Gender%20wise%20age%20comparison.PNG "Localities Explore")



* Line plot is observed to get the number of clusters that can be used to get the appropriate segregation of the customers.

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/Lineplot%20elbow.PNG "Localities Explore")



## MODEL DEVELOPMENT
* Since from the line plot above, it is observed that 3 and 4 are the number of clusters that can segregate the customers appropriately for further analysis, we train a model for the same
and plot the clusters in a scatter plot  for observation.

* Scatter plot for 3 clusters.

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/3%20clusters.png "Localities Explore")



* Scatter plot for 4 clusters.

![alt text](https://github.com/Rahul-Khairnar/Mall_Customer_Segmentation/blob/master/PHOTOS/4%20clusters.png "Localities Explore")
