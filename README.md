# Cluster Analysis of Indonesian Province Based on Household Primary Cooking Fuel Using K-Means

This repository contains a Jupyter Notebook implementing a **cluster analysis** of Indonesian provinces based on the household primary cooking fuel. The analysis uses the **K-Means algorithm** to group provinces with similar characteristics in terms of household energy consumption.

The project is inspired by the research paper:

**S. N. Huda (2017).** *Cluster Analysis of Indonesian Province Based on Household Primary Cooking Fuel Using K-Means.* IOP Conf. Ser.: Mater. Sci. Eng. 185 012016.  
[Link to paper if available]

---

## Project Description

Household cooking fuel is an important indicator of energy usage patterns and socio-economic conditions. This project aims to identify clusters of Indonesian provinces with similar primary cooking fuel usage, providing insights for policy-making and energy planning.

The workflow includes:

1. **Data Loading and Preprocessing**  
   - Loading datasets containing household cooking fuel statistics per province.  
   - Cleaning and standardizing the data for clustering.

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing distributions of fuel types across provinces.  
   - Understanding patterns and trends in household energy usage.

3. **K-Means Clustering**  
   - Applying the K-Means algorithm to group provinces into clusters.  
   - Determining the optimal number of clusters using methods like the Elbow method or Silhouette score.

4. **Results and Visualization**  
   - Visualizing cluster assignments on maps and charts.  
   - Interpreting the meaning of each cluster based on fuel usage patterns.

---

## Requirements

- Python 3.x  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
