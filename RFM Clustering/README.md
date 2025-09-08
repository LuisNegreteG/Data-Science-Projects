# RFM Customer Segmentation with Clustering

## Project Overview
This project applies **RFM (Recency, Frequency, Monetary) analysis** to customer transaction data and uses **unsupervised clustering** to segment customers into meaningful groups.  
The goal is to help businesses identify high-value customers, predict churn, and tailor marketing strategies.

---

## Objectives
- Perform **RFM scoring** to evaluate customer behavior.  
- Apply clustering algorithms (e.g., K-means) to segment customers.  
- Visualize the clusters and interpret insights for decision-making.  

---

## Tools & Technologies
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Machine Learning**: scikit-learn (K-means, silhouette score, elbow method)  
- **Notebook**: Jupyter (exploration, visualization, and reporting)  

---

## Workflow
1. **Data Preparation** – Cleaning and formatting customer transaction data.  
2. **Feature Engineering** – Calculating Recency, Frequency, and Monetary values.  
3. **Normalization** – Scaling values to improve clustering performance.  
4. **Modeling** – Applying K-means clustering and evaluating with silhouette score.  
5. **Visualization** – Plotting clusters and analyzing customer groups.  

---

## Key Results
- Identified **4 distinct customer segments**:  
  - **VIP / High Value** – frequent, high spenders.  
  - **Loyal Customers** – moderate spenders, high frequency.  
  - **Occasional Customers** – irregular purchasing patterns.  
  - **At-Risk Customers** – long inactivity, low monetary value.  

- Improved understanding of customer base for **targeted marketing campaigns**.  

---

## Sample Outputs

<img width="1148" height="666" alt="image" src="https://github.com/user-attachments/assets/4d7cb116-c722-481d-beec-30a20e815dca" />

<img width="930" height="648" alt="image" src="https://github.com/user-attachments/assets/f3ee36dd-0187-4372-afe4-9ef4ea36718f" />

---

## Resources
- Notebook: [`RFM_Cluster Segmentation_Project.ipynb`](./RFM_Cluster Segmentation_Project.ipynb)  
- Data Source: https://archive.ics.uci.edu/dataset/502/online+retail+ii

---

## Skills Demonstrated
- Customer analytics & segmentation  
- Unsupervised machine learning (K-means clustering)  
- Feature engineering & scaling  
- Business interpretation of analytical models  
