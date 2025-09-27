Mall Customer Segmentation using K-Means Clustering

Project Overview

Customer Segmentation is the process of dividing a customer base into distinct groups based on similarities such as age, gender, interests, and spending habits. This helps companies understand their customers better and tailor marketing strategies to each segment, maximizing profit and minimizing risks.

Objective

The goal of this project is to segment customers into different groups based on Age and Annual Income using K-Means Clustering. This helps businesses target each group effectively.

---------------------------------------------

K-Means Algorithm

Choose the number of clusters, k.

Randomly initialize k centroids.

Assign each customer to the closest centroid (based on Euclidean distance).

Recalculate the centroid of each cluster.

Repeat steps 3–4 until cluster assignments stop changing.

--------------------------------------------------

Dataset:

The dataset is taken from Kaggle:
https://www.kaggle.com/nelakurthisudheer/mall-customer-segmentation

It contains 200 customers with the following features:

CustomerID: Unique ID of the customer

Gender: Male or Female

Age: Age of the customer

Annual Income (k$): Income in thousand dollars

Spending Score (1-100): How much the customer spends

--------------------------------------------------

Tech Stack:

Python

pandas (Data handling)

scikit-learn (K-Means clustering)

matplotlib / seaborn (Data visualization)

Streamlit (Interactive UI, optional)

-----------------------------------------------------
How It Works

Load the dataset and explore customer features.

Use K-Means to cluster customers into 3–5 segments.

Visualize the clusters using scatter plots (e.g., Income vs Spending Score).

----------------------------------------------------
Outcome:

Customers are grouped into clusters with similar characteristics.

Businesses can target each cluster with specific marketing strategies.
<img width="1615" height="794" alt="Screenshot 2025-09-28 005539" src="https://github.com/user-attachments/assets/3a906233-7b79-4fe0-9474-c350019ac54d" />
<img width="1660" height="792" alt="Screenshot 2025-09-28 005555" src="https://github.com/user-attachments/assets/c11e06e2-46ac-4652-aaae-608d8f78b09d" />
<img width="1488" height="761" alt="Screenshot 2025-09-28 005608" src="https://github.com/user-attachments/assets/6f8b3e67-a070-4db9-af93-2b817493744c" />




Easy to visualize and interpret, making it ideal for decision-making.

