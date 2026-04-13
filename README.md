# United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-
This project applies K-Means clustering on Global Terrorism dataset to identify patterns in terrorist incidents.
## Algorithms Used
- K-Means Clustering
- StandardScaler

## Evaluation Metrics
- Silhouette Score
- Davies Bouldin Score
- Calinski Harabasz Score

## Results
Clusters grouped into:
- Low severity
- Medium severity
- High severity

Silhouette Score: 0.9642  
Davies Bouldin Score: 0.5877  
Calinski Harabasz Score: 181691.45
# Global Terrorism Analysis using Unsupervised Learning

## Project Overview
This project applies unsupervised learning techniques on the Global Terrorism dataset to identify hidden patterns in terrorist incidents. K-Means clustering is used to group incidents based on casualties and analyze severity levels.

## Objective
The objective of this project is to use unsupervised learning to discover natural groupings in terrorist incidents and categorize them based on impact and severity.

## Dataset Features Used
- iyear (Year)
- nkill (Number of people killed)
- nwound (Number of people wounded)
- Total casualties (nkill + nwound)

## Algorithm Used
K-Means Clustering was applied to group terrorist incidents into clusters based on similarity in casualties.

## Data Preprocessing
- Selected relevant features
- Handled missing values
- Created total casualties feature
- Applied StandardScaler for normalization

## Clustering Result
The K-Means algorithm grouped incidents into three severity levels:
- Low Severity Incidents
- Medium Severity Incidents
- High Severity Incidents

## Model Evaluation
The clustering performance was evaluated using the following metrics:

- Silhouette Score: 0.9642  
- Davies Bouldin Score: 0.5877  
- Calinski Harabasz Score: 181691.46  

These values indicate that the clusters are well-separated and meaningful.

## Visualization
The following visualizations were created:
- K-Means Cluster Plot (Killed vs Wounded)
- Severity Based Cluster Visualization
- Cluster Evaluation Metrics
  

## Conclusion
Unsupervised learning successfully identified hidden patterns in the dataset. K-Means clustering grouped terrorist incidents into meaningful severity-based clusters. The evaluation metrics confirm that the clustering model performs well and produces clearly separated clusters.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Author
satyam lokhande
