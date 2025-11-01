# EN3150 Assignment 03: CNN Image Classification

This repository contains the code for the EN3150 Pattern Recognition assignment. The project involves building two custom Convolutional Neural Networks (CNNs) to classify the MNIST dataset and comparing their performance against SOTA models (ResNet50 and VGG16) and different optimizers.

---

## 🚀 Tasks Completed

### Task 1: Custom CNN & Optimizer Comparison
* **Notebook:** `CNN.ipynb`
* Built a custom CNN for 28x28 MNIST images.
* Compared the performance of three optimizers:
    1.  **Adam** (Best: 99.17% Accuracy)
    2.  **SGD with Momentum** (98.96% Accuracy)
    3.  **SGD (Standard)** (97.91% Accuracy)

### Task 2: Comparison with SOTA Models
* **Notebook:** `Part2 new.ipynb`
* Preprocessed MNIST images to 224x224x3 to match SOTA model inputs.
* Built a 224x224 Custom CNN baseline.
* Fine-tuned **ResNet50** and **VGG16** using transfer learning.
* **Results:**
    * **VGG16:** 99.20% Accuracy
    * **ResNet50:** 98.62% Accuracy
    * **Custom (224x224):** 98.22% Accuracy

---

## 🛠️ How to Run

1.  Open either `CNN.ipynb` or `Part2 new.ipynb` in Google Colab.
2.  Ensure the runtime is set to **GPU** (`Runtime > Change runtime type > T4 GPU`).
3.  Run all cells sequentially.

---

## 👥 Group Members

* **Arththikan S.** - 220043F
* **Jathees S.** - 220244X
* **Sampavi J.** - 220561P
* **Thayalanesan M.** - 220637F
