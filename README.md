# Customer Segmentation Project

## 🚀 Introduction <a name="introduction"></a>
Customer segmentation is a powerful technique used by businesses to group customers based on common characteristics. This allows companies to target marketing efforts more effectively, personalize customer experiences, and increase overall business efficiency.

## 📝 Project Overview <a name="project-overview"></a>
In this project, we apply clustering algorithms to segment customers based on their purchasing behavior and demographics. The goal is to identify distinct customer segments that can be targeted with tailored marketing strategies.

## Objectives:
To identify different customer segments using clustering algorithms.
To analyze the characteristics of each segment.
To provide actionable insights for marketing and business strategy.
## 📊 Dataset <a name="dataset"></a>
The dataset used in this project includes information on customer demographics, purchase history, and other relevant variables.

### Features:
* CustomerID: Unique ID for each customer.
* Gender: Gender of the customer.
* Age: Age of the customer.
* Annual Income (k$): Annual Income of the customer in thousand dollars.
* Spending Score (1-100): A score assigned by the store based on customer behavior and spending nature.

### Data Source:
The dataset is sourced from https://www.kaggle.com/code/kushal1996/customer-segmentation-k-means-analysis.

### Preprocessing:
* Handling missing values.
* Feature scaling and normalization.
## 🔍 Exploratory Data Analysis (EDA) <a name="eda"></a>
EDA is performed to understand the distribution of data, identify outliers, and explore relationships between different variables. Key visualizations include:

* Age Distribution: A histogram showing the age distribution of customers.
* Income vs Spending Score: A scatter plot visualizing the relationship between income and spending score.
* Correlation Matrix: A heatmap displaying the correlations between different features.

## ⚙️ Methods and Techniques <a name="methods"></a>
We applied several clustering algorithms to segment the customers:

### Clustering Algorithms:
* K-Means Clustering: Selected the optimal number of clusters using the Elbow Method.
* Hierarchical Clustering: Created dendrograms to visualize and decide the number of clusters.
* DBSCAN: Used for identifying noise and handling non-linear cluster shapes.
  
### Model Evaluation:
* Silhouette Score: Used to evaluate the compactness and separation of the clusters.
* Inertia: Calculated for K-Means to evaluate how well the clusters are formed.

## 📑 Results and Insights <a name="results"></a>
The analysis revealed distinct customer segments:

### Key Segments:
* High Income, High Spending: Customers with high purchasing power and loyalty.
* Low Income, High Spending: Potential customers for targeted promotions.
* Young, Low Income, Low Spending: Budget-conscious young customers.
### Business Insights:
* Segment 1: Should be targeted with premium products and loyalty programs.
* Segment 2: Offers and discounts could be effective in increasing spending.
* Segment 3: Can be engaged through social media and budget-friendly options.
