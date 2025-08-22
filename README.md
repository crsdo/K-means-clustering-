# 🚀 K-Means Clustering from Scratch  

This project implements the **K-Means clustering algorithm** entirely from scratch in Python, as part of the CS412 coursework at UIUC. It demonstrates both the **mathematical foundations** of unsupervised learning and its **practical applications** in grouping geospatial and categorical data.  
 

---
## 📊 Visualization

Here’s an example of how K-Means partitions data into distinct groups:

![K-Means Clustering Visualization](kmeans_visualization.png)


## 📌 Project Overview  

- **Algorithm**: K-Means clustering (no external ML libraries used)  
- **Dataset**: Location and categorical attributes from a real-world dataset (`places.txt`)  
- **Goal**: Partition data points into clusters based on similarity, minimizing intra-cluster variance  
- **Implementation Details**:  
  - Random centroid initialization  
  - Iterative reassignment and centroid update  
  - Convergence detection  
  - Output includes cluster assignments for each data point  

---

## 🔑 Key Features  

- **Pure Python Implementation** → built entirely from scratch to deeply understand mechanics  
- **Structured Output** → results written to `clusters.txt` for clear visualization of assignments  
- **Educational Value** → demonstrates concepts of distance calculation, iterative optimization, and unsupervised learning in a reproducible way  

---

## 🧠 Why It Matters  

K-Means is one of the **cornerstones of unsupervised learning**. Understanding it at the code level builds intuition for:  
- Customer segmentation in business intelligence  
- Image compression & pattern recognition  
- Recommender systems and anomaly detection  
- Decision science applications where groups emerge naturally from data  

---

## ⚙️ How to Run  

1. Clone this repo:  
   ```bash
   git clone https://github.com/<your-username>/kmeans-from-scratch.git
   cd kmeans-from-scratch
