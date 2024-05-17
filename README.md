# Credit Card Customer Segmentation

This project implements a customer segmentation strategy using **Principal Component Analysis** (PCA) for dimensionality reduction and **K-Means Clustering** to identify distinct customer groups. I dataset, that this project is based on, is in Kaggle and can be found [here](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m).

The dataset was originally designed for Customer Churn/Attrition, but I filtered out irrelevant columns and kept the columns that could be applied to this project. After cleaning the dataset, I plotted the variation in customer Ages and plotted the amount of Male vs Female customers.

After using **PCA** for dimensionality reduction, and constructing the **Scree Plot**, I realized 2 dimensions wasn't good enough (not enough variation for my liking) for constructing the PCA plot. So I decided to swith to 3 dimensions and display it that way. I also made 6 related 2D plots to complement the 3D plot.

I knew how **K-Means Clustering** and **PCA** worked in theory. And although I don't yet know how to properly read PCA plots. After this project, I gained practical experience with **K-Means Clustering** and **PCA**, plus I learned *even more* features of the Matplotlib module.