Feature scaling in machine learning is the process of normalizing the range of independent variables or features in a dataset. The key points about feature scaling are:
**Feature scaling is applied to columns (features). It is never applied across columns or data in rows**

**Motivation:** Feature scaling is important because machine learning algorithms can be sensitive to the scale of the features. If the features have varying magnitudes, ranges, or units, it can cause some features to dominate the objective function, leading to poor model performance.

**Normalization vs Standardization:** 
There are two main methods of feature scaling:
**Normalization (min-max scaling):** Rescales the features to a common range, typically between 0 and 1.
**Standardization (z-score normalization):** Rescales the features to have a mean of 0 and a standard deviation of 1.

**Importance:** Feature scaling is important for many machine learning algorithms, such as gradient descent, distance-based algorithms (e.g., k-nearest neighbors), and support vector machines. It can improve the convergence speed of the algorithm and prevent numerical instability.

**When to use:** Feature scaling is recommended for most basic machine learning algorithms, especially when the features have different ranges, magnitudes, or units. It helps ensure that each feature contributes equally to the learning process.

**Implementation:** Popular Python libraries like scikit-learn provide functions like StandardScaler and MinMaxScaler to perform feature scaling on datasets.

