CA06 contains the code for customer segmentation K-Means clustering, the Python Notebook contains 5 tasks mainly include data analysis (EDA), data clustering preparation, determin the optimal number of clustering, and visualize and analysis of clusters.

The 'all_Customers.csv' dataset being used is provided here with link: https://github.com/ArinB/MSBA-CA-Data/raw/main/CA06/Mall_Customers.csv

TASK 1:
The original dataset has 200 rows of data records with 5 columns: CustomerID, Genre, Age, Annual Income (k$), and Spending Score (1-100). There are no missing vallues after checking each columns. The visulization was performed for both numerical column and categorical columns in the form of box plots and histogram plot. Age, annual income, and spending score have 1 or 2 outliers in each data records. 

TASK 2:
For preparing the data for clustering, the required features were selected from the dataset for clustering, and the scaled features were used for creating a new dataset for the later use. 

TASK 3:
Implementing K means clustring required to determin the optimal number of clusters for the model by using silhouette function, a list of range from 2 to 10 numbers of clusters was created. Using for loop to adjust the range in to k means function with random state equals to 101, and fit the new created data into the k means model for finding optimal number of 5 through visualizing the score within the range. set the n_clusters equal to 5 and random state the same, 101, the k means model was successfully built by using the optimal number of clusters, and at the end obtainning the clusters for each data point may help the later visualization process.

TASK 4:
for the section of visualize and analyze the clusters, the scatter plot was created base on the clustered features in the new data set. Setting annual income at the x axis and spending score at y axis for a clear view of each cluster. Using describe function to check the basic statistic of the clusters, and also using groupby function of to get the mean of the selected features clusters. based on the result, We can tell there are 5 sets of clusters for the 2 selected features, annual income and speding score. The information above shows the mean for each cluster under different features, 3 of the mean number of clusters under annual income are negative, and same for spending score.

TASK 5:
Conclusion
