# Mall Customer Segmentation using Custom K-Means

A Python-based machine learning project that implements the **K-Means Clustering** algorithm from scratch to segment retail mall customers based on their **Age** and **Spending Score**. 

This project demonstrates how businesses use unsupervised learning to automatically identify target audiences and customer profiles without prior labeling.

---

## 🚀 How It Works

The project builds the K-Means algorithm step-by-step using only `NumPy` and `Matplotlib`:
1. **Data Generation**: Uses `scikit-learn`'s `make_blobs` to generate synthetic customer data.
2. **Data Scaling**: Interpolates the data to fit realistic real-world ranges (Age: 18-70, Spending Score: 1-100).
3. **Initialization**: Randomly selects $k=3$ initial customer data points as starting centroids.
4. **Assignment Loop**: Uses **Euclidean distance** to assign each customer to their closest cluster center.
5. **Update Loop**: Recalculates the cluster centers by averaging the locations of all assigned points until the centroids stabilize.

---

## 📊 Customer Segments Identified

Running this algorithm successfully groups the 200 shoppers into 3 distinct business categories:
* 🎯 **Young High Spenders**: High spending score, younger age demographic. Perfect target for premium and trendy product campaigns.
* 🛍️ **Young Low Spenders**: Younger age demographic but low spending habits.
* 👥 **Mature Conservative Spenders**: Older age demographic with stable, moderate-to-low spending scores. Ideal for loyalty programs and value deals.

---

## 🛠️ Prerequisites & Installation
