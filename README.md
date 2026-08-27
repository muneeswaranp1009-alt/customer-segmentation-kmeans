# Customer Segmentation using K-Means Clustering

## Overview

Customer Segmentation is a machine learning project which groups customers according to their characteristics and the way they spend.

The project makes use of the Mall Customers dataset and applies learning in order to identify various customer segments.

## Objective

This project is intended to examine customer data and divide the customers into separate clusters.

Customer segmentation can enable businesses to get a better understanding of customer behaviour and identify groups that have certain spending habits.

## Dataset

The project involves the Mall Customers dataset.

The dataset contains customer-related information such as:

- Customer ID

- Gender

- Age

- Annual Income

- Spending Score

They aid in the investigation of customer characteristics and in identifying groups.

## Machine Learning Algorithm

This project uses:

### K-Means Clustering

K-Means is a machine learning algorithm which groups together data points that are similar.

The algorithm works by:

1. Start by deciding on how to use the clusters.

2. Then allocate each data point to the cluster.

3. Next find the centre point for each cluster.

4. Keep carrying out these steps until the clusters no longer change.

## Workflow

```text

Load Dataset

|

v

Explore Customer Data

|

v

Select Relevant Features

|

v

Determine Number of Clusters

|

v

Apply K-Means Clustering

|

v

Assign Cluster Labels

|

v

Visualize Customer Segments

```

## Finding the Optimal Number of Clusters

The Elbow Method may be used to determine a good number of clusters.

The WCSS, which is the Within-Cluster Sum of Squares, is calculated for various values of K.

To choose the appropriate number of clusters, the results are displayed in graphical form.

## Customer Segmentation

Customers are grouped by similarities in chosen features like:

- Annual Income

- Spending Score

Each customer is then assigned a cluster label.

These groups of customers can have different income levels and spending habits.

## Visualizations

The project includes data visualisations which aid in understanding the different customer segments.

Possible visualizations include:

- Customer distribution

- Annual Income vs Spending Score

- Cluster visualization

- Elbow Method graph

- Cluster centroids

## Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Scikit-learn

## Project Structure

```text

customer-segmentation-kmeans/

│

├── customer_segmentation.py

├── Mall_Customers.csv

── README.md

```

## Installation

Clone the repository:

```bash

git clone https://github.com/yourusername/customer-segmentation-kmeans.git

```

Navigate to the project directory:

```bash

cd customer-segmentation-kmeans

```

Install the required libraries:

```bash

pip install pandas numpy matplotlib scikit-learn

```

## Running the Project

Run the Python file:

```bash

python customer_segmentation.py

```

The program will:

1. Start by loading the customer dataset.

2. Next, look at the features that are available.

3. Then select the features that are to be used for clustering.

4. Carry out the Elbow Method.

5. Train the K-Means clustering model after that.

6. Next, allocate the customers to their clusters.

7. Lastly, imagine what the customer segments are like.

## Key Concepts Practiced

### Data Analysis

- Loading CSV datasets

- Exploring data

- Feature selection

- Data visualization

### Machine Learning

- Unsupervised Learning

- K-Means Clustering

- Cluster Analysis

- Elbow Method

- WCSS

- Cluster Centroids

## Learning Outcomes

Through this project I gained hands‑on experience with:

- Unsupervised Machine Learning

- Customer segmentation

- K-Means clustering

- Selecting the number of clusters

- Data visualization

- Analyzing customer behavior

- Working with real-world datasets

## Future Improvements

- Apply additional clustering algorithms

- Compare K-Means with Hierarchical Clustering

- Add PCA for dimensionality reduction

- Build a dashboard using Streamlit

- Add more customer features

- Create a customer recommendation system

## Author

**Muneeswaran P**

Student in the field of Artificial Intelligence and Machine Learning with a B.Sc.

I am interested in intelligence, machine learning, Python, and in carrying out practical data-driven projects.

## License

The purpose of this project is to be used for learning.
