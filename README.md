# Brain-Tumor-Classification
This repository contains the codes and resources for my MSc Thesis on "Feature engineering in Brain Tumor MRI Image Classification"
The main objective of this project is to develop a system for diagnosing and classifying brain tumor MRI images, as well as to learn how various image preprocessing and feature techniques can help improve the accuracy of medical image analysis systems.
The project aims to contribute to medical image analysis and aid in early and accurate tumor diagnosis.
Technology Used:
All experiments was done on Google collaboratory with CPU 83.48GB RAM and GPU 40GB. Keras, Tensorflow, and scikit-learn libraries with python programming language was used for the coding, testing and analysis of the models.

Key Features and Contribution:

Ensemble of deep features from pre-trained convolutional neural networks with machine learning and transfer learning is used for the classification of brain tumor MRI images into glioma tumor, meningioma tumor, notumor, and pituitary tumor. 

- VGG16, ResNet50, InceptionV3, MobileNet, and DesneNet are used to extract deep features from brain tumor MRI images from the Kaggle brain tumor datset. 
- The extracted deep features are then evaluated by random forest, xgboost and decision tree classifiers 
- The top three deep features are selected and concatenated as an ensemble of deep features 
- The ensembled deep features is used for the final classification using random forest, xgboost and decision tree classifiers and VGG16.
