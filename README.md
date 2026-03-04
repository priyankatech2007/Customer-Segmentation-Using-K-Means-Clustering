# Customer Segmentation Using K-Means Clustering

## 📖 Overview
Customer segmentation is a crucial task for businesses to better understand their customers and tailor marketing strategies accordingly.  
This project implements **K-Means clustering**, an unsupervised machine learning algorithm, to segment customers based on their **annual income** and **spending behavior**.

By grouping customers into distinct clusters, businesses can identify high-value customers, low-spending customers, and other meaningful segments that help in decision-making and targeted marketing.

---

## 🎯 Project Objectives
The main objectives of this project are:
- To analyze customer data and understand purchasing patterns
- To segment customers into meaningful groups using K-Means clustering
- To determine the optimal number of clusters using the Elbow Method
- To visualize customer segments for better interpretation
- To demonstrate the practical application of unsupervised machine learning

---

## 📊 Dataset Information
- **Dataset Name:** Mall Customers Dataset  
- **Source:** Kaggle  
- **Type:** Retail customer data  

### Attributes Used:
| Column Name | Description |
|------------|-------------|
| CustomerID | Unique identifier for each customer |
| Gender | Gender of the customer |
| Age | Age of the customer |
| Annual Income (k$) | Annual income of the customer |
| Spending Score (1-100) | Score assigned based on customer spending behavior |

The dataset contains **200 customer records** and does not include missing values, making it suitable for clustering analysis.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Scikit-learn  
- **Development Environment:** Google Colab  

---

## ⚙️ Methodology
The project follows a structured machine learning workflow:

1. **Data Loading**
   - Load the dataset into a Pandas DataFrame.

2. **Data Exploration**
   - Understand dataset structure using `info()` and `describe()`.

3. **Data Preprocessing**
   - Check for missing values.
   - Select relevant features for clustering.

4. **Feature Scaling**
   - Apply StandardScaler to normalize features.

5. **Elbow Method**
   - Identify the optimal number of clusters by plotting WCSS.

6. **K-Means Clustering**
   - Apply K-Means algorithm with the chosen number of clusters.

7. **Visualization**
   - Plot customer segments using a scatter plot.

8. **Cluster Analysis**
   - Analyze each cluster’s characteristics.

---

## 📈 Results
- The Elbow Method indicated **5 clusters** as the optimal number.
- Customers were successfully grouped into five distinct segments based on income and spending score.
- Each cluster represents a unique customer profile, such as:
  - High income – high spending
  - High income – low spending
  - Low income – high spending
  - Low income – low spending
  - Average income – average spending

These insights can help businesses improve marketing strategies and customer engagement.

---

## 📊 Visualization
The final output includes a scatter plot where:
- X-axis represents **Annual Income**
- Y-axis represents **Spending Score**
- Different colors represent different customer clusters

This visualization makes it easy to understand customer segmentation at a glance.

---

## ✅ Conclusion
This project demonstrates the effectiveness of **K-Means clustering** for customer segmentation.  
By analyzing income and spending behavior, customers can be grouped into meaningful clusters that provide valuable business insights.

The approach used in this project can be extended to larger datasets and additional features for more advanced customer analytics.

---

## 🚀 Future Enhancements
- Include additional features such as age and gender in clustering
- Apply other clustering algorithms like Hierarchical or DBSCAN
- Perform cluster labeling and business interpretation
- Build a dashboard for interactive visualization

---

## 👩‍💻 Author
**Priyanka**

---

## 📌 Note
This project is intended for educational and learning purposes and demonstrates the practical application of unsupervised machine learning techniques.
