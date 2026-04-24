
# 🌍 Global Terrorism Analysis using Machine Learning & Power BI

## Machine Learning Workflow

![Machine Learning Process](https://github.com/satyamlokhande25-maker/United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-/blob/54106c2be0e810b098253b8bada24f9deeea4520/ML-workflow.png)

## 📌 Project Overview

This project presents a comprehensive analysis of global terrorism incidents using unsupervised machine learning and interactive Power BI dashboards. The objective is to discover hidden patterns in terrorism incidents and classify them into severity-based clusters using casualty-related features such as number of people killed and wounded. The project combines data preprocessing, exploratory data analysis, clustering models, evaluation metrics, and dashboard visualization to support data-driven decision making.

---

# 🎯 Business Objective

* Identify severity levels of terrorist incidents
* Detect high-impact attacks and outliers
* Analyze global terrorism trends
* Segment incidents into Low, Medium, and High severity
* Compare multiple clustering algorithms
* Build interactive Power BI dashboard for insights

---

# 📂 Dataset

Global Terrorism Dataset containing the following features:

* Year of incident
* Country
* Region
* Attack type
* Terrorist group
* Number killed (nkill)
* Number wounded (nwound)
* Casualties
* Success rate

---

# 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand terrorism trends and distribution patterns.

### Key Insights

* Terrorist attacks peaked around 2014
* Iraq and Afghanistan were the most affected countries
* Bombing/Explosion was the most common attack type
* Most incidents resulted in low casualties
* High severity incidents are rare but impactful

---

# 🤖 Machine Learning Approach

Unsupervised learning algorithms were applied to identify hidden severity patterns.

## 1️⃣ K-Means Clustering (Best Performing Model)

* Segments incidents into three clusters
* Low Severity Incidents
* Medium Severity Incidents
* High Severity Incidents
* Produces clear and interpretable clusters
* Best visualization performance

## 2️⃣ HDBSCAN Clustering

* Density based clustering algorithm
* Detects noise and outliers
* Creates multiple clusters
* Strong separation but complex interpretation

## 3️⃣ Gaussian Mixture Model (GMM)

* Probabilistic clustering
* Allows overlapping clusters
* Moderate performance
* Less clear separation compared to KMeans

---

# 📊 Model Evaluation Metrics

| Algorithm | Silhouette Score | Davies Bouldin | Calinski Harabasz |
| --------- | ---------------- | -------------- | ----------------- |
| KMeans    | 0.964            | 0.587          | 181691            |
| HDBSCAN   | 0.986            | 0.266          | 1173048           |
| GMM       | 0.580            | 0.900          | 91379             |

---

# 🏆 Best Model Selection

K-Means clustering was selected as the best performing algorithm because:

* Produces clear severity-based clusters
* Easy to interpret results
* Clean visualization
* Balanced cluster distribution
* Suitable for Power BI dashboard
* Better business understanding

---

# 📊 Power BI Dashboard

The Power BI dashboard is divided into two main pages:
![Power Bi DashBoard](https://github.com/satyamlokhande25-maker/United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-/blob/052806512721c6df5f4dd3799bb053341710b010/Powerbi-dashBoard.png)

---

# 📍 Page 1 — EDA Dashboard

### Cards

* Total Incidents
* Total Casualties
* Success Rate
* Attacks per Year
* Affected Countries

### Visualizations

* Attacks per Year (Line Chart)
* Global Attack Map
* Top Countries (Bar Chart)
* Attack Type Distribution (Donut Chart)
* Region-wise Analysis
* Terrorist Group Table


---

# 📍 Page 2 — Machine Learning Dashboard

This page presents clustering results from K-Means model.

### Cards

* Total Incidents
* Low Severity Incidents
* Medium Severity Incidents
* High Severity Incidents
* Average Casualties
* Maximum Casualties



---

# 📈 Machine Learning Insights

* Most incidents fall under low severity cluster
* Medium severity incidents represent moderate impact
* High severity incidents are rare but highly destructive
* Casualty distribution shows extreme outliers
* Clustering clearly separates severity levels

---

# 🛠️ Technologies Used

### Programming

* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-learn
* KMeans
* HDBSCAN
* Gaussian Mixture Model

### Visualization

* Matplotlib
* Seaborn
* Power BI

---

# 🚀 Key Achievement

Developed an end-to-end unsupervised machine learning pipeline and built an interactive Power BI dashboard to analyze terrorism severity patterns and identify high-impact incidents.

---

# 📌 Conclusion

K-Means clustering provided the most interpretable and meaningful severity-based clusters compared to HDBSCAN and GMM. The model effectively segmented incidents into Low, Medium, and High severity groups and enabled clear visualization in the Power BI dashboard.

---



