Data Source: Great Learning

This project focuses on **detecting faces in movie scenes** for a streaming service application. The goal is to build an **automated cast and crew recognition system** that detects actors in a movie scene when a user pauses the video. The system uses **deep learning-based face detection** techniques and **segmentation models** to locate and classify faces within frames.

**What I Did**  

* **Dataset Preparation**: Imported and preprocessed movie scene images along with their corresponding masks indicating human faces.  
* **Feature Engineering**: Created structured datasets by extracting **features (images) and labels (masks)** from the data.  
* **Model Architecture Design**: Implemented a **U-Net based face detection model** with **pre-trained transfer learning models** for segmentation.  
* **Custom Loss Function**: Designed a **Dice Coefficient-based loss function** to improve segmentation accuracy.  
* **Model Training & Optimization**: Trained and tuned the model using **hyperparameter optimization** techniques.  
* **Evaluation & Testing**: Assessed model performance using **segmentation accuracy, Dice Coefficient, and visual validation on test images**.  
* **Prediction & Visualization**: Used the trained model to predict face masks on unseen movie scenes and generated segmented images.  

**Key Skills Demonstrated**  

* **Computer Vision & Image Processing**: Applied **image segmentation and face detection techniques** to identify actors in movie scenes.  
* **Deep Learning for Face Detection**: Designed and trained a **U-Net segmentation model** for face localization.  
* **Data Preprocessing & Augmentation**: Processed image datasets, applied augmentations, and generated training masks.  
* **Python & Libraries**: Used **TensorFlow, Keras, OpenCV, Pandas, NumPy, and Matplotlib** for model training and visualization.  
* **Custom Loss Function & Model Optimization**: Implemented a **Dice Coefficient-based loss function** to improve segmentation accuracy.  


0**SUMMARY**

The main objective of the project is to detect the faces in the image. In this project, images and masks were created, and using U net architecture and pretrained weights, the model was executed.

*Refer to "Project 17.ipynb" for all the details, the inference and the conclusions are also detailed within the notebook.*

**Results**

<img width="893" alt="image" src="https://user-images.githubusercontent.com/88423149/181877930-0e0bce8e-d7bd-4d1a-b6bd-79fc2c5f872d.png">

Test accuracy is only 58.33% with Train accuracy at 93%, this means the accuracy is saturating at around 55-60%

Before: 

![image](https://user-images.githubusercontent.com/88423149/181877950-d25bd34a-1293-4f68-a5fc-94fe0378dfda.png)

After:

![image](https://user-images.githubusercontent.com/88423149/181877959-42f079a6-5d93-46db-9f88-9a1c7b1cf6d1.png)

Face detection on test data worked properly

**Refer to the PYTHON NOTEBOOK FOR MORE DETAILS AND INFERENCES**
