# 🛍️ Customer Segmentation Analysis (using RFM & KMeans)  
📅 **Date:** November 2024  
👨‍💻 **Author:** Nirmalkumar Thirupallikrishnan Kesavan, Mohammed Ibrahim LNU  
🏫 **Institution:** Northeastern University, Boston MA  

🔗 **Portfolio:** [Nirmalkumar TK](https://www.datascienceportfol.io/nirmalkumartk)  
🔗 **LinkedIn:** [Nirmalkumar TK](https://www.linkedin.com/in/nirmalkumartk/)  

---

## 📌 **Project Overview**  
In today’s **data-driven eCommerce industry**, businesses must understand customer purchasing behavior to optimize engagement, enhance retention, and drive revenue growth. Traditional segmentation strategies often fail to capture dynamic purchasing trends, making **RFM (Recency, Frequency, Monetary) analysis** a powerful technique for segmenting customers based on real transaction data.  

This project applies **RFM analysis and KMeans clustering** to an **eCommerce dataset (2010-2011, UK-based online retailer)** to group customers into **distinct segments** based on their buying patterns.  

### **Key Objectives:**  
✔ Identify **distinct customer segments** based on transaction history  
✔ Leverage **RFM metrics** to assess customer value  
✔ Use **KMeans clustering** for customer segmentation  
✔ Provide **business insights** and **marketing recommendations** to optimize customer retention  

---

## 🛠️ **Tech Stack & Tools Used**  

- **Programming Language:** Python 🐍  
- **Data Analysis & Manipulation:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Machine Learning & Clustering:** Scikit-learn (KMeans)  
- **Jupyter Notebook** for interactive analysis  

---

## 📊 **Methodology & Implementation**  

### **1️⃣ Data Preprocessing**  
- **Dataset**: The dataset contains transaction details from **2010-2011 for a UK-based online retailer**.  
- **Data Cleaning**:  
  - Removed **135,080 missing Customer IDs** (essential for accurate segmentation).  
  - Handled **1,454 missing values** in the product description.  
  - Converted the **InvoiceDate** column into a **datetime format** to facilitate time-based analysis.  
  - Ensured data consistency by checking **duplicate invoices and incorrect entries**.  

---

### **2️⃣ RFM Analysis**  
RFM Analysis is a customer segmentation technique that groups customers based on:  

- **Recency (R):** How recently a customer made a purchase.  
- **Frequency (F):** How often a customer makes purchases.  
- **Monetary (M):** Total revenue generated by each customer.  

#### 📌 **Key Insights from RFM Analysis**  
✔ **Recency Analysis**: Customers were ranked based on how recently they purchased.  
✔ **Frequency Trends**: Identified frequent buyers versus one-time customers.  
✔ **Monetary Distribution**: Found high-spending customers vs. low spenders.  
✔ **Customer Segmentation based on RFM scores**:  
   - **High-value customers**: Frequent purchases with high spending.  
   - **At-risk customers**: High monetary value but low recency.  
   - **Dormant customers**: Low frequency and monetary value.  

---

### **3️⃣ Customer Segmentation using KMeans Clustering**  
✔ **Used the Elbow Method** to determine the optimal number of clusters (**K=3**).  
✔ Applied **KMeans clustering** on **RFM scores** to segment customers into **three main groups**.  
✔ **Visualized clusters using scatter plots** to interpret customer behavior.  

#### 🚀 **Cluster Insights & Customer Behavior**  

| Cluster | # Customers | Recency (Days) | Frequency | Monetary ($) | Customer Type |
|---------|------------|---------------|-----------|--------------|---------------|
| **0** | **3,258** | **39** | **6** | **1.4M** | Moderate Value |
| **1** | **1,108** | **245** | **2** | **51,930** | Dormant Customers |
| **2** | **6** | **7** | **138** | **95.7M** | High-Value Customers |

---

## 📢 **Marketing Recommendations**  

📌 **Cluster 0 (Moderate Value Customers - Largest Group)**  
✔ **Launch loyalty programs** to increase repeat purchases.  
✔ Use **personalized recommendations** based on past purchases.  
✔ Offer **time-sensitive discounts** to maintain customer engagement.  

📌 **Cluster 1 (Low-Value Customers - Dormant Buyers)**  
✔ Send **win-back emails** with special discounts & promotions.  
✔ Introduce **low-risk subscriptions** to encourage engagement.  
✔ Use **targeted ads** to re-engage inactive customers.  

📌 **Cluster 2 (High-Value Customers - VIPs)**  
✔ Implement **VIP loyalty programs** with exclusive perks.  
✔ Offer **personalized thank-you messages & gifts.**  
✔ Provide **early access to new products** to maintain engagement.  

📌 **General Strategies:**  
✔ **Cross-selling:** Recommend complementary products.  
✔ **Personalized communication:** Use behavior data for targeted marketing.  
✔ **Retention Strategies:** Keep VIP customers engaged.  
✔ **Feedback Collection:** Conduct surveys to enhance customer experience.  

---

## 📌 **Key Business Insights from Data Analysis**  

✔ **Peak Sales Days:** 📅 **Thursday has the highest orders**, while Friday & Sunday see lower engagement.  
✔ **Peak Shopping Hours:** 🕛 **Most orders occur between 11 AM - 2 PM.**  
✔ **Seasonality Trends:**  
   - 📈 **November & December show peak sales activity** due to the holiday season.  
   - 📉 **January & February have lower orders**, suggesting post-holiday slowdowns.  
✔ **Geographical Trends:**  
   - 🌍 **The UK dominates sales** (361,878 orders), followed by **Germany, France, and Ireland.**  
✔ **Profitability Analysis:**  
   - 📊 **Identified high-margin products for targeted promotions.**  

---
🔗 [**Project Report**](https://github.com/NirmalKumar31/Customer-Segmentation-Analysis/blob/3aee7b83a98dbe72f25a76b88ecf2ec3ab582fbe/Customer%20Segmentation%20Analysis%20-%20Project%20Report.pdf)  
🔗 [**Code File**](https://github.com/NirmalKumar31/Customer-Segmentation-Analysis/blob/3aee7b83a98dbe72f25a76b88ecf2ec3ab582fbe/Customer%20Segmentation%20Analysis.ipynb)  
