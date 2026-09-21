# Intel Image Classification — CNN & Transfer Learning

## Project Overview

This project is a Computer Vision system for classifying natural scene images into six different categories using Deep Learning.

The project uses two approaches:

1. A CNN model built from scratch.
2. A Transfer Learning model using MobileNetV2.

The goal is to compare both models and evaluate their performance on unseen test images.

## Dataset

The project uses the Intel Image Classification dataset.

The dataset contains six classes:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

The images are RGB natural-scene images.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow

The project follows these main steps:

1. Dataset Loading
2. Dataset Understanding
3. Exploratory Data Analysis (EDA)
4. Image Preprocessing
5. Data Augmentation
6. CNN Model Building
7. Model Training
8. Model Evaluation
9. Error Analysis
10. Transfer Learning using MobileNetV2
11. Model Comparison

## Models

### 1. Baseline CNN

A CNN model was built from scratch using TensorFlow/Keras.

**Test Accuracy:** 73.53%

### 2. MobileNetV2 Transfer Learning

A pretrained MobileNetV2 model was used with a custom classification layer for the six scene classes.

**Test Accuracy:** 89.97%

## Results

| Model | Test Accuracy |
|------|---------------|
| Baseline CNN | 73.53% |
| MobileNetV2 | 89.97% |

The MobileNetV2 model achieved a higher test accuracy than the baseline CNN.

## Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Error analysis was also performed to examine incorrectly classified images.

## How to Run the Project

1. Open the notebook in Google Colab.
2. Upload or connect the Intel Image Classification dataset.
3. Run the notebook cells from top to bottom.
4. The notebook will load and preprocess the images.
5. The CNN model will be trained and evaluated.
6. The MobileNetV2 transfer learning model will then be trained and evaluated.

## Files

- `Intel_Image_Classification_CNN_Transfer_Learning.ipynb` — Main project notebook.

## Conclusion

This project demonstrates an end-to-end image classification pipeline using both a CNN built from scratch and transfer learning with MobileNetV2.

The results show the performance of both approaches on the Intel Image Classification dataset.
