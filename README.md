# 🧠 MNIST Handwritten Digit Classification using PyTorch

A simple Artificial Neural Network (ANN) built with PyTorch to classify handwritten digits from the MNIST dataset. The project demonstrates the complete deep learning workflow—from loading and preprocessing data to training, evaluating, making predictions, and saving the trained model.

---

## 📌 Features

- Load and preprocess the MNIST dataset
- Build a fully connected Artificial Neural Network (ANN)
- Train the model using PyTorch
- Evaluate model performance on the test dataset
- Predict handwritten digits
- Save the trained model for future use

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- Matplotlib

---

## 📂 Project Structure

```
├── MNISTproject.ipynb      # Main notebook
├── mnist_model.pth         # Saved trained model
├── data/                   # MNIST dataset (downloaded automatically)
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mnist-ann-pytorch.git
cd mnist-ann-pytorch
```

### 2. Install dependencies

```bash
pip install torch torchvision matplotlib
```

### 3. Run the notebook

Open the notebook using Jupyter Notebook or VS Code.

```bash
jupyter notebook MNISTproject.ipynb
```

---

## 🧠 Model Architecture

The model is a simple feed-forward Artificial Neural Network (ANN).

- **Input Layer:** 784 neurons (28 × 28 flattened image)
- **Hidden Layer(s):** Fully Connected Layers with ReLU activation
- **Output Layer:** 10 neurons (Digits 0–9)

---

## 📊 Dataset

The project uses the **MNIST** handwritten digit dataset.

- 60,000 training images
- 10,000 testing images
- Image size: **28 × 28**
- Classes: **0–9**

---

## 🔮 Prediction

The notebook includes a prediction section where:

- A test image is displayed.
- The trained model predicts the digit.
- The actual and predicted labels are printed for comparison.

---

## 💾 Saving the Model

The trained model is saved using:

```python
torch.save(model.state_dict(), "mnist_model.pth")
```

You can later load it using:

```python
model.load_state_dict(torch.load("mnist_model.pth"))
model.eval()
```

---

## 📈 Future Improvements

- Add Convolutional Neural Network (CNN)
- Hyperparameter tuning
- Model accuracy visualization
- Confusion matrix
- TensorBoard integration
- Deploy using Streamlit or Flask

---

## 🎯 Learning Outcomes

This project helped in understanding:

- PyTorch tensors
- Neural Networks
- Forward propagation
- Backpropagation
- Loss functions
- Optimizers
- Model evaluation
- Saving and loading models

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Hitesh**

Aspiring AI/ML Engineer | Data Analyst | Deep Learning Enthusiast

Feel free to connect and share feedback!
