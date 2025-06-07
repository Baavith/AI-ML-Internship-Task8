# AI-ML-Internship-Task8

# 🧠 Heart Disease Clustering using K-Means

## 📌 Task 8: Clustering with K-Means

This project performs unsupervised clustering on the Heart Disease UCI dataset using the K-Means algorithm. It includes data preprocessing, dimensionality reduction using PCA, and evaluation with the Elbow Method and Silhouette Score.

---

## 📁 Dataset

- **Name:** `heart_disease_uci.csv`
- **Source:** UCI Machine Learning Repository
- **Type:** Medical dataset for heart disease prediction
- **Goal in this task:** Unsupervised clustering (ignores target labels)

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🧪 Steps Performed

### 1. Load & Clean Data
- Dropped irrelevant columns (`id`, `dataset`, `ca`, `thal`, `slope`)
- Encoded categorical columns
- Removed rows with missing target (`num`) values

### 2. Feature Preparation
- Removed target (`num`) column (unsupervised task)
- Handled missing values using `SimpleImputer`
- Scaled features using `StandardScaler`

### 3. Dimensionality Reduction (PCA)
- Reduced data to 2 principal components for visualization

### 4. K-Means Clustering
- Ran K-Means with various `k` values
- Plotted **Elbow Curve** to determine optimal `k`

### 5. Evaluation
- Assigned cluster labels
- Visualized clusters in 2D space (PCA)
- Evaluated using **Silhouette Score**

---

## 📊 Results

- **Optimal K:** 3 (based on Elbow Method)
- **Silhouette Score:** ~0.28–0.35 (approximate, may vary slightly)

---

## 📈 Visualizations

- 📌 Elbow Method Plot (to choose optimal `k`)
- 🎨 PCA Plot of Clusters with Color-Coding
