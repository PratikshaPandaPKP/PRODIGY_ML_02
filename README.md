Task-02 entails the development of a K-means clustering algorithm to segment customers of a retail store according to their purchase behavior. The process begins with importing essential libraries such as NumPy, pandas, Matplotlib, Seaborn, and warnings to handle any potential issues. The dataset, containing information like customer gender, age, annual income, and spending score, is read into a pandas DataFrame.

Next, exploratory data analysis (EDA) is performed to gain insights into the data distribution and relationships between variables. Various visualizations, including violin plots for age distribution, boxplots for spending score and annual income, and bar plots for gender distribution and customer age groups, are generated.

Following the EDA, the Within-Cluster-Sum-of-Squares (WCSS) metric is computed and visualized for different values of K (number of clusters) to determine the optimal number of clusters for the K-means algorithm. This helps in selecting an appropriate value for K by identifying the "elbow" point in the WCSS plot.

Subsequently, K-means clustering is applied to the dataset with a chosen number of clusters, and the resulting clusters are visualized using scatter plots. Initially, a 2D scatter plot is created to represent clusters based on age and annual income, providing a clear visualization of how customers are grouped.

Moreover, a 3D scatter plot is generated to visualize clusters based on age, annual income, and spending score. This visualization offers a more comprehensive understanding of the customer segments identified by the K-means algorithm.

Overall, the process involves a systematic approach to segmenting customers based on their purchase history using K-means clustering, coupled with insightful visualizations to interpret the clustered data effectively.
