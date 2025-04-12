<h1 align="center">
🛍️ Customer Behaviour Analysis in Online Retail: <br> RFM Analysis & PCA for Marketing Insights 📈
</h1>

<h3 align="center"> 📊 Advanced EDA | 🔧 Feature Engineering | 💰 RFM Analysis | 🔍 PCA Dimensionality Reduction </h3>

---


## About the Project
  
The goal of this project is to understand customer behaviour patterns in an online retail environment and derive actionable insights for marketing strategies. Online retail generates vast amounts of transactional data that contains valuable patterns about customer preferences and behaviors.

Using advanced analytics techniques including detailed EDA, feature engineering, RFM analysis, and Principal Component Analysis, this project aims to uncover hidden patterns in customer behaviour and provide a foundation for targeted marketing strategies and personalized recommendations.


## About the Dataset

This dataset is derived from a UK-based online retailer and includes all transactions between December 2010 and December 2011. 

The retailer specializes in unique gifts for various occasions, with many customers being wholesalers. This extensive dataset provides a detailed record of transactions, including product details, customer information, and purchase history, making it ideal for analyzing customer behavior patterns in the retail sector.
    
*The Online Retail dataset is widely used for customer segmentation, clustering, customer relationship analysis and recommendation system development, making it a valuable resource for analysing customer behaviour in the retail sector.*
    
    
- **Dataset:** E-commerce Dataset / Online Retail Dataset  
- **Content:** Data on transactions including product details, customer information, and purchase history  
- **Number of Rows:** 541,909  
- **Number of Columns:** 8  

| **INPUTS**         | **Description**                                            |
|--------------------|------------------------------------------------------------|
| **InvoiceNo**      | Unique identifier for each transaction/invoice.            |
| **StockCode**      | Unique identifier for each product (product code).         |
| **Description**    | Description of the product.                                |
| **Quantity**       | The quantity of each product per transaction.              |
| **InvoiceDate**    | Date and time when the transaction occurred.               |
| **UnitPrice**      | Price of the product per unit.                             |
| **CustomerID**     | Unique identifier for each customer.                       |
| **Country**        | The country where the customer resides.                    |


**Reference:**
 UCI Machine Learning Repository. (2015). Online Retail Dataset. https://archive.ics.uci.edu/dataset/352/online+retail

 ## 🔍 Key Steps:
- **Data Exploration:** Detailed analysis of each column in the dataset to understand customer behavior, product popularity, and sales trends.
- **Feature Engineering:** Creation of advanced metrics including RFM analysis (Recency, Frequency, Monetary) and additional shopping pattern features.
- **Dimensionality Reduction:** Application of Principal Component Analysis to simplify complex data while preserving essential variance.
- **Component Analysis:** Interpretation of principal components to understand key drivers of customer behavior.

----

## 📂 Conclusion:

After conducting a thorough exploratory data analysis and applying Principal Component Analysis to our online retail dataset, we have gained valuable insights about customer behaviour patterns through dimensionality reduction.

The PCA results provided an effective way to reduce our complex, multi-dimensional customer data into a more manageable form while preserving the essential information. With five principal components, we were able to capture approximately 81% of the total variance in the dataset, which represents a significant portion of the customer behaviour patterns.

### Key Component Insights:

- **PC1 (43% variance)**: Strongly correlates with monetary metrics (0.95), total products purchased (0.92), and frequency of purchases (0.85). This component primarily represents the overall spending behaviour and engagement level of customers.

- **PC2 (17% variance)**: Has strong negative correlation with average price (-0.78) and monthly spending mean (-0.63), while positively correlating with cancellation rate (0.58) and average days between purchases (0.53). This seems to represent price sensitivity and purchase consistency.

- **PC3 (10% variance)**: Shows strong correlation with average days between purchases (0.60) and negative correlation with cancellation frequency (-0.54). This component appears to capture purchasing rhythm and satisfaction.

- **PC4 (8% variance)**: Has a strong correlation with favourite hour (0.88), suggesting it represents timing preferences in shopping behaviour.

- **PC5 (7% variance)**: Correlates most strongly with spending trend (0.70) and recency (0.39), potentially indicating growth potential and recent activity patterns.

### Business Impact:

These five components provide a simplified yet comprehensive view of customer behaviour, enabling more effective customer profiling and targeting strategies. By transforming raw transaction data into these meaningful components, we can better understand the underlying patterns driving customer behaviour in this online retail environment.

As a next step, applying K-means clustering to these principal components would allow for effective customer segmentation, followed by the potential development of a recommendation system tailored to each segment's unique characteristics and preferences.

---

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Customer Behaviour Analysis in Online Retail 🛍️](https://www.kaggle.com/code/duygujones/customer-behaviour-analysis-eda-rfm-pca)
 - The dataset is available to download on the UCI Machine Learning Repository: [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
 - Relevant Paper: UCI Machine Learning Repository. (2015). Online Retail Dataset. https://archive.ics.uci.edu/dataset/352/online+retail

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Duygu Jones, a Data Scientist, passionate about data analysis, and machine learning.

♻️ You can find more about me and my work through the following links:

- **LinkedIn**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)

🌐Feel free to connect with me!

<br>

🎯 Enhance your data analysis skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---

##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.