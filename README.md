# Customer-segmentation
Customer segmentation using K-Mean clustering

Customer segmentation is a vital step in understanding consumer behavior and improving marketing strategies. This project uses the K-Means clustering algorithm to analyze and group mall customers based on their income levels and spending scores.


## Introduction
This project aims to classify customers into distinct groups using clustering techniques. By analyzing the provided dataset, we identify patterns that can help businesses understand and tailor their services to different customer groups.

## Motivation
Customer segmentation provides insights into customer behavior, preferences, and financial capabilities. This helps businesses:

- Personalize their marketing strategies.
- Optimize resource allocation.
- Enhance customer satisfaction and retention.

## Dataset
The dataset used in this project is Mall_Customers.csv, which consists of:

- 200 records of customer data.
- 5 features:
  - `CustomerID`: Unique identifier for customers.
  - `Gender`: Male or Female.
  - `Age`: Age of the customer.
  - `Annual Income (k$)`: Income in thousands of dollars.
  - `Spending Score (1-100)`: Mall-assigned score reflecting spending habits

## Features
### Key Highlights:
  - Implements the K-Means Clustering Algorithm.
  - Determines the optimal number of clusters using the Elbow Method.
  - Visualizes data distribution and clusters with Seaborn and Matplotlib.
### Insights:
  - Identify high-value customers.
  - Segment based on spending behavior and income levels.

## Tech Stack
### Programming Languages:
  Python
### Libraries:
  - Data Analysis: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Machine Learning: sklearn

## Workflow
1. Data Preprocessing:

    - Load the dataset and check for missing or inconsistent data.
    - Analyze basic statistics and visualize distributions.
2. Exploratory Data Analysis (EDA):

    - Plot relationships between income, spending score, and age.
    - Identify patterns and trends in customer demographics.
3. Clustering:

    - Apply the Elbow Method to determine the optimal number of clusters.
    - Use the K-Means algorithm to assign customers to clusters.
4. Visualization:

    - Represent clusters in a 2D plot.
    - Provide a clear interpretation of the clustering results.
5. Interpretation:

    - Discuss the characteristics and implications of each cluster.

## Setup
### Prerequisites
  - Python 3.7 or higher
  - `pip` for package management
### Installation
1. Clone the repository:
```
git clone https://github.com/Varun-Ajith/Customer-segmentation.git
```
2. Navigate to the project directory:
```
cd Customer-segmentation
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Place the dataset (`Mall_Customers.csv`) in the root directory.

## Usage
1. Launch the Jupyter Notebook:
```
jupyter notebook
```
2. Open the Customer_segmentation.ipynb file.
3. Run all cells sequentially.

## Results
The clustering analysis identified distinct customer groups:

1. Cluster 1: High-income, high-spending customers (VIPs).
2. Cluster 2: Low-income, high-spending customers (Potentially overspending).
3. Cluster 3: Moderate-income, moderate-spending customers.

### Visualizations
  - Scatter plots showing clusters.
  - Distribution plots for income and spending scores.

## Future Work
- Add advanced clustering algorithms like DBSCAN or Agglomerative Clustering.
- Automate cluster interpretation with dashboards.
- Incorporate more customer attributes to refine segmentation.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (git checkout -b feature-name).
3. Commit your changes (git commit -m "Add feature-name").
4. Push to your branch (git push origin feature-name).
5. Submit a pull request.
   
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
