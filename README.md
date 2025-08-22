# 🚀 K-Means Clustering from Scratch  

This project implements the **K-Means clustering algorithm** entirely from scratch in Python, as part of the CS412 coursework at UIUC. It demonstrates both the **mathematical foundations** of unsupervised learning and its **practical applications** in grouping geospatial and categorical data.  
 
## 📊 Visualization

<img src="https://github.com/user-attachments/assets/c60fc347-d4d1-44a2-a103-eafee46d999c" alt="K-Means Clustering Visualization" width="400"/>


## 📌 Project Overview  

- **Algorithm**: K-Means clustering (no external ML libraries used)  
- **Dataset**: Location and categorical attributes from a real-world dataset (`places.txt`)  
- **Goal**: Partition data points into clusters based on similarity, minimizing intra-cluster variance  
- **Implementation Details**:  
  - Random centroid initialization  
  - Iterative reassignment and centroid update  
  - Convergence detection  
  - Output includes cluster assignments for each data point  


## 🔑 Key Features  

- **Pure Python Implementation** → built entirely from scratch to deeply understand mechanics  
- **Structured Output** → results written to `clusters.txt` for clear visualization of assignments  
- **Educational Value** → demonstrates concepts of distance calculation, iterative optimization, and unsupervised learning in a reproducible way  


## 🧠 Why It Matters  

K-Means is one of the **cornerstones of unsupervised learning**. Understanding it at the code level builds intuition for:  
- Customer segmentation in business intelligence  
- Image compression & pattern recognition  
- Recommender systems and anomaly detection  
- Decision science applications where groups emerge naturally from data

## 📊 Sample Output
```
Point 0 → Cluster 1
Point 1 → Cluster 0
Point 2 → Cluster 2
```
Clusters represent emerging groups in the dataset (e.g., geographic regions or categories with shared attributes).

## 🔮 Future Enhancements

- Implement smarter centroid initialization (K-Means++)

- Visualize clusters using matplotlib / Plotly

- Compare clustering quality with hierarchical and DBSCAN methods

## 🏫 Academic Context

This project was developed as part of CS412: Introduction to Data Mining at UIUC. It reflects both an academic understanding of machine learning principles and practical coding skills that scale to industry applications.
