# Lung Cancer Prediction using Neural Networks

## Project Overview

This project involves building a neural network model to predict lung cancer risk based on various health-related features. The goal is to utilize machine learning techniques to enhance early detection and improve patient outcomes.

## Model Description

The model is a neural network designed to classify whether a patient is at risk of lung cancer or not. The key features used in this model include:

- **GENDER**
- **AGE**
- **SMOKING**
- **YELLOW_FINGERS**
- **ANXIETY**
- **PEER_PRESSURE**
- **CHRONIC_DISEASE**
- **FATIGUE**
- **ALLERGY**
- **WHEEZING**
- **ALCOHOL_CONSUMING**
- **COUGHING**
- **SHORTNESS_OF_BREATH**
- **SWALLOWING_DIFFICULTY**
- **CHEST_PAIN**

### Model Architecture

- **Input Layer:** Dense layer with 5 neurons and ReLU activation
- **Hidden Layer:** Dense layer with 1 neuron and Sigmoid activation for binary classification

### Training Parameters

- **Epochs:** 100
- **Batch Size:** 32
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Validation Split:** 20%

## Results

The model achieved an accuracy of approximately **55%**(Highest using any Neural Network on Kaggle) on the test set. This represents the highest accuracy obtained using a neural network model for this dataset on Kaggle. 

**Training Performance:**
- **Training Accuracy:** Up to 55%
- **Training Loss:** Decreased and stabilized

**Validation Performance:**
- **Validation Accuracy:** Up to 55%
- **Validation Loss:** Decreased and stabilized

## Insights

- **Accuracy Trends:** The accuracy and validation accuracy both increased and stabilized over time, suggesting that the model was well-optimized.
- **Loss Trends:** Training and validation loss decreased and stabilized, indicating no overfitting.

## How to Run the Code

a. **Clone the Repository:**
   ```bash
   git clone https://github.com/himanshu07rautela/lung-cancer-prediction.git
   ```
b. **Navigate to the Project Directory:**
   ```bash
   cd lung-cancer-prediction
   ```
## Database Source
- https://www.kaggle.com/datasets/humairmunir/lung-cancer-risk-dataset

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
   
