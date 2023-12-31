# Data Mining Project 2020/2021 🎓
---
Members of the group:
- [Luca de Martino](https://github.com/luca-demartino)
- [Raffaele Villani](https://github.com/vlnraf)

The project's target is to study the customers' behaviour, trying to find some interesting patterns.<br>
The project includes:
- Data Understanding
- Clustering Analysis
- Classification
- Pattern Mining

### Data understanding
---

- Data semantics (3 points)
- Distribution of the variables and statistics (7 points)
- Assessing data quality (missing values, outliers) (7 points)
- Variables transformations (6 points)
- Pairwise correlations and eventual elimination of redundant variables (7 points)

### Data understanding
---
Improve the quality of your data and prepare it by extracting *new features* interesting for describing the customer profile and his purchasing behaviour. These indicators have to be extracted for each customer. 
Indicators to be computed are:
- I: the total number of items purchased by a customer during the period of observation.
- IU: the number of distinct items bought by a customer in the period of observation.
- Imax: the maximum number of items purchased by a customer during a shopping session.
- E: the Shannon entropy on the purchasing behaviour of the customer.
Each team must define **additional indicators** leading to the construction of a customer profile that can lead to an interesting analysis of customer segmentation. 
Once, the set of indicators will be computed the team has to explore the new features for statistical analysis (distributions, outliers, visualizations, correlations)
### Clustering
---
Based on the customer's profile explore the dataset using various clustering techniques. 
Carefully describe your decisions for each algorithm and which are the advantages provided by the different approaches. 
**Subtasks** 
-  Clustering Analysis by K-means:
    - Identification of the best value of k.
    - Characterization of the obtained clusters by using both analysis of the k centroids and comparison of the distribution of variables within the clusters and that in the whole dataset.
    - Evaluation of the clustering results.
-  Analysis by density-based clustering:
    - Study of the clustering parameters.
    - Characterization and interpretation of the obtained cluster
- Analysis by hierarchical clustering:
    - Compare different clustering results got by using different versions of the algorithm.
    - Show and discuss different dendrograms using different algorithms.
- Final evaluation of the best clustering approach and comparison of the clustering obtained.
- **Optional**: Explore the opportunity to use alternative clustering techniques in the library : [Clustering](https://github.com/annoviko/pyclustering/)

### Predictive Analysis
---
Consider the problem of predicting for each customer a label that defines if (s)he is a **high-spending** customer, **medium-spending** or **lower-spending** customer.  
The students need to:
- Define a customer profile that enables the above customer classification. Please reason on the suitability of the customer profile, defined for the clustering analysis. In case this profile is not suitable this profile is unsuitable for the above prediction problem,  
- Compute the label for any customer. Note that, the class to be predicted must be nominal.  
- Perform the predictive analysis comparing the performance of different models discussing the results and discussing the possible preprocessing that they applied to the data for managing possible problems identified that can make the prediction hard. Note that the evaluation should be performed on both training and test sets.

### Sequential Pattern Mining
---
Consider the problem of mining frequent sequential patterns. To address the task:
- Model the customer as a sequence of baskets.
- Apply the sequential pattern mining algorithm.
- Discuss the resulting patterns.

Note, that you can decide to filter out some customers.
