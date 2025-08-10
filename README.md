# Movie-Genre-Clustering-using-K-Means-Unsupervised-Machine-Learning
# 🎬 Movie Genre Clustering with K-Means

This project applies **K-Means clustering** to group movies with similar characteristics, helping to discover potential genre groupings.  
The dataset can be simulated or sourced from a real-world dataset like [MovieLens](https://grouplens.org/datasets/movielens/).

---

## 📌 Project Overview
- **Goal:** Group movies by similarity based on runtime, ratings, and genre tags.
- **Algorithm:** K-Means Clustering (unsupervised learning).
- **Output:** Cluster labels with visualizations showing cluster characteristics.

---

## 📂 Features in Dataset
- **Numerical:**
  - `runtime` (minutes)
  - `rating` (IMDb-like score)
- **Binary genre tags:**
  - `action`
  - `comedy`
  - `drama`
  - `romance`
  - `horror`

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (StandardScaler, KMeans, PCA)

---

## 🚀 Workflow
1. **Data Loading/Simulation**
   - Generate 200 simulated movies with random features.
2. **EDA (Exploratory Data Analysis)**
   - Feature correlation heatmap.
3. **Data Preprocessing**
   - Standardize features using `StandardScaler`.
4. **K-Means Clustering**
   - Apply K-Means with `n_clusters=4`.
   - Assign cluster labels to each movie.
5. **Cluster Profiling**
   - Group by cluster to analyze average feature values.
   - Display results as a heatmap.
6. **Dimensionality Reduction**
   - Use PCA to visualize clusters in 2D.
7. **Visualization**
   - Correlation heatmap.
   - Cluster feature profile heatmap.
   - PCA scatter plot of clusters.

---

## 📊 Example Visualizations
- **Feature Correlation Matrix**
- **Cluster Feature Profiles**
- **Movie Clusters in 2D (PCA)**

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements
- Dataset inspiration: [MovieLens](https://grouplens.org/datasets/movielens/)
- Algorithm: [K-Means Clustering – scikit-learn](https://scikit-learn.org/stable/modules/clustering.html#k-means)
