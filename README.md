# Credit Card Fraud Detection Using Autoencoder and t-SNE
## Overview
This project aims to detect credit card fraud by utilizing Autoencoder (AE) for feature extraction and t-distributed Stochastic Neighbor Embedding (t-SNE) for visualizing high-dimensional data. The dataset consists of credit card transactions, with the goal of identifying fraudulent activities. The Autoencoder helps in learning an efficient representation of the data, while t-SNE provides a means of visualizing the data in a more interpretable way. The project includes data preprocessing, model development, and visualization techniques to enhance fraud detection accuracy.

## Abstract
Detecting credit card fraud accurately is vital for maintaining financial security. In this study, Autoencoder (AE) is employed for feature extraction, and t-SNE is used to visualize the high-dimensional data for identifying fraudulent transactions. The project focuses on data preprocessing, model development, and visualization strategies to improve fraud detection performance, offering valuable insights into feature representation and anomaly detection.

## Objectives
- Data Preprocessing: Clean and prepare the credit card transaction data for model training.
- Feature Extraction: Utilize Autoencoder to derive meaningful features from the data.
- Visualization: Apply t-SNE to reduce the dimensionality of features and visualize them for easier interpretation.
- Fraud Detection: Use the features obtained from the Autoencoder to accurately detect fraudulent transactions.
  
## Methodology
- Data Processing:
Preprocess the transaction data by handling missing values, normalizing features, and addressing any imbalances in the dataset.
- Autoencoder for Feature Extraction:
Implement an Autoencoder to learn a compressed version of the transaction data, preserving important patterns and removing noise.
- t-SNE Visualization:
Apply t-SNE to project the high-dimensional data into a 2D or 3D space, which helps in visually distinguishing between fraudulent and legitimate transactions.
- Fraud Detection:
Utilize the extracted features from the Autoencoder to classify transactions as legitimate or fraudulent, thus improving detection accuracy.

## Results
The project demonstrates the efficacy of Autoencoder for feature extraction and t-SNE for visualizing credit card transaction data in detecting fraud. It provides insights into how the features relate to fraud, helping to distinguish between legitimate and fraudulent transactions effectively.

## Conclusion
By combining Autoencoder for feature extraction with t-SNE for visualization, this approach significantly enhances credit card fraud detection. This study contributes to improving both the accuracy and interpretability of fraud detection systems, making them more applicable to real-world financial security needs. The integration of these techniques offers a deeper understanding of the data, which aids in the effective identification of fraudulent activities.
