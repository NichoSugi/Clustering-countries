# Clustering-Countries
Malnutrition is a complex issue. Using Unsupervised Learning and clustering techniques in machine learning helps identify patterns in nutritional data, making strategies more targeted and efficient.

# Data Explanation
Malnutrition is a complex issue. Using Unsupervised Learning and clustering techniques in machine learning helps identify patterns in nutritional data, making strategies more targeted and efficient.

# Data Description
8 variables: Country, Income Classification, Severe Wasting, Wasting, Underweight, Overweight, Stunting, and Under 5 y/o Population.

# Data Understanding
Outliers are spotted in some variables using boxplots. However, I've chosen not to remove them because they represent real aspects of the data. This decision helps keep the dataset genuine, preserving its natural variety and details, providing a more accurate picture of what's really happening.

# Data Preparation
In data preprocessing, missing values are replaced with the median of the respective variable for robust and statistically sound datasets. MinMaxScaler is used as the scaling technique to scale the data, chosen when features have different scales.

# ML MODEL
While using the elbow method to find the best number of clusters (k), I noticed some uncertainty at k equals 3 and k equals 6. I decided on k equals 6 to make the clusters more detailed and specific. This choice helps improve cluster analysis, considering the complexities in the data, compared to the alternative k value of 3.

# Evaluation
The interactive result of the clustering modelis available on the ipynb. You can drag the mouse over the dots, and it will show the cluster of each dot. Principal Component Analysis (PCA) is used to reduce the dimensionality of the dataset. Originally, the dataset has 8 variables, which are reduced using PCA to create a 2D visualization.

# PERSONA ANALYSIS
Cluster 0: Urban populations in developing countries where they face some nutrition issues but not extreme.
Cluster 1: Low-income countries struggling with severe malnutrition.
Cluster 2: High-income countries that can provide a balanced diet for their people.
Cluster 3: Developing countries striving to improve health indicators.
Cluster 4: Middle-upper income countries dealing with moderate malnutrition rates.
Cluster 5: Countries facing multiple challenges due to the mix of income classifications.

# CONCLUSION
In summary, my approach involved initial steps of data understanding and preparation to optimize the model. I determined the most suitable value for K using the elbow method, followed by evaluating the silhouette score for each K. Once the model was established, I transformed the clustered values into an interactive 2D scatter plot. This dynamic plot allows users to explore clusters by dragging the mouse over data points, revealing the cluster and the coordinates of principal components 1 and 2. Following the visualization, I conducted a persona analysis, a crucial step in understanding what each cluster represents. By performing persona analysis, I unveiled insights into the characteristics defining each cluster, shedding light on the factors influencing the model's clustering decisions. This in-depth understanding enhances the interpretability and practical application of the clustering results.
