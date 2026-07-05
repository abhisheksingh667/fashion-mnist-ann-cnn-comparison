# 👕 Fashion MNIST Image Classification using Deep Learning

A beginner-friendly Deep Learning project that compares the performance of three neural network architectures—**Perceptron**, **Artificial Neural Network (ANN)**, and **Convolutional Neural Network (CNN)**—on the Fashion MNIST dataset.

This project demonstrates the complete deep learning workflow, from data preprocessing to model training, evaluation, and performance comparison.

---

## 📌 Project Objective

The goal of this project is to classify grayscale images of fashion products into one of **10 clothing categories** using different neural network architectures and compare their performance.

The project helps understand:

- Image preprocessing
- Neural Networks
- Deep Learning fundamentals
- CNN architecture
- Model evaluation
- Performance comparison

---

## 📂 Dataset

**Dataset:** Fashion MNIST

The dataset contains:

- **60,000** Training Images
- **10,000** Testing Images
- Image Size: **28 × 28 pixels**
- Color: **Grayscale**
- **10 Classes**

### Clothing Categories

| Label | Class |
|--------|----------------|
| 0 | T-shirt/Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle Boot |

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn

---

# 📊 Project Workflow

1. Load Dataset
2. Data Exploration
3. Data Preprocessing
4. Normalize Pixel Values
5. One-Hot Encode Labels
6. Build Deep Learning Models
7. Train Models
8. Evaluate Performance
9. Compare Results
10. Visualize Training Curves

---

# 🤖 Models Implemented

## 1️⃣ Perceptron

Architecture:

```
Input
   ↓
Flatten
   ↓
Dense (Softmax)
```

A single-layer neural network that serves as the baseline model.

---

## 2️⃣ Artificial Neural Network (ANN)

Architecture:

```
Input
   ↓
Flatten
   ↓
Dense(128)
   ↓
Dense(64)
   ↓
Output Layer
```

Learns non-linear relationships between image pixels and improves classification performance compared to the Perceptron.

---

## 3️⃣ Convolutional Neural Network (CNN)

Architecture:

```
Input Image
      ↓
Conv2D
      ↓
MaxPooling
      ↓
Conv2D
      ↓
MaxPooling
      ↓
Flatten
      ↓
Dense
      ↓
Output Layer
```

CNN automatically learns important image features such as edges, textures, and shapes, making it the best-performing model.

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

Training and validation curves were plotted to analyze the learning behavior of each model.

---

# 📊 Results

| Model | Purpose |
|---------|----------|
| Perceptron | Baseline Model |
| ANN | Learns complex non-linear patterns |
| CNN | Learns spatial image features and provides the best accuracy |

**Observation:**

- Perceptron provides the lowest performance.
- ANN significantly improves classification accuracy.
- CNN achieves the highest accuracy by extracting spatial features from images.

---

# 📚 Key Concepts Learned

- Image Classification
- Data Normalization
- One-Hot Encoding
- Dense Layers
- Activation Functions
- Softmax Classification
- Forward Propagation
- Backpropagation
- Convolution Layer
- Pooling Layer
- Model Evaluation
- Deep Learning Workflow

---

# 🚀 Future Improvements

- Add Dropout layers
- Hyperparameter tuning
- Data Augmentation
- Confusion Matrix
- Precision, Recall & F1-Score
- Model Saving and Loading
- TensorBoard Integration

---

# 📁 Project Structure

```
Fashion-MNIST-Deep-Learning/
│
├── CNN_first.ipynb
├── fashion-mnist_train.csv
├── fashion-mnist_test.csv
├── README.md
```

---

# 💡 What This Project Demonstrates

This project demonstrates the progression from a simple neural network to an advanced Convolutional Neural Network for image classification.

It highlights:

- End-to-end Deep Learning workflow
- Image preprocessing techniques
- Neural Network implementation using TensorFlow/Keras
- Performance comparison between Perceptron, ANN, and CNN
- Practical understanding of CNNs for computer vision tasks

---

## 👨‍💻 Author

**Abhishek Singh**

- GitHub: https://github.com/abhisheksingh667

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
