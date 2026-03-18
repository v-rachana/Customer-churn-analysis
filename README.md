## Introduction 

Customer retention is a cornerstone of long-term business success, especially in industries like telecommunications where acquiring new customers incurs high costs. Customer churn—when subscribers cancel or switch to competitors—negatively impacts revenue and increases operational and marketing expenses. Accurately predicting and mitigating churn has become a strategic priority for telecom providers aiming to maintain market share and profitability.

Machine learning (ML) provides powerful tools for identifying at-risk customers, analyzing behavioral trends, and designing targeted retention strategies. This project applies both supervised and unsupervised ML techniques to develop a predictive churn framework and segment customers based on behavior. 
 
Data Source: [Telco Customer Churn Dataset – Kaggle ](https://www.kaggle.com/datasets/alfathterry/telco-customer-churn-11-1-3)

The dataset comprises various customer-level features, including tenure, monthly charges, contract type, and satisfaction score. The project objectives are: 
1. Customer Behavior Analysis: Apply clustering and dimensionality reduction to uncover latent customer segments.
2. Churn Prediction Modeling: Build and evaluate classification models to predict churn likelihood.
3. Business Insight Extraction: Translate predictive insights into actionable retention strategies. 

To accomplish these objectives, the project implements a full ML pipeline including preprocessing, feature engineering, model training, and validation. Dimensionality reduction methods (PCA, t-SNE, UMAP) were used to visualize patterns and support segmentation. Logistic Regression, Random Forest, and XGBoost models were trained for churn prediction, with XGBoost achieving the highest balanced performance. 

## Tools and Libraries 
- Python (scikit-learn, XGBoost, pandas)
- R (tidyverse, caret, ggplot2)
 
1. Python Libraries: 
 
• scikit-learn: For data preprocessing, classification models, and validation procedures. 
• XGBoost: For building and optimizing gradient boosting models. 
• Pandas and NumPy: For data manipulation and numerical computation. 
• Matplotlib and Seaborn: For generating data visualizations and model insights. 
 
2. R Libraries: 
 
• tidyverse, data.table: For data manipulation and wrangling. 
• ggplot2, cowplot, gridExtra: For rich and multi-faceted visualizations. 
• caret, recipes, dplyr, forcats: For data preprocessing, feature engineering, and model tuning. 
• randomForest, gbm, e1071, MASS: For implementing machine learning and statistical models. 
• pROC: For model evaluation using ROC curves. 
• cluster, FactoMineR, factoextra: For clustering analysis and dimensionality reduction. 
• stats: For traditional statistical methods and unsupervised learning. 
 
Computational Environment: All analyses were conducted in a reproducible Python environment (e.g., Jupyter Notebook or Colab), ensuring scalability and easy integration for future enhancements. All analyses were also performed in RStudio using .Rmd files, ensuring reproducibility, integrated documentation, and ease of future extension. 

##  Workflow Summary 
 
The end-to-end methodology included: 
1. Data Preprocessing and Feature Engineering 
2. Dimensionality Reduction for Exploratory Analysis 
3. Clustering for Customer Segmentation 
4. Supervised Model Training and Evaluation 
5. Validation through Cross-Validation and Hyperparameter Tuning
   
This structured pipeline ensures robust churn prediction and actionable insights for effective customer retention strategies.
