# Alphabet Soup Charity Neural Network Model

This project builds and optimizes a deep learning neural network to predict the success of charity funding applications for Alphabet Soup.

## Overview

The goal of this analysis is to create a neural network model that can accurately classify whether funding applicants will be successful, based on their features. Two models were built:
- **Initial Model**: A basic neural network with two hidden layers.
- **Optimized Model**: A more complex network with additional neurons and dropout layers to improve performance.

## Files

- **AlphabetSoupCharity.ipynb**: Code for the initial model.
- **AlphabetSoupCharity_Optimization.ipynb**: Code for the optimized model.
  
## Results

- **Initial Model**
  - Accuracy: 72.78%
  - Loss: 0.5585

- **Optimized Model**
  - Accuracy: 73.80%
  - Loss: 0.5434

## How to Run

1. Clone the repository.
2. Open the Jupyter notebooks in Google Colab or locally.
3. Run the cells to train and evaluate the models.

## Conclusion

The optimized model showed slight improvement over the initial model. Further model tuning or trying alternative models such as Random Forest or XGBoost could improve accuracy for this classification task.
