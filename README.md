# Customer_Segmentation_Using_K_Means_Clustering

Customer Segmentation Using K-Means Clustering
Project Overview
Customer segmentation is the process of dividing customers into groups based on common characteristics, which helps businesses to target different customer segments more effectively. This project applies the K-Means Clustering algorithm to segment customers based on features such as age, annual income, and spending score.

The goal of this project is to use unsupervised machine learning to group customers into distinct clusters and analyze their behavior to derive actionable business insights.

Objectives
To explore customer data and identify significant patterns using clustering.
To group customers into clusters based on their purchasing behavior and demographic attributes.
To provide insights that will help businesses improve their marketing strategies, customer engagement, and retention efforts.
Dataset
The dataset contains the following columns:

CustomerID: Unique identifier for each customer.
Age: Age of the customer.
Annual_Income: Annual income of the customer in USD.
Spending_Score: A score between 1 and 100 assigned to customers based on their spending habits and behavior.
Sample Data:
CustomerID	Age	Annual_Income	Spending_Score
1	23	50,000	55
2	45	80,000	22
3	34	62,000	77
Tech Stack / Libraries Used
Python: Programming language used for analysis.
Pandas: Data manipulation and analysis library.
NumPy: Numerical computing library used for handling arrays.
Matplotlib: Visualization library used for plotting graphs.
Seaborn: Visualization library for creating statistical plots.
Scikit-learn: Machine learning library used for clustering and data preprocessing.
Steps in the Project
Data Preprocessing:

Loaded the dataset and checked for missing values.
Handled missing values and scaled the features using StandardScaler to ensure that all data is on the same scale.
K-Means Clustering:

Applied the Elbow Method to determine the optimal number of clusters by plotting the sum of squared distances (SSE) for different values of K.
Applied K-Means clustering to group customers into clusters based on their attributes.
Visualization:

Created scatter plots to visualize the customer segments.
Plotted customer segments by Age vs Annual Income, and Annual Income vs Spending Score to gain insight into the clustering.
Insights:

Analyzed the characteristics of each cluster to understand customer segments better.
Provided insights into high-spending customers, low-income customers, and potential areas for targeted marketing.
Key Findings
Cluster 1: High-income customers with moderate spending scores. They may be more selective in their purchases.
Cluster 2: Younger customers with moderate income but high spending scores, representing a segment that could be highly engaged.
Cluster 3: Low-income customers with lower spending scores, which could be targeted for discounts or loyalty programs.
Usage
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/shiva201/Customer_Segmentation_Using_K_Means_Clustering.git
Install the required libraries:
bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Project
Download the dataset and place it in the project directory (replace customer_data.csv with your dataset).
Run the script customer_segmentation.py:
bash
Copy code
python customer_segmentation.py
Visualizations
1. Elbow Method
This plot helps to identify the optimal number of clusters by showing the point at which the SSE starts decreasing more slowly (the "elbow").


2. Customer Segments by Age and Annual Income
Scatter plot visualizing customer segments based on age and income.


3. Customer Segments by Annual Income and Spending Score
Scatter plot visualizing customer segments based on income and spending behavior.


Contributing
If you would like to contribute, feel free to create a pull request or submit issues. All contributions are welcome!
