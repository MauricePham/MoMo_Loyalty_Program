# MoMo_Loyalty_Program

# [Python] Analyze Customer Behaviour from MoMo Loyalty Program

## Acknowledgement
Thank you teacher Trung Duc Tran for gently marked my project as 95/100 and commented truthfully so I can learn a lot more.

Trung Duc Tran's profile: https://www.researchgate.net/profile/Trung-Tran-31

## Introduction

Users' retention has always been one of the key targets that MoMo is striving to be better. A Loyalty program called "MoMo hoàn tiền" - one of the projects aiming to achieve such goal was launched from January 1st 2021 to March 2022.

Problems:

What ideas do you have for MoMo in loyalty program development strategy? Do you have any advice for the Marketing department in designing promotion campaigns to increase user retention's performance?

Solutions:

    Using KMeans to cluster customers in groups by analysing RFM.
    Find characteristics and true needs of users to offer the right service.

Why RFM?

RFM Analysis allows a comparison between potential contributors and clients. It gives organizations a sense of how much revenue comes from repeat customers (vs. new customers), and which levers they can pull to try to make customers happier so they become repeat purchasers.

## Body

### Steps
1. Understanding data by conducting bacic EDA
2. Customers Segmentation (Find RFM)
  - Plot distribution
  - Use Box-cox to transform data
  - Use StandardScaler to scale data
  - Plot final distribution after doing some feature engineering
3. Find K
  - Find K with normal approach (Ploting Elbow and Silhouette)
  - Find K by using function WCSS (Within-Cluster-Sum-of-Squares)
  - Find K by using built-in function named KneeLocator
  - Detect final K by using KElbowVisualizer (WCSS & SSE)
The basic idea behind the KElbowVisualizer is to plot the within-cluster sum of squared errors (SSE) against different values of k and look for a "kink" or "elbow" in  the plot where the rate of decrease in SSE slows down significantly. This point is often considered as the optimal value for K.

4. Modeling KMeans with K = 4
  - 3D Plot
  - Applying labels for 4 clusters
  - Clusters Analysis
5. Hypothesis Testing with T-test
  - Reject the H0 
6. Conclusion
  - Dendogram

## The end

This is my personal project, I presented this project for final term at school. I got 95/100 from my teacher. But not being too humble, I am just being inquisitive, enthusiastic that I really really desire to improve my project, make it better so do not hesitate to contact me if you have found something that can be done better in this project, I deeply appreciate it a lot.

My LinkedIn: https://www.linkedin.com/in/huypham040100/
