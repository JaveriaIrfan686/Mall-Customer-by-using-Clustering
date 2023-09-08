# Mall-Customer-by-using-Clustering
I am using "Mall Customer" dataset from kaggle. This dataset consists of 5 columns. In this, I have performed multiple clustering techniques. Lets first discuss about its pre-processing.

##Pre-processing
* There is no missing values in dataset.
* There are no duplicted values.
* The "Genre" column has categorical data. That's why I have performed one-hot encoding that shows 1 for MALE and 0 for FEMALE.
* I checked outliers.
    * Annual Income column have outliers only.
* I checked skewness in order to understand the distribution of data in terms of its asymmetry:
    * ###CustomerID:
       * Its value is 0.000 that shows the distribution of customer IDs is perfectly symmetrical. There is no skewness in this feature.
    * ### Genre:
       * Its value is 0.243578 that shows a slight positive skew. The distribution of the 'Genre' feature is slightly skewed to the right. This means that there may be a slightly higher number of one category of genres compared to the other.
    * ###AGE:
       * Its value is 0.485569 indicates a moderate positive skew. The distribution of ages is skewed to the right, shows that there might be more younger individuals in the dataset, with fewer older individuals.
    * ###Annual Income (k$):
       * Its value is 0.321843 indicates a moderate positive skew. The distribution of annual incomes is skewed to the right, suggesting that there may be more individuals with lower annual incomes and fewer individuals with higher annual incomes.
    * ###Spending Score (1-100):
       * Its value is -0.047220 is close to zero, indicating that the distribution of spending scores is approximately symmetrical. There is little to no skewness in this feature





