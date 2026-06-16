# Gravitational Wave Signal Classification using Deep Learning (CNN)

## Project Overview

The project deals with identifying and recognizing gravitational wave signals through noisy space signals using deep learning. The CNN is trained to classify patterns that occur in spectrograms related to different kinds of gravitational wave signals.

Gravitational waves are distortions in space-time that arise due to catastrophic celestial events like black hole collisions. These are difficult to detect due to the presence of significant amounts of noise.
---

##  Objective

* Build a deep learning model to classify gravitational wave signals
* Automatically distinguish between real signals and noise
* Analyze model performance using multiple evaluation metrics

---

##  Methodology

### 1. Data Preprocessing

* Input data consists of spectrogram images
* Images are resized to a uniform shape (128x128)
* Pixel values are normalized for better training

### 2. Model Architecture

* Convolutional Neural Network (CNN) used for feature extraction
* Multiple Conv2D and MaxPooling layers
* Dropout layer added to prevent overfitting
* Softmax activation for multi-class classification

### 3. Training Process

* Model trained on labeled dataset
* Validation data used to monitor performance
* Early stopping and checkpoints used (if implemented)

### 4. Evaluation Metrics

* Accuracy
* Loss curves
* Confusion Matrix
* ROC / Precision-Recall curves
* Top-K Accuracy

---

## Results And Visualizations

The following are the visualizations  generated to evaluate the model:

*  Training Accuracy vs Validation Accuracy
*  Training Loss vs Validation Loss
*  Confusion Matrix (Normalized)
*  ROC Curve (Multi-class)
*  Precision-Recall Curve
* Sample Predictions (Correct vs Incorrect)

##  Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
## How to Run the Project
### Run on Google Colab
Open the notebook directly:
https://colab.research.google.com/github/Anushka-Pokhriyal/Gravitational-Wave-Signal-Classification/blob/main/Gravitational_Wave_Signal_Classification.ipynb
### Run Locally
1. Clone the repository:
```bash
git clone https://github.com/Anushka-Pokhriyal/Gravitational-Wave-Signal-Classification.git
```
2. Install dependencies:
```bash
pip install tensorflow numpy matplotlib scikit-learn
```
3. Open the notebook:
* Run in Jupyter Notebook or Google Colab
## Key Learnings
* Understanding of CNNs for image classification
* Handling noisy real-world data
* Model evaluation using multiple metrics
* Visualization of model performance
## Some of the Screenshots

## confusion matrix

<img width="567" height="471" alt="image" src="https://github.com/user-attachments/assets/367ee54e-b96e-468d-88dd-10a67732f115" />
## Audio/Signal Classification evaluation

<img width="437" height="482" alt="image" src="https://github.com/user-attachments/assets/2be0b223-8360-47b9-919c-78108191125f" />
## ROC Curve

<img width="760" height="601" alt="image" src="https://github.com/user-attachments/assets/b0e9fbd6-631e-44e3-8b90-026e0a3dd954" />
## Class Distributions

<img width="955" height="652" alt="image" src="https://github.com/user-attachments/assets/a75031b8-d966-4b32-9940-362c05fc206f" />
## Precision Recall Curve

<img width="763" height="603" alt="image" src="https://github.com/user-attachments/assets/a7483fe5-45a2-4582-b321-974828b9d67f" />

##  Applications

* Detection of black hole collisions
* Space research and astrophysics
* Signal classification in noisy environments

---

##  Author

**Anushka Pokhriyal**

---

##  Acknowledgment

Dataset inspired by gravitational wave detection research (Gravity Spy / Kaggle)
(https://www.kaggle.com/datasets/tentotheminus9/gravity-spy-gravitational-waves)

---
