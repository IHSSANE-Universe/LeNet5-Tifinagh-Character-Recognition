# LeNet-5 for Tifinagh Character Recognition

## Description

This project implements a modified **LeNet-5 Convolutional Neural Network (CNN)** for handwritten **Tifinagh character recognition**.

The model is trained on the **Amazigh Handwritten Character Dataset (AMHCD)** to classify **33 Tifinagh characters**.

## Architecture

32×32×1 ↓ Conv2D (6 filters, 5×5) ↓ Average Pooling (2×2) ↓ Conv2D (16 filters, 5×5) ↓ Average Pooling (2×2) ↓ Dense (120) ↓ Dense (84) ↓ Output (33 classes)


## Experiments

Two optimizers are evaluated:

- **SGD**
- **Adam**

The project includes:

- Image preprocessing and normalization
- Train / validation / test split
- Accuracy and loss curves
- Confusion matrix
- Classification report
- Feature map visualization
- Model performance comparison

## Dataset

[Amazigh Handwritten Character Dataset (AMHCD)](https://www.kaggle.com/datasets/benaddym/amazigh-handwritten-character-database-amchdc)

## Project Structure

LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998).  
*Gradient-Based Learning Applied to Document Recognition.*
