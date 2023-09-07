# Classification Perceptron Analysis
### Description:
Explore problem categorization in ML using Mitchell's perspective. Evaluate tasks, implement the Pocket algorithm-based Perceptron model 
for classification. Analyze convergence, report accuracy, and visualize results. A concise guide to ML classification and algorithmic implementation.
### Problem Categorization and Evaluation:
- Categorizing tasks according to Tom Mitchell's ML definition.
- Defining evaluation criteria based on past experiences.
- Determining supervised/unsupervised nature, mentioning sub-branches for supervised problems.

### Perceptron Algorithm Implementation:
- Reading and interpreting the provided dataset structure.
- Visualizing class examples in a 2D space.

### Convergence Analysis and Implementation:
- Analyzing the convergence of the Pocket algorithm-based Perceptron model.
- Explaining the convergence behavior.

### Perceptron Model Training and Evaluation:
- Implementing the Perceptron model based on the Pocket algorithm.
- Training on the provided dataset, running Pocket algorithm if needed.
- Reporting accuracy on training and test data.
- Visualizing training and test data with the learned Perceptron's separating line.


# Regression Analysis and Model Evaluation
### Description:
Implement linear regression models, perform polynomial feature extraction, evaluate and analyze model performance.
### Linear Regression with Polynomial Features:
1. Implement linear regression using the normal equation.
2. Perform degree 5 polynomial feature extraction.

### Polynomial Regression Analysis:
1. Train independent polynomial regression models of degree 5.
2. Evaluate models with 10, 25, 50, and 200 train samples.
3. Report MSE on training and test data.
4. Discuss underfitting, overfitting, and model superiority.

### Linear Regression with Regularization:
1. Standardize data based on training dataset.
2. Implement linear regression with regularization.
3. Evaluate polynomial regressions of orders 1, 3, and 5.
4. Use Repeated 5-Fold Cross-Validation with 3 regularization values.
5. Display training and evaluation errors using Boxplot.
6. Analyze overfitting, underfitting, and optimal settings.
7. Predict test data with optimal model and save results.
Feel free to copy and paste this Markdown code into your GitHub repository's README or any other relevant documentation.



# Multilayer Perceptron and Neural Network from Scratch
### 1. Building a 3-Dimensional Hidden Layer
In this initial task, we construct a neural network with a 3-dimensional hidden layer. The primary objective is to visualize and understand the decision boundary created by this network.

### 2. Varying Hidden Layer Sizes
We investigate the impact of hidden layer size on network performance. Hidden layer sizes ranging from 1 to 40 are experimented with, and decision boundaries are plotted for each size.

### 3. Mini-Batch Gradient Descent
To enhance training efficiency, we switch from batch gradient descent to mini-batch gradient descent, a more practical approach for large datasets.

### 4. Implementing Learning Rate Annealing
We implement a learning rate annealing schedule for gradient descent. This dynamic learning rate adjustment can improve convergence during training.

### 5. Exploring Activation Functions
We experiment with different activation functions for the hidden layer, exploring how they affect the network's behavior. This involves not only changing the activation function but also adapting the backpropagation process.

### 6. Handling Three Classes
The network is extended to handle three classes, requiring the creation of an appropriate dataset to support this multi-class classification task.

### 7. Four-Layer Network
Finally, we extend the network to four layers. The layer size is adjusted, necessitating updates to both forward propagation and backpropagation.
