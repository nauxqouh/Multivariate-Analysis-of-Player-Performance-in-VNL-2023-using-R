# Multivariate-Analysis-of-Player-Performance-in-VNL-2023-using-R

This project was developed as an advanced academic analysis in the field of **multivariate statistics**, utilizing **real-world sports data** sourced from [Kaggle](https://www.kaggle.com/datasets/yeganehbavafa/vnl-men-2023). It demonstrates my ability to apply rigorous statistical thinking and R programming skills to uncover hidden structures within player performance metrics.

Focusing on the 2023 Volleyball Nations League (VNL), the dataset includes match-level performance indicators for 131 professional players across 16 national teams. Technical attributes — including `attack`, `block`, `serve`, `dig`, `set`, and `receive` — are analyzed to extract **latent performance dimensions**, identify **versatile and standout players**, and generate **data-driven insights to support coaching and strategic decisions**.

Key analytical methods include **Principal Component Analysis (PCA)**, **Factor Analysis (FA)**, and **Permutation-based MANOVA**, all implemented in R.

## 🧠 Key Techniques

- **Data Exploration**: Descriptive statistics, correlation matrices, boxplots, and histograms.
- **Principal Component Analysis (PCA)**:  
  - Dimensionality reduction of performance metrics  
  - Interpretation of components as underlying skill dimensions  
  - Visualization of variable contributions and player distribution  
- **K-Means Clustering (on PCA scores)**:  
  - Player segmentation based on performance profiles  
- **Factor Analysis (FA)** with Varimax rotation:  
  - Identification of latent skill factors  
  - Construction of factor-based performance scores  
- **Permutation-based MANOVA**:  
  - Statistical testing of group differences by nationality and age

## 📈 Key Findings

- PCA revealed three interpretable components:
  - **PC1**: Offensive strength (`attack`, `serve`, `block`)
  - **PC2**: Defensive ability (`dig`, `receive`)
  - **PC3**: Tactical coordination (`set`)
- FA supported a similar three-factor structure, explaining over 60% of total variance.
- Clustering identified meaningful player segments, particularly specialized roles such as **Liberos** and **Setters**.
- Players like **Ichikawa Yuki** and **Zhang Jingyin** stood out as all-rounders, excelling across multiple dimensions.

## 🛠 Technologies Used

- **Language**: R  
- **Key Libraries**: `tidyverse`, `ggplot2`, `factoextra`, `corrplot`, `cluster`, `psych`, `vegan`

## 📄 Report

Access the full report with visualizations and statistical interpretations:

👉 [PDF Report](https://github.com/nauxqouh/Multivariate-Analysis-of-Player-Performance-in-VNL-2023-using-R/blob/main/VNL-2023-Player-Performance-Analysis-Report.pdf)

👉 [RPubs Publication](https://rpubs.com/nauxqouh/1334657)

👉 [Kaggle (Coming soon)](#)
