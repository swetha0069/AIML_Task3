This Exploratory Data Analysis (EDA) was performed on the Iris Dataset to understand the distribution of physical characteristics across three flower species. The goal is to identify patterns, detect outliers, and determine which features are most important for predicting the species.

1. Distribution of Numerical Features (Histogram)
Observation: The histogram for Sepal Length shows a relatively normal distribution with a slight right skew.

Insight: Most flowers in this dataset have a sepal length falling between 5.0 and 6.5 units.
Shutterstock
Explore


2. Categorical Analysis (Count Plot)
Observation: The count plot confirms that the dataset is perfectly balanced.

Insight: There are exactly 50 samples for each species (Setosa, Versicolor, and Virginica), ensuring that a future machine learning model won't be biased toward one specific category.

3. Outlier Detection (Box Plot)
Observation: The box plot highlights that most features are within expected ranges, but Sepal Width contains a few data points outside the whiskers.

Insight: These outliers represent rare variations in the flower population. Identifying them is crucial as they can impact the accuracy of statistical summaries.

4. Feature Relationships (Correlation Heatmap)
Observation: There is an extremely strong positive correlation (near 0.96) between Petal Length and Petal Width.

Insight: These two features are the most important for prediction. However, because they are so highly correlated, we must watch for Multicollinearity, where redundant features provide the same information to a model.
