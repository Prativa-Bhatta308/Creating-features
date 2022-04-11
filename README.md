# Creating-features

Instructions

Create X, an array of the values from the sales_df DataFrame's "radio" column.
Create y, an array of the values from the sales_df DataFrame's "sales" column.
Reshape X into a two-dimensional NumPy array.
Print the shape of X and y.

import numpy as np

# Create X from the radio column's values
X = sales_df["radio"].values

# Create y from the sales column's values
y = sales_df["sales"].values

# Reshape X
X = X.reshape(-1, 1)

# Check the shape of the features and targets
print(X.shape, y.shape)

output:
    (4546, 1) (4546,)
