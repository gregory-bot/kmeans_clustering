# Clustering Analysis: K-Means and DBSCAN

This project demonstrates unsupervised machine learning techniques for clustering using K-Means and DBSCAN algorithms. The analysis is performed on two datasets: `Mall_customers.csv` and `income.csv`.

## Project Structure
- **kmeans.ipynb**: Jupyter notebook implementing K-Means clustering.
- **db scan.ipynb**: Jupyter notebook implementing DBSCAN clustering.
- **Mall_customers.csv**: Dataset for customer segmentation.
- **income.csv**: Dataset for income-based clustering.

## Methods Used
### K-Means Clustering
- Data preprocessing and scaling
- Elbow method for optimal cluster selection
- Visualization of clusters

### DBSCAN Clustering
- Data normalization
- Density-based clustering
- Visualization of clusters

## Results
### K-Means Clustering
Example cluster visualization:

![KMeans Cluster 1](kmeans_plot1.png)
![KMeans Cluster 2](kmeans_plot2.png)
![KMeans Cluster 3](kmeans_plot3.png)
![KMeans Cluster 4](kmeans_plot4.png)

### DBSCAN Clustering
Example cluster visualization:

![DBSCAN Cluster 1](dbscan_plot1.png)
![DBSCAN Cluster 2](dbscan_plot2.png)
![DBSCAN Cluster 3](dbscan_plot3.png)

## How to Run
1. Open the notebooks in Jupyter or VS Code.
2. Run all cells to reproduce the analysis and plots.
3. The generated images will be saved in the workspace and are referenced in this README.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

Install requirements with:
```
pip install pandas numpy matplotlib scikit-learn
```

## Author
- Your Name

---
This project showcases practical clustering techniques for exploratory data analysis and customer segmentation.