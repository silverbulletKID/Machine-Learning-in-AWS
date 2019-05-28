# Machine-Learning-in-AWS

## Case 1 Population Segmentation with SageMaker

Using principal component analysis (PCA) you will reduce the dimensionality of the original census data. Then, you'll use k-means clustering to assign each US county to a particular cluster based on where a county lies in component space. How each cluster is arranged in component space can tell you which US counties are most similar and what demographic traits define that similarity; this information is most often used to inform targeted, marketing campaigns that want to appeal to a specific group of people. This cluster information is also useful for learning more about a population by revealing patterns between regions that you otherwise may not have noticed.

### Machine Learning Workflow
To implement population segmentation, you'll go through a number of steps:

-Data loading and exploration
-Data cleaning and pre-processing
-Dimensionality reduction with PCA
-Feature engineering and data transformation
-Clustering transformed data with k-means
-Extracting trained model attributes and visualizing k clusters

These tasks make up a complete, machine learning workflow from data loading and cleaning to model deployment. Each exercise is designed to give you practice with part of the machine learning workflow, and to demonstrate how to use SageMaker tools, such as built-in data management with S3 and built-in algorithms.


