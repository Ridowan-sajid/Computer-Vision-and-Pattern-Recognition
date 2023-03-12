# CVPR

**The code of KNN implement k-Nearest Neighbors (k-NN) algorithm for the CIFAR-10 dataset.
It first reads the training images from the directory and creates a list TRAIN_DATA containing the image arrays and their corresponding class labels. 
It then shuffles this list randomly and displays a sample of 50 images along with their class labels.**

**After that, the code defines a function accuracyCount that calculates the accuracy of the k-NN algorithm for a given k value using L1 and L2 distance metrics. The function takes in the training set, validation set, and the value of k, and returns the number of correct predictions for both L1 and L2 metrics.**

**The code divides the shuffled training data into 5 folds. Use the remaining 4 folds for training and the current fold for validation. It uses two different distance metrics (L1 and L2)
for calculating the distances between the training and validation images. It calculates the accuracy of the algorithm for different values of 
k (1, 3, 5, 7, 9) and records the average accuracy across the 5 folds for each value of k.
Finally, it plots two graphs showing the average accuracy for L1 and L2 metrics for different values of k.**

