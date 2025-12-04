# Assignment 5

This folder contains my solution for Assignment 5 of the [**Digital Image Processing**](https://ece.iisc.ac.in/~rajivs/#/teaching/dip) course. The primary goal of this assignment was to explore an architecture of a CNN model. Use it as a Feature Extractor and do the transfer learning for a dataset of corrupted CIFAR-10-C dataset.

---

## 📝 Problems Solved

The Jupyter Notebook `DIP_Assignment_5.ipynb` addresses the following problems:

1. **Question 1:** (Feature Extractor) Use a Pre-trained model as a Feature extractor on the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The CNN Architecture used here is ResNet50 Architecture.

2. **Question 2:** (Transfer Learning) Fine-tune the pre-trained model on a corrupted [CIFAR-10-C](https://zenodo.org/records/2535967) dataset.

3. **Question 3:** (Feature Representation Analysis) Analyse the Feature extracted from both the models on both the datasets using PCA.

---

## 📂 Files in this Folder

* `DIP_Assignment_5.ipynb`: The main Jupyter Notebook containing all code, analysis, and solutions.
* `Report 5.pdf`: Report containing all my analysis for each question along with the output achieved.
* `images`: (dataset) Contains the images which are used for the assignment (download the dataset into this folder)
* `savedData`: (savedModels) Contains the result and the saved models for future reference. (Save your trained models in this folder)
* `Problem Statements 5.pdf`: Problem statement for this assignment.

---

## 🚀 How to Run

To view and run the solution, ensure you have Jupyter installed and required packages installed. If not, then please read this [Readme](../README.md) to install the required packages.

Navigate to this directory in your terminal and launch the notebook.

```bash
jupyter DIP_Assignment_5.ipynb
```
