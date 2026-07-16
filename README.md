## K-Nearest Neighbors (KNN)

### Overview

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for both classification and regression tasks. It predicts the class of a new data point based on the labels of its **K nearest neighbors** in the feature space.

### How KNN Works

1. Choose the value of **K** (number of neighbors).
2. Calculate the distance between the new data point and all training samples.
3. Select the **K closest neighbors**.
4. For classification, assign the class that appears most frequently among the neighbors.
5. For regression, predict the average value of the neighbors.

### Distance Metrics

Common distance metrics include:

- Euclidean Distance
- Manhattan Distance
- Minkowski Distance

### Advantages

- Simple and easy to understand.
- No training phase (lazy learning).
- Works well on small datasets.
- Can be used for both classification and regression.

### Limitations

- Computationally expensive for large datasets.
- Sensitive to irrelevant features and outliers.
- Requires feature scaling for best performance.
- Performance depends on choosing an appropriate value of **K**.

### Libraries Used

```python
from sklearn.neighbors import KNeighborsClassifier
```

### Applications

- Customer Segmentation
- Recommendation Systems
- Fraud Detection
- Pattern Recognition
- Medical Diagnosis