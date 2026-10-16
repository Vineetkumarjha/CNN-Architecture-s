# Intel Image Classification using AlexNet

## Overview

This project implements the **AlexNet Convolutional Neural Network (CNN)** architecture using PyTorch to perform multi-class image classification on the Intel Image Classification Dataset. The model learns visual features from landscape images and classifies them into their corresponding environmental categories.

The model achieved **83% classification accuracy in just 10 epochs**, demonstrating the effectiveness of CNN-based deep learning for image recognition tasks.

## Dataset

The project uses the **Intel Image Classification Dataset**, which contains natural scene images belonging to six classes:

- **Buildings**
- **Forest**
- **Glacier**
- **Mountain**
- **Sea**
- **Street**

The dataset is organized into training, testing, and prediction image folders.

## Model Architecture

**AlexNet** is a pioneering CNN architecture designed for large-scale image classification. This project implements the architecture in PyTorch, using convolutional layers to extract spatial features and fully connected layers to perform final classification.

Key components include:

- Convolutional layers for feature extraction
- ReLU activation functions for non-linearity
- Max-pooling layers for spatial downsampling
- Fully connected layers for classification
- Softmax-based class probabilities during inference, where applicable

## Results

| Metric | Result |
|---|---|
| Model | AlexNet |
| Framework | PyTorch |
| Dataset | Intel Image Classification |
| Training Epochs | 10 |
| Classification Accuracy | **83%** |

*Note: The reported accuracy depends on the evaluation dataset and the metric used.*

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Project Structure

```text
CNN-Architecture-s/
├── Alexnet/
│   └── AlexNet implementation notebook
├── Intel.pt
└── README.md
```

*Update the folder and notebook names above to match your actual repository structure.*

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Vineetkumarjha/CNN-Architecture-s.git
cd CNN-Architecture-s
```

### 2. Install dependencies

```bash
pip install torch torchvision numpy matplotlib jupyter
```

### 3. Run the notebook

Open the AlexNet notebook in Jupyter Notebook or VS Code, configure the dataset paths, and execute the cells to train or evaluate the model.

The trained model weights are provided in `Intel.pt` through Git Large File Storage (Git LFS).

## Key Learning Outcomes

- Understanding the implementation of AlexNet using PyTorch
- Applying CNNs to multi-class image classification
- Working with image datasets and preprocessing pipelines
- Training and evaluating a deep learning model
- Saving and loading trained model weights

## Future Improvements

- Experiment with different learning rates and optimizers
- Apply data augmentation to improve generalization
- Compare AlexNet performance with VGG, GoogLeNet, and ResNet
- Evaluate precision, recall, F1-score, and a confusion matrix
- Explore transfer learning and fine-tuning

## Author

**Vineet Kumar Jha**

GitHub: [@Vineetkumarjha](https://github.com/Vineetkumarjha)

