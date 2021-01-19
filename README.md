# K-Nearest-Neighbour
Implementation of KNN algorithm for recognition of handwritten digits  

Algorithm
  - Start
  - S1 -> Input query 
  - S2 -> Compute distance of query from all training data points (Point refers to image with 784 features in implemented case)
  - S3 -> Sort points according to distance
  - S4 -> Select top 'k' points
  - S5 -> Count number of points with each label in these 'k' points. (Labels in implemented case are in range [0,9])
  - S6 -> Return label with maximum count
  - End
  
Dataset: https://www.kaggle.com/oddrationale/mnist-in-csv
