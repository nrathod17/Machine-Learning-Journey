# Machine Learning Unsupervised Learning Journey: From Clustering to Manifold Learning

## 📌 Overview

This repository documents my structured journey into **Unsupervised Machine Learning**, focusing on discovering hidden patterns, grouping similar observations, and reducing the complexity of high-dimensional datasets without relying on labelled data.

The notebooks follow a progressive learning approach — beginning with centroid-based clustering, expanding into alternative clustering algorithms, introducing dimensionality reduction, and concluding with advanced non-linear embedding techniques used for data exploration and visualisation.

Each notebook builds upon the previous one while following a consistent machine learning workflow:

* Data preparation
* Feature scaling
* Synthetic data generation
* Clustering analysis
* Dimensionality reduction
* Data visualisation
* Algorithm comparison
* Business interpretation

The projects are centred around synthetic advertising and marketing datasets designed to simulate real-world business scenarios where customer groups and campaign behaviour must be discovered rather than predicted.

---

# 🎯 Business Context

Working in the advertising industry, I wanted to understand how Unsupervised Machine Learning can uncover meaningful insights from marketing data without predefined target labels.

The notebooks explore how clustering and dimensionality reduction can support decision-making in areas such as:

* Customer segmentation
* Campaign grouping
* Audience discovery
* Behaviour analysis
* Marketing optimisation
* Feature reduction for large datasets
* Data exploration and visualisation

Synthetic datasets provide full control over:

* Feature generation
* Cluster structure
* Noise introduction
* Outlier detection
* Algorithm behaviour
* Business scenario simulation

---

# 📚 Notebook Roadmap

## Notebook 1 — Centroid-Based Clustering: K-Means

### Objective

Build a strong foundation in clustering by understanding how K-Means partitions observations into meaningful groups.

### Topics Covered

* Unsupervised learning fundamentals
* Synthetic data generation
* make_blobs
* K-Means
* K-Means++
* Cluster centroids
* Euclidean distance
* Inertia
* Distortion
* Elbow Method
* Silhouette Score
* Cluster visualisation
* Feature scaling
* Image clustering
* Image compression
* Gaussian Mixture Models (Introduction)
* Hard vs Soft Clustering
* K-Means vs GMM

### Key Learning

Understanding how similarity and distance can be used to discover natural groupings within data and how cluster quality can be evaluated.

---

# Notebook 2 — Beyond K-Means: Hierarchical & Alternative Clustering Algorithms

### Objective

Explore clustering techniques capable of handling different data structures beyond spherical clusters.

### Topics Covered

* Distance Matrix
* Agglomerative Hierarchical Clustering
* Single Linkage
* Complete Linkage
* Average Linkage
* Ward Linkage
* Dendrogram
* Cluster hierarchy
* DBSCAN
* Density-based clustering
* Mean Shift
* Noise detection
* Cluster profiling
* Silhouette Score
* Business cluster interpretation
* Clustering algorithm comparison

### Key Learning

Understanding that different clustering algorithms make different assumptions about data structure and no single clustering technique performs best for every problem.

---

# Notebook 3 — Dimensionality Reduction

### Objective

Reduce feature complexity while preserving the most informative structure within the data.

### Topics Covered

* Curse of Dimensionality
* Principal Component Analysis (PCA)
* Principal Components
* Explained Variance Ratio
* Cumulative Explained Variance
* Feature loadings
* PCA visualisation
* 2D Projection
* 3D Projection
* K-Means before vs after PCA
* Singular Value Decomposition (SVD)
* Truncated SVD
* Image compression
* Image reconstruction
* PCA vs Truncated SVD

### Key Learning

Understanding how dimensionality reduction simplifies high-dimensional datasets while retaining the majority of useful information for analysis and modelling.

---

# Notebook 4 — Advanced Non-Linear Embedding & Manifold Learning

### Objective

Explore advanced techniques that uncover complex non-linear structures hidden within high-dimensional datasets.

### Topics Covered

* Linear vs Non-Linear Dimensionality Reduction
* Manifold Learning
* Nearest Neighbours
* Isomap
* Locally Linear Embedding (LLE)
* Modified LLE
* Hessian LLE
* Spectral Embedding
* t-SNE
* UMAP (Optional)
* Embedding comparison
* Runtime comparison
* Visualisation of high-dimensional data
* Algorithm selection

### Key Learning

Understanding how manifold learning preserves local neighbourhood structures to reveal hidden patterns that cannot be captured by linear dimensionality reduction techniques.

---

# 🛠️ Technologies Used

## Programming

* Python

## Libraries

* NumPy
* Pandas
* Matplotlib
* SciPy
* Scikit-learn

## Machine Learning Techniques

* Clustering
* Cluster evaluation
* Distance metrics
* Feature scaling
* Dimensionality reduction
* Principal Component Analysis
* Singular Value Decomposition
* Density-based learning
* Hierarchical clustering
* Manifold learning
* Data visualisation

---

# 📂 Repository Structure

```text
Machine-Learning-Unsupervised-Learning/

│
├── Notebook_1_KMeans Clustering.ipynb
│
├── Notebook_2_Hierarchical Clustering & Alternative Clustering Algorithms.ipynb
│
├── Notebook_3_Dimensionality Reduction.ipynb
│
├── Notebook_4_Advanced Non-Linear Embeddings & Manifold Learning.ipynb
│
└── README.md
```

---

# 📈 Learning Progression

The progression follows increasing algorithm complexity and abstraction:

```text
K-Means Clustering
        ↓
Alternative Clustering Algorithms
        ↓
Dimensionality Reduction
        ↓
Advanced Manifold Learning
```

Each notebook introduces a different approach to discovering structure within unlabelled data:

| Technique                          | Learning Approach                      |
| ---------------------------------- | -------------------------------------- |
| K-Means                            | Centroid-based clustering              |
| Hierarchical / DBSCAN / Mean Shift | Alternative clustering strategies      |
| PCA / SVD                          | Linear dimensionality reduction        |
| Manifold Learning                  | Non-linear embedding and visualisation |

---

# 🚀 Future Development

Planned extensions:

* Anomaly Detection

  * Isolation Forest
  * Local Outlier Factor
  * One-Class SVM

* Recommendation Systems

  * Collaborative Filtering
  * Matrix Factorisation

* Topic Modelling

  * Latent Dirichlet Allocation (LDA)
  * Non-negative Matrix Factorisation (NMF)

* Advanced Representation Learning

  * Autoencoders
  * Variational Autoencoders (VAE)
  * Self-Supervised Learning

* End-to-end Customer Segmentation Project

---

# 📌 Final Reflection

This repository represents my progression from learning individual clustering algorithms to understanding how unsupervised learning discovers hidden structure within data.

The focus extends beyond applying algorithms to understanding:

* Why each technique works
* When it should be used
* Its assumptions and limitations
* How to evaluate clustering quality
* How to interpret results in a business context
* How dimensionality influences machine learning performance

Unsupervised Learning is not about predicting known outcomes—it is about uncovering meaningful patterns, simplifying complex data, and generating insights that support better exploration, understanding, and decision-making.