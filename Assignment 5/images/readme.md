# CIFAR-10 & CIFAR-10-C Datasets

This repository contains the **CIFAR-10** dataset for standard classification benchmarking and the **CIFAR-10-C** (Common Corruptions) dataset for evaluating model robustness against common image corruptions.

## 📂 Directory Structure

The datasets are organized into their respective parent directories as follows:

```text
.
├── CIFAR-10/              # Standard CIFAR-10 Dataset
│   ├── cifar-10-batches-py
│
├── CIFAR-10-C/            # Corrupted CIFAR-10 Dataset
│   ├── labels.npy
│   ├── brightness.npy
│   ├── contrast.npy
│   ├── defocus_blur.npy
│   ├── elastic_transform.npy
│   ├── ... (other corruption files)
│   └── zoom_blur.npy
│
└── README.md
```

## Setup CIFAR-10

```bash
mkdir CIFAR-10

wget [https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)

tar -xzvf cifar-10-python.tar.gz -C CIFAR-10
```

## Setup CIFAR-10

```bash
mkdir CIFAR-10-C

wget [https://zenodo.org/record/2535967/files/CIFAR-10-C.tar](https://zenodo.org/record/2535967/files/CIFAR-10-C.tar)

tar -xvf CIFAR-10-C.tar
```

## Cleanup

```bash
rm cifar-10-python.tar.gz CIFAR-10-C.tar
```
