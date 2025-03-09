
# Customer Segmentation Project

## 🛍️ Project Overview
This project involves analyzing customer behavior on an e-commerce platform to identify distinct customer segments using clustering techniques. The goal is to segment customers based on their interactions, purchases, and browsing patterns, which will help businesses tailor their strategies to different types of customers.

### 📊 Dataset Overview
The dataset contains the following features:

- **customer_id**: Unique ID for each customer.
- **total_purchases**: Total number of purchases made by the customer.
- **avg_cart_value**: Average value of items in the customer's cart.
- **total_time_spent**: Total time spent on the platform (in minutes).
- **product_click**: Number of products viewed by the customer.
- **discount_count**: Number of times the customer used a discount code.

The goal of this project is to identify and visualize customer behavior patterns and classify customers into distinct clusters. Based on the behavior and characteristics in the dataset, we aim to find **3 primary customer segments**.

### 👥 Customer Segments

#### 1. **Bargain Hunters**:
   - **Total Purchases**: High (frequent purchases).
   - **Average Cart Value**: Low (they buy cheaper items).
   - **Total Time Spent**: Moderate (they spend some time browsing but focus on purchasing).
   - **Product Clicks**: Moderate (they view a reasonable number of products).
   - **Discount Count**: High (they frequently use discount codes).

   **Behavior**: Deal-seekers who make frequent purchases of low-value items and heavily rely on discounts.

#### 2. **High Spenders**:
   - **Total Purchases**: Moderate (fewer but high-value purchases).
   - **Average Cart Value**: High (they buy expensive items).
   - **Total Time Spent**: Moderate (they spend time browsing but focus on high-value items).
   - **Product Clicks**: Moderate (they view a reasonable number of products).
   - **Discount Count**: Low (they rarely use discount codes).

   **Behavior**: Premium buyers who focus on high-value purchases and are less influenced by discounts.

#### 3. **Window Shoppers**:
   - **Total Purchases**: Low (they make very few purchases).
   - **Average Cart Value**: Moderate (they view items of varying prices).
   - **Total Time Spent**: High (they spend a lot of time browsing).
   - **Product Clicks**: High (they view a large number of products).
   - **Discount Count**: Low (they rarely use discount codes).

   **Behavior**: Customers who browse a lot but rarely make purchases. They are interested in exploring various products, possibly for research or future purchases.

---

## 🎯 Objective
The goal of this project is to use a clustering algorithm to identify and visualize customer segments based on the provided features. We validated multiple models, including Agglomerative Clustering, Gaussian Mixture Models (GMM) and K-Means clustering. K-Means clustering was selected as the best model based on its performance and accuracy for this task.

### 🛠️ Key features 
## 🧹 Data Cleaning & Preprocessing
- **Handling Missing Data**: Addressed any missing values in the dataset.
- **Feature Scaling**: Normalized features to ensure equal contribution to clustering.

## 🔍 Exploratory Data Analysis (EDA)
- **Visualized Relationships**: Explored correlations between features using plots to understand patterns in customer behavior.

## 🔧 Feature Engineering
- **Created New Features**: Derived additional features to improve the clustering model's performance, such as scaling the numerical features.

## 🏗️ Model Building
- **Clustering Models**: Validated multiple clustering algorithms (K-Means, Agglomerative Clustering, Gaussian Mixture Model). **K-Means** was selected based on performance and accuracy.

## 📊 Model Evaluation
- **Evaluation Metrics**: Used metrics like **silhouette score** and **elbow method** to evaluate and compare clustering performance.
"""

---

## 📁 Project Folder Structure

```
customer-segmentation/
│
├── customer_behavior_analytcis.csv               # The dataset containing customer information
│            
│
├── customer_segmentation.ipynb                   # Jupyter notebook for analysis and clustering
│   
├── requirements.txt                 # List of dependencies
│
├── report.pdf                       # Detailed report on analysis and clustering methods
│
├── README.md                        # Project documentation
│
└── LICENSE                          # License file (optional)
```

---

## 🧑‍💻 Prerequisites

To run this project, you will need the following Python libraries:

- `pandas` - for data manipulation and analysis.
- `numpy` - for numerical operations.
- `matplotlib` - for data visualization.
- `seaborn` - for statistical data visualization.
- `scikit-learn` - for machine learning algorithms and clustering techniques (including K-Means).
- `jupyter` - for running the Jupyter notebook.

You can install the required libraries using `pip` by running the following command:

```bash
pip install -r requirements.txt
```


## 🚀 Reproducing the Results

To reproduce the clustering results and analysis, follow these steps:

1. Clone this repository:
   
   ```bash
   git clone https://github.com/Sanila-577/Intellihack_OutlierRejects_Task2.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook to explore the customer segmentation analysis:

   ```bash
   jupyter notebook customer_segmentation.ipynb
   ```

4. Run the cells in the notebook to execute the analysis.

5. **Optional**: View the detailed report in PDF format (`report.pdf`), which includes further details on the methodology, analysis and results.

---

## 📈 Results

The results of the clustering analysis will provide insights into customer behavior, segmenting customers into three primary groups:

1. **Bargain Hunters**
2. **High Spenders**
3. **Window Shoppers**

These segments can be used to tailor marketing strategies, improve user experience, and enhance business decision-making processes.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
