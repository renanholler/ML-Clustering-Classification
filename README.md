<div>
  <image src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <image src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
</div>

# ML-Clustering-Classification

The task consists of applying clustering and classification techniques to fruits based on a dataset provided by the fictional company **Grupo Flora**, which specializes in fruit exports.

## Project Description

The main goal of this task was to use clustering and classification techniques to analyze a fruit dataset:

1. **Fruit Clustering**: Using a clustering algorithm to group fruits based on their characteristics.
2. **Fruit Classification**: Training a classification model using the groups formed by the clustering algorithm as one of the features.

## Methodology

### Clustering

For clustering, the **K-Means** algorithm was used, as it is a widely known and efficient method for partitioning data into *k* groups based on shared characteristics. The number of clusters was determined using the **Elbow Method**.

### Classification

After clustering, the **Random Forest** algorithm was used to classify the fruits. The model was trained using the generated cluster labels as one of the input features, in addition to the original fruit features.

### Evaluation

Model evaluation was performed using metrics such as **accuracy, precision, recall, and F1-score** to measure classification performance. For clustering, metrics such as **inertia** (for K-Means) and the **silhouette score** were used to assess the quality of the clusters.
