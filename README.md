# CIFAR10-CNN-Image-Classification
CNN model to classify CIFAR-10 images using TensorFlow

# CIFAR-10 Image Classification with CNN

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔥 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset**. The CIFAR-10 dataset consists of **60,000 32x32 color images** in **10 classes** (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).  

The model achieves **~80% accuracy** on the test set using a simple CNN architecture.

---

## 🛠 Tools & Technologies
- Python 3.10+
- TensorFlow
- NumPy
- Matplotlib

---

## 🧠 How It Works
1. **Load Dataset:** CIFAR-10 is automatically downloaded using TensorFlow.  
2. **Normalize Data:** Pixel values scaled to 0–1 for faster learning.  
3. **CNN Architecture:**
   - Conv2D → MaxPooling2D → Conv2D → MaxPooling2D → Conv2D
   - Flatten → Dense → Output (Softmax)
4. **Compile Model:** Using `Adam` optimizer and `sparse_categorical_crossentropy` loss.
5. **Train Model:** Model is trained over 10 epochs with training and validation accuracy tracking.
6. **Evaluate Model:** Test accuracy is reported, and predictions can be made on sample images.

---

## 📊 Results
- **Test Accuracy:** ~80%
- **Training Visualization:**  
  ![Accuracy Graph](example_graph.png) *(Replace with your own graph screenshot)*

---

## 🚀 How to Run
1. Clone this repository:
```bash
git clone https://github.com/YourUsername/CIFAR10-CNN-Image-Classification.git
