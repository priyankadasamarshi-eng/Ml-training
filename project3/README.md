# Customer Segmentation Using K-Means Clustering

## 📌 Project Overview
This project demonstrates **customer segmentation** using the **K-Means clustering algorithm**.  
The goal is to group customers into distinct segments based on their purchasing behavior, enabling businesses to better understand customers and design targeted marketing strategies.

The notebook focuses on clustering customers using:
- **Annual Income**
- **Spending Score**

## 📊 Dataset
The dataset contains customer-related features, commonly used in market segmentation problems.  
Key features used for clustering:
- **Annual Income**
- **Spending Score**

*(The dataset is assumed to be preprocessed and numeric.)*

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 🔍 Methodology
The project follows these main steps:

### 1. Data Preparation
- Load customer data
- Select relevant numerical features
- Convert data into a suitable NumPy array for clustering

### 2. Choosing the Number of Clusters
- The **Elbow Method** is used to determine the optimal number of clusters (`k`)
- Inertia is plotted against different values of `k`

### 3. Applying K-Means Clustering
- Initialize the K-Means model with the chosen number of clusters
- Fit the model to the customer data
- Assign cluster labels to each customer

### 4. Visualization
- Customers are plotted using **Annual Income vs Spending Score**
- Each cluster is displayed in a different color
- Cluster **centroids** are highlighted for better interpretation

## 📈 Results
- Customers are successfully grouped into meaningful clusters
- Each cluster represents a distinct customer segment
- The visualization clearly shows separation between customer groups

## 📷 Sample Output
The final plot displays:
- Colored clusters representing different customer segments
- Centroids marked to indicate the center of each cluster

## 🚀 How to Run the Project
1. Clone the repository
   ```bash
   git clone <repository-url>
