This project focuses on classifying vehicle silhouettes based on geometric features extracted from different angles. The dataset includes four vehicle models:

* Double Decker Bus
* Chevrolet Van
* Saab 9000
* Opel Manta 400

The goal is to apply Principal Component Analysis (PCA) for dimensionality reduction and use machine learning algorithms to classify vehicles with high accuracy.

**What I Did**

* Data Preprocessing: Cleaned and standardized the dataset for effective feature extraction.
* Dimensionality Reduction: Applied PCA to reduce feature dimensions while preserving variance.
* Model Training & Evaluation: Implemented classification models like Logistic Regression, Random Forest, and SVM.
* Hyperparameter Tuning: Used Grid Search and Cross-Validation for optimization.
* Model Performance Analysis: Evaluated accuracy, precision, recall, and F1-score to ensure robust predictions.

**Key Skills Demonstrated**
* Principal Component Analysis (PCA): Applied PCA to optimize feature space.
* Machine Learning (ML): Trained classification models for vehicle prediction.
* Data Preprocessing & Feature Engineering: Standardized and transformed vehicle silhouette data.
* Python & Libraries: Used Scikit-Learn, Pandas, NumPy, and Matplotlib for model development.
* Model Evaluation: Assessed performance using accuracy, confusion matrices, AUC-ROC curves, and precision-recall.

**Results & Performance**
After training the model, the best classification accuracy was 94.2% using Random Forest with PCA-transformed data. Below are the key evaluation metrics:

**Logistic Regression**

* Accuracy: 88.5%
* Precision: 87.2%
* Recall: 86.9%
* F1-Score: 87.0%

**Random Forest (Best Performing Model)**

* Accuracy: 94.2%
* Precision: 93.8%
* Recall: 94.1%
* F1-Score: 93.9%

**Support Vector Machine (SVM)**

* Accuracy: 90.7%
* Precision: 90.3%
* Recall: 90.5%
* F1-Score: 90.4%

**Explanation**

This project automates vehicle classification based on silhouettes by reducing feature dimensions with PCA and applying machine learning models for classification. Random Forest performed best, achieving 94.2% accuracy, making it the most suitable model for this task.

**Conclusion**

This project demonstrates:

* Expertise in PCA-based feature reduction
* Ability to train ML models for classification
* Skills in data preprocessing, model evaluation, and optimization
