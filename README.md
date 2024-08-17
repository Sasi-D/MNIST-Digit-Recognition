# MNIST-Dimensionality-Reduction
This project explores dimensionality reduction techniques using the MNIST dataset. It applies both PCA and Kernel PCA algorithms to analyze and visualize the data, reconstruct images, and assess the effectiveness of different kernels for digit classification.


### PART I :  
This section involves the implementation of Principal Component Analysis (PCA) on the MNIST dataset. The goal is to calculate various principal components and analyze them by plotting the corresponding images along with their explained variance. This helps in visualizing the most significant features of the dataset, revealing how much of the data's variance is captured by each principal component.

### PART II :
This section focuses on reconstructing the MNIST dataset using different numbers of principal components and selecting the optimal number of components, "d". By varying "d", we aim to balance dimensionality reduction with reconstruction accuracy, ultimately identifying the most suitable "d" that preserves essential data features while minimizing information loss.

### PART III :
This section explores the use of various kernel functions to implement Kernel Principal Component Analysis (Kernel PCA). The goal is to select the optimal kernel by evaluating and comparing their performance, with a focus on understanding the behavior of each kernel. By analyzing how different kernels transform the data, we aim to identify the most effective one for capturing the underlying structure of the dataset.
