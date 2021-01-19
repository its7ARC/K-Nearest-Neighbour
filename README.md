# K-Nearest-Neighbour
Implementation of KNN algorithm for recognition of handwritten digits  

Algorithm
  - Start
  - S1 -> Input query 
  - S2 -> Compute L2 norm b/w query and each training data point (Point refers to image with 784 features in implemented case)
  - S3 -> Sort points in ascending order of distance
  - S4 -> Select top 'k' points
  - S5 -> Count number of points with each label in these 'k' points. (Labels in implemented case are in range [0,9])
  - S6 -> Return label with maximum count
  - End
  
Dataset: https://www.kaggle.com/oddrationale/mnist-in-csv
