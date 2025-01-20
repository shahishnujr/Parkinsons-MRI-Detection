# Parkinson's Disease Detection from MRI Images

This repository contains the implementation of a hybrid convolutional neural network (CNN) model with quantum-inspired layers designed for the early diagnosis of Parkinson's disease using MRI images. The project showcases an innovative approach to medical imaging analysis, achieving high accuracy and demonstrating potential clinical applications.

## Features
- Utilizes MRI scans for accurate classification of Parkinson's disease.
- Incorporates a quantum-inspired fully connected layer to enhance feature extraction and model performance.
- Achieves **97.16% accuracy on the validation set**.

## Dataset
The dataset used in this project is the **NTUA Parkinson Dataset**:
- Includes MRI scans of 150 subjects (75 Parkinson's disease patients and 75 healthy controls).
- Preprocessed to grayscale, resized to 28x28 pixels, and normalized.
- [Access the dataset here](https://www.kaggle.com/datasets/shayalvaghasiya/ntua-parkinsons).

## Model Architecture
- **Convolutional Layers** for feature extraction.
- **Max Pooling** for dimensionality reduction.
- **Quantum-Inspired Fully Connected Layer** for enhanced pattern recognition.
- Softmax activation for binary classification (Parkinson's vs. Non-Parkinson's).

## Results
The model was trained and validated using the NTUA Parkinson Dataset:
- **Training Accuracy**: 97.33%
- **Validation Accuracy**: 97.16%

## Preprocessing Steps
1. Conversion to grayscale.
2. Resizing images to 28x28 pixels.
3. Normalization of pixel values to [0,1].

## Visualizations
- Loss and Accuracy plots.
- Activation Maps to highlight regions of interest in MRI scans.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Parkinsons-MRI-Detection.git
2. Navigate to the project directory:
cd Parkinsons-MRI-Detection
3. Run the Jupyter Notebook:
jupyter notebook parkinsson_detection.ipynb
