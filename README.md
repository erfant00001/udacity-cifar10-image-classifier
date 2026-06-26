# CIFAR-10 Image Classifier

![Python](https://img.shields.io/badge/Python-3.x-blue) ![PyTorch](https://img.shields.io/badge/PyTorch-CNN-ee4c2c) ![License](https://img.shields.io/badge/License-MIT-green) ![Udacity](https://img.shields.io/badge/Udacity-Intro%20to%20Machine%20Learning-02b3e4)

A **Convolutional Neural Network**, built from scratch in PyTorch, that classifies images from the **CIFAR-10** dataset into 10 categories (plane, car, bird, cat, deer, dog, frog, horse, ship, truck).

> Completed for the **Udacity — Intro to Machine Learning Nanodegree**.

## Overview

The network stacks convolutional + max-pooling layers into a fully-connected classifier with dropout, trained with the Adam optimiser and cross-entropy loss. CIFAR-10 is loaded directly through `torchvision`, normalised, and trained over several epochs while tracking the training loss; the model is then evaluated on the held-out test set. The project target is **>70%** test accuracy.

## Files

| File | Description |
|------|-------------|
| `CIFAR-10_Image_Classifier-STARTER.ipynb` | The complete project notebook |
| `CIFAR-10_Image_Classifier-STARTER-2.html` | Rendered HTML export (tracked via Git LFS) |
| `cifar10_model.pth` | Saved model weights (tracked via Git LFS) |

## Getting started

```bash
pip install torch torchvision matplotlib numpy tqdm
jupyter notebook "CIFAR-10_Image_Classifier-STARTER.ipynb"
```

The notebook downloads CIFAR-10 automatically via `torchvision.datasets.CIFAR10(download=True)`.

## Acknowledgements

Starter notebook and specification provided by **Udacity** (*Intro to Machine Learning Nanodegree*). Implementation by Erfan Taatizadeh.

## ⚠️ Academic integrity

Shared as a personal portfolio / learning reference. If you are enrolled in this Nanodegree, do **not** submit this code as your own — see the [Udacity Honor Code](https://www.udacity.com/legal/en-us/honor-code).

## License

[MIT License](LICENSE) for the author's contributions; Udacity starter code remains Udacity's property.
