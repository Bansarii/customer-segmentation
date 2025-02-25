# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers based on their **annual income and spending score**. The goal is to identify different customer groups and help businesses make **data-driven marketing decisions**.

## 🚀 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Machine Learning** (K-Means Clustering)
- **Data Visualization** (Seaborn, Matplotlib)

## 📂 Dataset
- **Dataset Name:** Mall Customers Dataset  
- **Source:** [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Features:**
  - `CustomerID`: Unique ID for each customer
  - `Gender`: Male/Female
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Customer's yearly income in $1000s
  - `Spending Score (1-100)`: Score assigned based on spending behavior

## 📊 Exploratory Data Analysis (EDA)
- Distribution of **Age, Annual Income, and Spending Score**
- Correlation analysis between **income and spending habits**
- Outlier detection and data preprocessing

## 🔍 K-Means Clustering
### **1️⃣ Finding the Optimal Number of Clusters**
- Used the **Elbow Method** to determine the best `K` value
- Visualized WCSS (Within-Cluster Sum of Squares) vs. Cluster Count

### **2️⃣ Applying K-Means**
- Standardized the dataset using `StandardScaler`
- Trained a K-Means model with `n_clusters=5`
- Assigned customers into clusters based on their **spending behavior**

## 📈 Results & Visualizations
- **Clustered Customers** based on **Annual Income vs. Spending Score**
- **Identified Customer Groups:**
  - **High Income, High Spending (Luxury Shoppers)**
  - **Low Income, High Spending (Potential Credit Risk)**
  - **Moderate Income, Moderate Spending (Regular Shoppers)**
  - **Low Income, Low Spending (Minimal Shoppers)**
  - **High Income, Low Spending (Frugal Customers)**

### **🖼️ Sample Visualization**
![Customer Segmentation Plot](https://github.com/Bansarii/customer-segmentation/blob/main/Mall_clu_kmeans.png)

## 📌 Key Insights
✔ **Luxury shoppers** can be targeted with premium offers  
✔ **Low-income high spenders** may need loyalty programs or discounts  
✔ **Regular shoppers** represent a stable revenue base  
✔ **Frugal customers** may need incentives to increase spending  

## 🔗 Repository Structure
📂 Customer-Segmentation │── 📂 images/ # Plots & visualizations │── customer_segmentation.ipynb # Jupyter Notebook │── README.md # Project Documentation

## 🎯 Next Steps
🔹 Try **Hierarchical Clustering** for comparison  
🔹 Use **additional features (Age, Gender) for deeper insights**  
🔹 Deploy this model using **Streamlit or Flask**  

## 🤝 Connect with Me!
If you found this project helpful, feel free to connect with me on **[LinkedIn](https://www.linkedin.com/)** or give this repo a ⭐ on GitHub!

---

### **🔹 Next Steps for You**
✅ Add this `README.md` to your GitHub repository.  
✅ Upload sample **visualization images** (Elbow Method plot, Cluster Plot).  
✅ Share your **project on LinkedIn** with insights!  

Let me know if you need any modifications! 🚀🔥
