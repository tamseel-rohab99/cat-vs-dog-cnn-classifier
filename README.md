# Cat vs Dog CNN Classifier

![Accuracy](images/accuracy.png)

## Overview
Binary image classifier built using Convolutional Neural Network (CNN) 
with TensorFlow and Keras. Model classifies images as Cat or Dog with 
94%+ training accuracy.

## Model Architecture
- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling  
- Conv2D (128 filters) + MaxPooling
- Flatten
- Dropout (0.5) 
- Dense (128, ReLU)
- Dense (1, Sigmoid)

## Results
- Training Accuracy: 94%+
- Validation Accuracy: 72%
- Total Epochs: 20
- Training Images: 1280
- Validation Images: 320

## Tasks Completed
- Task 1: Added Dropout Layer (0.5) to reduce overfitting
- Task 2: Increased epochs from 10 to 20
- Task 3: Tested model with 3 new images
- Task 4: Plotted Accuracy and Loss graphs
- Task 5: CNN explanation written

## Tech Stack
- Python 3
- TensorFlow / Keras
- Google Colab
- Matplotlib
- NumPy

## Dataset Structure
dataset/
├── train/
│   ├── cats/
│   └── dogs/
└── test/
├── cats/
└── dogs/
## How to Run
1. Open `cat_vs_dog.ipynb` in Google Colab
2. Upload dataset folder
3. Run all cells step by step

## Student Info
- Name: Tamseel
- ID: 14984
- University: City University of Science & IT, Peshawar
