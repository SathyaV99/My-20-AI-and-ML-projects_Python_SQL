Data source: https://www.kaggle.com/datasets/hereisburak/pins-face-recognition

This project focuses on face identification using a pre-trained deep learning model for facial similarity detection. The dataset comprises 10,770 images of 100 individuals, with all images aligned using the dlib library. The system determines whether two given faces belong to the same person or not by leveraging feature embeddings and similarity comparisons.

What I Did

Data Preprocessing: Imported and aligned images using dlib face alignment to standardize inputs.
Feature Extraction: Used a pre-trained face recognition model to extract facial feature embeddings.
Face Similarity Matching: Applied cosine similarity to compare extracted embeddings and determine identity matches.
Model Training & Evaluation: Assessed accuracy using face verification techniques, ensuring high precision.
Visualization & Results Analysis: Displayed image pairs with similarity scores to validate model performance.
Key Skills Demonstrated

Face Recognition & Feature Extraction: Leveraged a pre-trained model to extract meaningful facial embeddings.
Machine Learning for Similarity Detection: Applied cosine similarity to evaluate face match probability.
Data Preprocessing & Alignment: Standardized dataset by aligning facial images using dlib.
Python & Libraries: Used OpenCV, dlib, TensorFlow, Keras, Pandas, and NumPy for model training and feature extraction.
Model Evaluation & Performance Tuning: Measured false positive rates, accuracy, and similarity thresholds.
