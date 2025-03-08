# Medical-TL-MobileNet

## Introduction

This repository, **Medical-TL-MobileNet**, explores **transfer learning** using **MobileNetV2** for **medical image classification**. The project demonstrates how pre-trained deep learning models can be fine-tuned to classify medical images accurately, enabling AI-assisted diagnostics in healthcare.

## Key Features

- **Transfer Learning with MobileNetV2**: Utilizes a pre-trained MobileNetV2 model for efficient feature extraction.
- **Medical Image Processing**: Works with medical imaging datasets for classification tasks.
- **Fine-Tuning the Model**: Adjusts model layers for improved accuracy on medical data.
- **Performance Evaluation**: Analyzes model accuracy, loss, precision, recall, and confusion matrix.
- **Data Augmentation**: Enhances model generalization with transformations such as flipping and rotation.

## Installation

Ensure you have the required dependencies installed before running the notebook:

```bash
pip install numpy matplotlib tensorflow keras opencv-python jupyter
```

## Usage

Follow these steps to run the notebook:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Medical-TL-MobileNet
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook assignment4_Mohammed_Ali.ipynb
   ```
3. Run the notebook step by step to train and evaluate the transfer learning model.

## Dataset Overview

This project is designed for medical image classification and can be applied to datasets such as:
- **Chest X-rays (Pneumonia vs. Normal)**
- **MRI Scans (Brain Tumor Detection)**
- **Skin Lesion Classification (Melanoma vs. Benign)**

## Model Implementation

- **Pre-trained Model**: MobileNetV2 (initialized with ImageNet weights)
- **Custom Fully Connected Layers**: Added to fine-tune for medical image classification
- **Activation Functions**: ReLU, Softmax
- **Optimizer**: Adam
- **Loss Function**: Categorical Cross-Entropy

## Evaluation Metrics

- **Accuracy & Loss Plots**
- **Precision & Recall Scores**
- **Confusion Matrix Analysis**
- **ROC-AUC Curve**

## Applications

This project can be applied to various medical imaging domains, including:
- **Radiology**: Automated disease detection in X-rays and MRIs
- **Dermatology**: Skin lesion classification for early melanoma detection
- **Pathology**: Histopathology image classification for cancer diagnosis

## Contribution

This repository is open for contributions. Feel free to fork, modify, and submit pull requests.

## License

This project is distributed under an open-source license and is intended for educational and research purposes.

## Author

- **Mohammed Ali Ali**  
  Cairo University - Faculty of Engineering

