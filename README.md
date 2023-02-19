# Detecting_outliers

When working with a new dataset, it's important to inspect the data for anomalies and outliers before building a model. This can be done visually with techniques like box and whisker plots and distribution graphs. These visualizations can help identify potential issues with the data, such as skewed distributions or extreme values, which can impact the accuracy and performance of the model.

Outliers were using the [Isolation Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html) algorithm, which is a commonly used technique for outlier detection in datasets. This algorithm identifies anomalies by isolating observations that are different from the majority of the data based on their feature values.

Once the outliers have been removed, it's important to re-examine the distribution of each feature to ensure that the data is still representative of the underlying population. This can be done using distribution graphs again, which allow you to visualize the shape, spread, and central tendency of the data. The distribution graphs can also help identify any remaining outliers or anomalies that were not detected by the Isolation Forest algorithm.

By inspecting the data both visually and through statistical analysis, you can ensure that the data used to build the model is appropriate for the problem at hand and that the model is able to accurately capture the underlying patterns and relationships in the data.
