# Potato Disease Detection using Deep Learning

This repository contains a Convolutional Neural Network (CNN) project designed to identify and classify potato leaf diseases. It provides an automated, high-accuracy diagnostic tool aimed at supporting agricultural technology and precision farming.

## Project Overview
- **Objective:** Classify potato leaves into three categories: Early Blight, Late Blight, and Healthy.
- **Dataset:** [PlantVillage Dataset]([https://www.kaggle.com/datasets/emmarex/plantvillage-dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)) (Public domain).
- **Accuracy:** Achieved ~98% overall accuracy on the test set, with high confidence levels on individual samples.
- **Tech Stack:** Python, TensorFlow, Keras, Matplotlib, and NumPy.

## Key Features
- **Data Pipeline:** Efficient loading and preprocessing of the PlantVillage dataset.
- **CNN Architecture:** Optimized sequential model with Dropout layers to prevent overfitting.
- **Visualization:** Integrated plotting tools to review training history and individual predictions.
- **Saved Model:** Pre-trained model exported in the modern .keras format.

## Project Structure
- `Potato_Disease_Detection.ipynb`: The complete development process from data loading to evaluation.
- `modelos/`: Directory containing the trained model potato_model_v1.keras.
- `requirements.txt`: List of Python dependencies for easy replication.
- `.gitignore`: Configured to exclude heavy datasets and virtual environments.

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Blanktricio/Potato-Disease-Detection.git
