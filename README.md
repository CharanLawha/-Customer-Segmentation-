# 🛍️ Customer Segmentation using K-Means

## 📌 Project Overview
This project applies **unsupervised learning (clustering)** to segment mall customers into groups based on their **Annual Income** and **Spending Score**.  
The analysis helps businesses identify different customer types such as **high spenders, budget-conscious, and average shoppers**, enabling better marketing strategies.

## 📊 Dataset
- **Source**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/)  
- **Features**:  
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## 🔑 Covered Topics
- Exploratory Data Analysis (EDA)  
  - Gender distribution (Pie Chart)  
  - Feature distributions (Histograms & Line Plots)  
  - Pairplots and scatter plots (Age vs Income, Income vs Spending Score)  
- Feature Scaling  
- K-Means Clustering  
- Elbow Method & Silhouette Score for optimal clusters  
- Cluster Visualization & Interpretation  

## 📂 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked distributions of age, income, and spending score  
   - Visualized gender balance and feature relationships  
2. **Feature Scaling**  
   - Prepared features for clustering  
3. **Clustering**  
   - Applied **K-Means clustering**  
   - Used **Elbow Method** to select optimal `k`  
4. **Visualization**  
   - Plotted clusters of customers with distinct colors  
   - Highlighted cluster centroids  
5. **Cluster Analysis**  
   - Calculated **average annual income & spending score per cluster**  
   - Interpreted customer groups (e.g., high income–high spenders, low income–low spenders)  

## 📈 Results
- The dataset was segmented into **5 distinct clusters**.  
- Key customer groups identified:  
  - **Cluster 1**: Low income – high spenders  
  - **Cluster 2**: High income – high spenders  
  - **Cluster 3**: Average income – average spenders  
  - **Cluster 4**: High income – low spenders  
  - **Cluster 5**: Low income – low spenders  
- Insights can help businesses **target promotions more effectively**.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
