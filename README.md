# VectorVision: Neural Network from Scratch

A 2-layer Neural Network implemented exclusively in NumPy to classify fashion items from the Fashion-MNIST dataset. This project demonstrates manual implementation of backpropagation and matrix calculus without high-level ML frameworks.

## 🧠 Model Architecture
* **Input Layer:** 784 neurons (28x28 grayscale pixels).
* **Hidden Layer:** 20 neurons using **ReLU** activation.
* **Output Layer:** 10 neurons using **Softmax** for multi-class classification.
* **Optimization:** Manual Gradient Descent.

## 🛠️ Setup
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the `fashion-mnist_train.csv` from [Kaggle](https://www.kaggle.com/datasets/zalando-research/fashion-mnist) and place it in the project root.
4. Open `NeuralNetwork.ipynb` to train and test the model.

## 📈 Results
The model successfully identifies items like T-shirts, boots, and dresses with high accuracy after 500 iterations.
