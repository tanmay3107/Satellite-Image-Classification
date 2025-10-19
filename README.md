# Satellite-Image-Classification

A custom Convolutional Neural Network (CNN) built in TensorFlow/Keras to classify satellite imagery into 10 land-use categories (e.g., "Forest," "Residential").

Objective: Classify land use from 64x64 satellite images.

Dataset: EuroSAT (RGB version).

Tech Stack: Python, TensorFlow (Keras), NumPy.

Key Features: Custom CNN architecture, ImageDataGenerator for data augmentation.

Performance: Achieved 92.5% accuracy by mitigating overfitting.

How to Run
Install: pip install tensorflow numpy matplotlib

Data: Download the EuroSAT (RGB) dataset. Create train and val folders, each containing the 10 category subfolders.

Update Script: Change the train_dir and validation_dir variables to point to your train and val folders.

Run: python satellite_classifier.py
