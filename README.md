# ACM Research Coding Challenge (Fall 2020)

## No Collaboration Policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed to use Internet documentation. If you _do_ use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Submission Procedure

Please follow the below instructions on how to submit your answers.

1. Create a **public** fork of this repo and name it `ACM-Research-Coding-Challenge`. To fork this repo, click the button on the top right and click the "Fork" button.
2. Clone the fork of the repo to your computer using . `git clone [the URL of your clone]`. You may need to install Git for this (Google it).
3. Complete the Challenge based on the instructions below.
4. Email the link of your repo to research@acmutd.co with the same email you used to submit your application. Be sure to include your name in the email.

## Question One

![Image of Cluster Plot](ClusterPlot.png)
<br/>
Given the following dataset in `ClusterPlot.csv`, determine the number of clusters by using any clustering algorithm. **You're allowed to use any Python library you want to implement this**, just document which ones you used in this README file. Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file.

Solution 
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
