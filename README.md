# 🍷 Wine Quality Prediction

This project uses a neural network built with TensorFlow and Keras to predict the quality of wine based on its physicochemical properties.

## 📊 Dataset
The dataset used is `WineQT.csv`, containing features like:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

**Target:** Wine quality score (integer)

## 🧠 Model Architecture
- **Type:** Sequential Neural Network
- **Layers:**
  - Dense (256 neurons, ReLU, L2 Regularization)
  - Dense (256 neurons, ReLU, L2 Regularization)
  - Dense (128 neurons, ReLU, L2 Regularization)
  - Dense (11 neurons, Softmax activation)
- **Loss:** SparseCategoricalCrossentropy
- **Optimizer:** Adam (`learning_rate=0.001`)
- **Metric:** Accuracy

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wine-quality-prediction.git
   cd wine-quality-prediction
