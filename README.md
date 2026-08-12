# Cat vs. Dog Image Classification with PyTorch CNN

## Project Overview

This project implements an end-to-end **binary image classification pipeline** using a custom **Convolutional Neural Network (CNN)** built with PyTorch.

The model is trained to classify images into two categories: **Cats** and **Dogs**.

The notebook covers the complete workflow, from dataset exploration and image preprocessing to model training, evaluation, and final inference.

## Objective

The main objective is to build and evaluate a custom CNN capable of accurately distinguishing between cat and dog images while demonstrating the key stages of a practical deep learning image classification workflow.

## Project Workflow

The project follows the following pipeline:

1. Dataset exploration and visualization
2. Class distribution analysis
3. Image preprocessing and normalization
4. Custom PyTorch Dataset implementation
5. DataLoader preparation
6. CNN architecture design
7. Model training
8. Learning-rate scheduling
9. Early stopping
10. Best model checkpointing
11. Training and validation performance visualization
12. Model evaluation
13. Classification report
14. Confusion matrix analysis
15. Test-set inference and predictions

## Model

A custom **Convolutional Neural Network (CNN)** was implemented from scratch using PyTorch.

The training pipeline includes:

- Cross-Entropy Loss
- Optimizer
- ReduceLROnPlateau learning-rate scheduler
- Early Stopping
- Best Model Checkpointing

The best-performing model was saved during training and later loaded for evaluation and inference.

## Results

The final evaluation produced the following results:

| Metric | Score |
|---|---:|
| Accuracy | **99.34%** |
| Precision | **99.28%** |
| Recall | **99.40%** |
| F1-Score | **99.34%** |

### Best Validation Performance

- **Best Validation Accuracy:** 99.64%
- **Best Validation Loss:** 0.0141
- **Best Epoch:** 14

The confusion matrix shows that the model correctly classified **7,947 out of 8,000 validation images**, with **53 misclassified images**.

```text
[[3971   29]
 [  24 3976]]
```

## Training Performance

The training process was monitored using:

- Training Loss
- Validation Loss
- Training Accuracy
- Validation Accuracy

Early stopping was used to prevent unnecessary training once the validation performance stopped improving.

## Model Evaluation

The model was evaluated using multiple classification metrics rather than relying on accuracy alone.

The evaluation includes:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow

## Project Structure

```text
cat-vs-dog-image-classification/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── cat-vs-dog-image-classification-with-pytorch-cnn.ipynb
│
└── models/
    └── best_model.pth
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Ayakhedr/cat-vs-dog-image-classification.git
cd cat-vs-dog-image-classification
```

### 2. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open the following notebook:

```text
notebooks/cat-vs-dog-image-classification-with-pytorch-cnn.ipynb
```

Run the notebook cells sequentially to reproduce the workflow.

## Key Takeaways

This project demonstrates practical experience with:

- Deep Learning
- Convolutional Neural Networks
- PyTorch
- Image preprocessing
- Custom Dataset and DataLoader
- Model training
- Learning-rate scheduling
- Early stopping
- Model checkpointing
- Classification metrics
- Confusion matrix analysis
- Model evaluation and inference
