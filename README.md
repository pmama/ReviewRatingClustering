# ReviewRatingClustering

Thrilled to share my recent work where I delved into a thorough clustering analysis on a review rating dataset 

📊📈. Employing the following clustering models to study behavior patterns and preferences. 

# 🎯Objective:
The objective of this project is to perform cluster analysis on the provided dataset's features, which encompass a wide range of venue types and their associated metrics. By employing advanced clustering techniques, our aim is to uncover distinct groups or clusters within the dataset, where venues with similar characteristics are grouped together. This clustering will facilitate a deeper understanding of patterns, preferences, and trends in venue popularity and satisfaction, enabling more targeted strategies and insights-driven decision-making in various domains such as tourism, urban planning, and customer experience optimization.

# 📌 Clustering Models Utilized:

🧮 **K-means Clustering**: K-means is a partitioning-based clustering algorithm that divides data points into a pre-defined number of clusters. It aims to minimize the variance within clusters by iteratively adjusting cluster centroids. The algorithm assigns data points to the nearest cluster centroid based on distance metrics. The optimal number of clusters (K) is determined using techniques such as the elbow method, which helps find the point where additional clusters yield diminishing returns in terms of variance reduction.

🌳 **Hierarchical Clustering**: Hierarchical clustering creates a tree-like structure of clusters, known as a dendrogram. It's an agglomerative process, where each data point starts as an individual cluster and is iteratively merged into larger clusters based on proximity. The linkage method defines how the distance between clusters is calculated. Hierarchical clustering doesn't require pre-defining the number of clusters and can help visualize different levels of granularity in clustering results.



# 📋 Workflow Highlights:


# 🔍 Data Processing:
 Handled missing values and standardized data using standardization.
# 🛠️ Feature Selection:
 Experimented with various feature combinations to capture diverse aspects of the dataset. 
# 📈 Determining Optimal K:
     ✅ K-means: Leveraged the elbow method by calculating inertia to identify the best number of clusters.
     ✅ Hierarchical: Constructed dendrograms using linkage matrices to pinpoint the optimal cluster count.


# 🏗️ Model Building: 

Constructed clusters with the optimal K value for each technique.


# 📊 Model Evaluation:


 Calculated silhouette scores to quantitatively evaluate the quality of each clustering model.

