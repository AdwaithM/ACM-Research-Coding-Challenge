## Author:    Adwaith Moothezhath Rajesh
## NetID:	   Axm180043
## Date:       9/9/2020
## IDE:   Python Jupyter Notebook
##ACMCoding.ipynb- Python Program that uses the K-Means Clustering alogrithm to determine the number of clusters
***********************************************************************************************************/

The libraries I used were pandas to read the raw data csv file, matplotlib.pyplot for plotting the graphs, sklearn.prepeocessing for scaling data using MinMaxScaler,
sklearn.cluster K means for using the KMeans algorithm.

First I read the raw csv file and found the count, mean, std, min and all information about it.
Then I plotted the data as a scatter plot and x axis was V1 and y axis was V2.
I dropped the unamed column with the numbers from 0-149 because I didn't need that column.
Then I scaled the dataset using MinMaxScaler and replot it as a scatter plot.
I used the Elbow method to minimize the WWS (Within-cluster Sum of Square) and found out that optimal k is at 3.
Finally I used the K-Means algorithmn using k = 3 to cluster the dataset. I also found the centroid of the cluster and drew it in the scatter plot.
