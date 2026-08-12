# Cat vs Dog Image Classification using PyTorch CNN

## Overview

This project focuses on building a **Convolutional Neural Network (CNN) from scratch using PyTorch** to classify images into two categories:

- Cat
- Dog

The project demonstrates a complete deep learning workflow, including data loading, visualization, custom dataset creation, CNN architecture design, model training, evaluation, and prediction.

---

## Project Highlights

- Building a CNN model from scratch using PyTorch
- Implementing a custom Dataset class
- Using DataLoader for efficient batch processing
- Image preprocessing and normalization
- Training and validation monitoring
- Learning rate scheduling
- Early stopping to reduce overfitting
- Evaluation using accuracy and confusion matrix
- Visualizing model predictions on test images

---

## Dataset

The dataset contains two classes:

- Cats
- Dogs

The images were loaded, explored, and visualized before training to understand the dataset distribution and image samples.

---

## Methodology

The project follows a complete computer vision pipeline:

```
Input Images
      |
      |
Image Preprocessing
      |
      |
Custom PyTorch Dataset
      |
      |
DataLoader
      |
      |
Custom CNN Architecture
      |
      |
Training & Validation
      |
      |
Evaluation & Prediction
```

---

## Data Preprocessing

The preprocessing pipeline includes:

- Resizing images to a fixed size
- Converting images into tensors
- Normalizing image values

The training pipeline was prepared using PyTorch transforms.

---

## Custom Dataset

A custom PyTorch Dataset class was implemented to:

- Load image paths
- Apply transformations
- Return images with their corresponding labels

This creates a flexible and reusable data pipeline.

---

## CNN Architecture

A custom CNN model was built from scratch using PyTorch.

The architecture consists of:

- Multiple convolutional layers for feature extraction
- Activation functions
- Pooling layers
- Fully connected layers for classification

Architecture overview:

```
Input Image
     |
Conv2D Layer
     |
Activation Function
     |
Pooling Layer
     |
Conv2D Layers
     |
Pooling
     |
Fully Connected Layers
     |
Cat / Dog Prediction
```

---

## Training Strategy

The model was trained using:

- PyTorch
- Adam optimizer
- Cross Entropy Loss
- Learning rate scheduler
- Early stopping

Training performance was monitored using:

- Training loss
- Validation loss
- Training accuracy
- Validation accuracy

---

## Evaluation

The model was evaluated using:

- Validation accuracy
- Confusion matrix
- Test predictions visualization

The confusion matrix was used to analyze classification performance and identify prediction errors.

---

**Custom CNN built from scratch using PyTorch**

## Repository Structure

```
Cat-Dog-PyTorch-CNN/

│
├── cat-vs-dog-image-classification-with-pytorch-cnn.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/your_username/your_repository.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
cat-vs-dog-image-classification-with-pytorch-cnn.ipynb
```

and run the cells sequentially.

---

## Model Weights

The trained CNN model weights are not included in this repository because the file size exceeds GitHub upload limitations.

The complete training pipeline is available in the notebook, and the model can be reproduced by running the training process.

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PIL

---

## Future Improvements

Possible improvements include:

- Adding stronger data augmentation techniques
- Using transfer learning with pretrained models such as ResNet or DenseNet
- Hyperparameter optimization
- Deploying the model using an API
- Optimizing inference speed

---

## Disclaimer

This project is developed for educational purposes to demonstrate deep learning and computer vision techniques.
