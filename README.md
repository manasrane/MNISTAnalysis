# 🖊️ Handwritten Digit Recognition with MNIST (CNN – TensorFlow/Keras)

This Colab notebook demonstrates how to build, train, and evaluate a **Convolutional Neural Network (CNN)** for handwritten digit recognition using the **MNIST** dataset. It’s a classic deep learning problem that showcases how neural networks learn image patterns.

## 📌 Key Features

* 📚 Uses the **MNIST** dataset — 60,000 training and 10,000 test grayscale digit images (28x28 pixels)
* 🧠 Implements a CNN from scratch using **TensorFlow** and **Keras**
* ⚙️ Includes model training, evaluation, and visualization
* 📉 Plots training/validation accuracy and loss
* ✅ Achieves high accuracy (>98%) on test data

## 🧱 Architecture Overview

```text
Input (28x28x1)
→ Conv2D → ReLU → MaxPooling
→ Conv2D → ReLU → MaxPooling
→ Flatten
→ Dense → ReLU
→ Dense (10 neurons for digits 0–9) → Softmax
```

## 🚀 How to Use

1. Open the notebook in Colab:
   👉 [Open in Google Colab](https://colab.research.google.com/drive/1LGwlSfBBk-q01ab8YpCo1PTIbxwuUP85?usp=sharing)

2. Run all cells in order:

   * 📥 Load and preprocess data
   * 🏗️ Build the CNN model
   * 🏋️‍♂️ Train and evaluate
   * 📊 Visualize predictions and metrics

3. (Optional) Modify the architecture or add dropout/regularization for experimentation.

## 🛠️ Libraries Used

* `TensorFlow`
* `Keras`
* `Matplotlib`
* `NumPy`

*All libraries are pre-installed in Google Colab.*

## 📊 Results

* High accuracy on unseen test data
* Confusion matrix and sample prediction visualizations
* Graphs of training/validation loss and accuracy over epochs

## 📌 Try Extending

* Add dropout or batch normalization
* Use different optimizers (Adam, RMSprop, SGD)
* Test on custom handwritten digit images
* Convert to a model that can run on mobile (TFLite)

---

## 🔗 Link

📘 [Run in Google Colab](https://colab.research.google.com/drive/1LGwlSfBBk-q01ab8YpCo1PTIbxwuUP85?usp=sharing)

---
