
# Projects – Unsupervised Machine Learning & Recommendation Systems

## **Overview**

This repository contains multiple AI/ML projects focused on **unsupervised learning, anomaly detection, image clustering, and recommendation systems**. These projects demonstrate practical applications of dimensionality reduction, clustering, association rules, and embeddings for real-world business problems.

---

## **Projects Included**

### **Project 1: Clustering Toy Datasets (Basics)**

* **Dataset:** Synthetic datasets (`make_moons`, `make_circles`, `make_blobs`)
* **Concepts:** K-Means, DBSCAN, feature scaling, silhouette score
* **Goal:** Demonstrate how different clustering algorithms capture non-linear clusters
* **Business Impact:** Understand clustering fundamentals before applying to real-world data

### **Project 2: Customer Segmentation for Retail**

* **Dataset:** Mall Customers Dataset or e-commerce customer data
* **Concepts:** K-Means, PCA for visualization
* **Goal:** Identify customer groups (budget buyers, premium spenders, frequent shoppers)
* **Business Impact:** Targeted marketing and personalized offers

### **Project 3: Document Clustering & Topic Modeling**

* **Dataset:** 20 Newsgroups or scraped news articles
* **Concepts:** TF-IDF, Cosine similarity, K-Means, LDA
* **Goal:** Group documents into topics without labels
* **Business Impact:** Auto-tagging news, blogs, or document archives

### **Project 4: Music/Song Clustering**

* **Dataset:** Spotify Tracks Dataset (Kaggle)
* **Concepts:** Feature scaling, K-Means/Hierarchical clustering
* **Goal:** Cluster songs into genres/moods using acoustic features
* **Business Impact:** Playlist generation and music recommendations

### **Project 5: Image Compression with PCA & Autoencoders**

* **Dataset:** MNIST or Fashion-MNIST images
* **Concepts:** PCA for linear compression, autoencoders for nonlinear reduction
* **Goal:** Reconstruct images using fewer dimensions
* **Business Impact:** Optimizes storage and transmission of image data

### **Project 6: Anomaly Detection in Transactions**

* **Dataset:** Credit Card Fraud Dataset
* **Concepts:** Isolation Forest, One-Class SVM
* **Goal:** Detect unusual/fraudulent transactions
* **Business Impact:** Prevent financial fraud and losses

### **Project 7: Market Basket Analysis (Association Rules)**

* **Dataset:** Groceries or retail transaction data
* **Concepts:** Apriori, FP-Growth, lift & confidence metrics
* **Goal:** Identify patterns like “People who bought X also bought Y”
* **Business Impact:** Recommendation engines and cross-selling

### **Project 8: Visualizing High-Dimensional Data**

* **Dataset:** MNIST handwritten digits or CIFAR-10 images
* **Concepts:** t-SNE, UMAP for 2D visualization
* **Goal:** Visualize clustering of digits/images in latent space
* **Business Impact:** Explore high-dimensional data for AI/ML pipelines

### **Project 9: Image Clustering with Deep Features**(Coming Soon...)

* **Dataset:** CIFAR-10 or Caltech-101 images
* **Concepts:** Pretrained CNN (ResNet) → Extract embeddings → K-Means/DBSCAN
* **Goal:** Cluster images without labels into semantic groups
* **Business Impact:** Auto-tagging and semantic organization of images

### **Project 10: Hybrid Recommendation Engine (Deep Unsupervised)**(Coming Soon...)

* **Dataset:** YouTube Trending Videos / MovieLens
* **Concepts:** Autoencoders + clustering + embeddings
* **Goal:** Build a content-based recommendation engine (group similar users/videos)
* **Business Impact:** Personalization for streaming platforms and e-commerce
---

## **Environment Setup**

### **1. Create Virtual Environment**

```bash
python -m venv myEnv
```

### **2. Activate Virtual Environment**

* **Windows:**

```bash
myEnv\Scripts\activate
```

* **Linux/Mac:**

```bash
source myEnv/bin/activate
```

### **3. Install Dependencies**

```bash
pip install -r requirements.txt
```

---

## **Freezing Requirements**

To capture all packages for reproducibility:

```bash
pip freeze > requirements.txt
```

This creates a `requirements.txt` file listing all installed packages and versions.

To install packages from this file on another machine:

```bash
pip install -r requirements.txt
```

---

## **Folder Structure**

```
AI_ML_Projects/
│
├── Data/Keep All data here
├── Project_1_basic.ipynb
├── Project_2_Customer_Segmentation.ipynb
├── Project_3_Document_Clustering_Topic_Modeling.ipynb
├── Project_4_Music_Clustering.ipynb
├── Project_5_Image_Compression_with_PCA_&_Autoencoders.ipynb
├── Project_6_Anomaly_Detection_in_Transactions.ipynb
├── Project_7_Market_Basket_Analysis.ipynb
├── Project_8_Visualizing_High_Dimensional_Data.ipynb
├── Project_9_Image_Clustering_with_Deep_Features.ipynb
├── Project_10_Hybrid_Recommendation_Engine.ipynb
├── requirements.txt
└── README.md
```

---

## **How to Use**

1. Navigate to the project folder.
2. Run the Jupyter Notebook step-by-step.
3. Analyze results and visualizations for each project.

---
