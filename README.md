# Customer Purchase Prediction (Neural Network from Scratch)

This project builds a neural network from scratch using NumPy to predict whether a customer will make a purchase based on their online behavior.

## Project Overview

The goal of this project is to understand how a neural network works internally and apply it to a practical use case. The model is trained on the Online Shoppers Intention dataset and learns patterns in user behavior to make predictions.

## What is implemented

- Data preprocessing using pandas  
- Conversion of categorical variables into numerical format  
- Feature normalization  
- Train/test split  
- Neural network with two hidden layers  
- ReLU activation for hidden layers  
- Sigmoid activation for output layer  
- Forward propagation  
- Backpropagation  
- Gradient descent for weight updates  
- Model evaluation using accuracy  

## Model Structure

Input layer → Hidden layer (32 neurons) → Hidden layer (16 neurons) → Output layer (1 neuron)

The output represents the probability that a customer will make a purchase.

## Training Process

The model follows these steps:

1. Make predictions using forward propagation  
2. Compare predictions with actual values  
3. Calculate error  
4. Propagate the error backward through the network  
5. Update weights to reduce error  

This process is repeated over multiple iterations to improve performance.

## Results

The model outputs a probability between 0 and 1. A threshold of 0.5 is used to classify whether a customer is likely to make a purchase.

Performance is evaluated using accuracy on the test dataset.

## Tech Stack

- Python  
- NumPy  
- Pandas  

## What I learned

This project helped me understand:

- How neural networks work at a mathematical level  
- How forward and backward propagation are implemented  
- The role of activation functions  
- How gradient descent updates model parameters  
- How to prepare data for machine learning models  

## Future improvements

- Add more evaluation metrics (precision, recall)  
- Visualize training performance  
- Tune hyperparameters  
- Compare with other models such as logistic regression  

## Author

Shuang-Lin "Marvin" Chen  
Data Analytics student at Hyper Island
