# Comparison_of_MLmodel_DLmodel_digits_classification
This project aims in finding out the efficiency and difference between ML and DL models 
This project was performed against two different digits dataset:
1) Hand written digits (MNIST dataset)
2) Synthetic digits( generated using matlab)

Both machine learning and DL models were trained and tested against these two datasets.
Random forest and a CNN created from scratch were used to train against these datasets.
The observations are as follows:
As usual the models performed well when trained and tested on same dataset
But in both cases when model was trained using MNIST and tested against synthetic performed poorly and the possible reason is that images in synthetic data were rotated in different angles and whereas MNIST had no such type of rotations and also both are generated using different data distributions.
In contrary, when viceversa was done both models performed well than compared to the previous conditions and this is because the dataset had data augmentation in it.

