# K-Means Clustering Using the Elbow Method

## Overview

This project demonstrates the implementation of the **K-Means Clustering** algorithm using Python and the **Scikit-learn** library. It uses a sample housing dataset containing **Area** and **House Cost** to group similar data points into clusters.

The project also applies the **Elbow Method** to determine the optimal number of clusters before performing the final clustering.

---

## Features

* Creates a sample housing dataset using Pandas.
* Applies the Elbow Method to identify the optimal value of **K**.
* Performs K-Means clustering with **K = 3**.
* Visualizes clusters using a scatter plot.
* Displays cluster centroids.
* Prints inertia values and final clustering statistics.

---

## Technologies Used

* Python 3
* Pandas
* Matplotlib
* Scikit-learn

---

## Dataset

The dataset contains two features:

| Feature   | Description       |
| --------- | ----------------- |
| Area      | Size of the house |
| HouseCost | Cost of the house |

Sample Data:

| Area | HouseCost |
| ---- | --------- |
| 10   | 30        |
| 20   | 40        |
| 30   | 50        |
| 70   | 70        |
| 80   | 80        |
| 90   | 90        |
| 130  | 120       |
| 150  | 130       |
| 170  | 150       |

---

## Project Workflow

1. Import the required Python libraries.
2. Create the housing dataset.
3. Apply the Elbow Method for values of **K = 1 to 7**.
4. Plot the inertia values to determine the optimal number of clusters.
5. Train the K-Means model with **K = 3**.
6. Visualize the clustered data and cluster centroids.
7. Print the inertia values and final clustering information.

---

## Output

The program generates:

* Elbow Method graph
* K-Means clustered scatter plot
* Cluster centroids
* Inertia values for different K values
* Final inertia for K = 3
* Total number of data points

---

## How to Run

1. Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

2. Save the Python program.

3. Run the script:

```bash
python kmeans_clustering.py
```

---

## Learning Outcomes

After completing this project, you will understand:

* What K-Means Clustering is.
* How the Elbow Method helps determine the optimal number of clusters.
* How inertia measures clustering quality.
* How to visualize clustered data using Matplotlib.
* How to implement K-Means using Scikit-learn.

---

## Future Enhancements

* Use larger real-world datasets.
* Normalize data before clustering.
* Compare K-Means with other clustering algorithms such as DBSCAN and Hierarchical Clustering.
* Add interactive visualizations.

---

## Author

**Hasini Nimmakayala**

Undergraduate Student | Learning Python, Java, and Machine Learning
