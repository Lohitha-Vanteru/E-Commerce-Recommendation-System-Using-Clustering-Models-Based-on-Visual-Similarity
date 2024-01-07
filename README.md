# Clothing Image Recommender System

## Overview
This project focuses on enhancing e-commerce recommendation systems by introducing a machine learning-based approach to fashion product recommendations using a dataset of over 5000 high-definition clothing images.

## Objective
Implement a recommendation system based on machine learning and clustering algorithms to provide users with similar fashion product suggestions.

## Methodology
![image](https://github.com/Lohitha-Vanteru/E-Commerce-Recommendation-System-Using-Clustering-Models-Based-on-Visual-Similarity/assets/113141006/d9804b86-7eb6-449f-a26e-05044d3e2643)

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework. The primary steps include data collection, preprocessing, labeling, and clustering using machine learning techniques.

## Data Collection
- **Source:** Crowdsourced from social networks and collaboration platforms (Toloka and Tagios).
- **Size:** 7.07 GB with over 5000 images.
- **Dataset:** [Clothing Dataset on Kaggle](https://www.kaggle.com/datasets/agrigorev/clothing-dataset-full)
- **CSV File:** `images.csv` contains additional information about the images.

## Preprocessing
- Normalization of data and dropping unnecessary columns.
- Analysis for duplicates, nulls, corrupted images, and class imbalance.
- Data augmentation techniques: Image Random Rotation and Image Flipping.

## Dimensionality Reduction
- Applied Principal Component Analysis (PCA) with Singular Value Decomposition (SVD) for high-dimensional data.
- Aimed at extracting principal features with maximum variance.

## Clustering Algorithms
- Utilized unsupervised clustering algorithms: K-means++, Minibatch, Birch, and Agglomerative.
- Evaluation metrics: Silhouette coefficient, Calinski-Harabasz index, and Davies-Bouldin index.

## Results
![image](https://github.com/Lohitha-Vanteru/E-Commerce-Recommendation-System-Using-Clustering-Models-Based-on-Visual-Similarity/assets/113141006/e33c8daf-6636-42aa-8d15-cbe106275ccc)

- BIRCH model achieved a Silhouette coefficient of 0.672, Davies-Bouldin index of 0.321, and Calinski-Harabasz index of 1075.56 at an optimal number of clusters (5).

## License
This project is licensed under the [MIT License](LICENSE).

