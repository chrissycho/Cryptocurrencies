# Chrissy Cho's Cryptocurrencies
### Table of Contents
[ 1. Project Overview ](#desc)<br /> 
[ 2. Resources ](#resc)<br /> 
[ 3. Objectives ](#obj)<br /> 
[ 4. Challenge Overview ](#chal)<br /> 
[ 5. Challenge Objective ](#chalsum)<br /> 
[ 6. Final Thoughts ](#find)<br />


<a name="desc"></a>
## Project Overview
In this module, we've learned how unsupervised learning algorithms works and what types there are to cluster groups. 

<a name="resc"></a>
## Resources
- Data Source: [challenge_data](https://github.com/chrissycho/Cryptocurrencies/tree/master/challenge)
- Software: Jupyter Notebook, Python3 

<a name="obj"></a>
## Objectives
- Describe the differences between supervised and unsupervised learning, including real-world examples of each.
- Preprocess data for unsupervised learning.
- Cluster data using the K-means algorithm.
- Determine the best amount of centroids for K-means using the elbow curve.
- Use PCA to limit features and speed up the model.

<a name="chal"></a>
## Challenge Overview
In this challenge, we've completed preprocessing cryptocurrency data by data selecting, data processing (removing rows with null values, removing unnecessary columns, etc.), data transforming, and training the unsupervised learning with K-means and PCA. 

<a name="chalsum"></a>
## Challenge Objective
- Prepare the data for dimensions reduction with PCA and clustering using K-means.
- Reduce data dimensions using PCA algorithms from sklearn.
- Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
- Create some plots and data tables to present your results.

<a name="find"></a>
## Final Thoughts
After preprocessing data, the data was standardized with StandardScaler method from  sklearn library. Once the data was scaled, the data was reduced down to 3 features using PCA. Then, the elbow curve was created to find out a number of clusters of the data, which shows the elbow curve at K = 4. With a new DataFrame, a 2D and 3D graphs were created to show how the data points look like in clusters. 