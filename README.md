# Plant Disease Detection for Sustainable Agriculture

## Overview

This project uses deep learning, specifically Convolutional Neural Networks (CNNs), to detect plant diseases from leaf images. Early identification of plant diseases can help reduce crop loss, improve yield quality, and promote sustainable agricultural practices by minimizing the misuse of pesticides and chemicals.

## Features

- Detects multiple plant diseases using image classification
- CNN-based architecture for high accuracy
- Supports real-time prediction (can be deployed via web or mobile app)
- Promotes sustainable agriculture through early diagnosis

## Project Pipeline

1. **Data Collection & Preprocessing**
   - Leaf images collected from public datasets
   - Images resized, normalized, and augmented to improve model generalization

2. **CNN Model Architecture**
   - Convolutional and pooling layers to extract features
   - Fully connected layers to classify diseases
   - Activation functions (ReLU, Softmax)

3. **Training & Validation**
   - Trained on labeled dataset with proper train-validation split
   - Used metrics like accuracy, loss, precision, and recall for evaluation

4. **Prediction & Evaluation**
   - Model predicts disease type from new images
   - Evaluated using confusion matrix and classification report

5. **Deployment (Optional)**
   - Model can be integrated into a user-friendly interface (e.g., web app using Flask/Streamlit or Android app)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/plant-disease-detection.git
   cd plant-disease-detection
