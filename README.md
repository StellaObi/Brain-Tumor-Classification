# Project Title

Feature engineering in Brain Tumor MRI Image Classification

## Overview

This repository contains the codes and resources for my MSc Thesis on "Feature engineering in Brain Tumor MRI Image Classification"

## Background and Motivation

The extraction of relevant features from brain tumor MRI images is a critical step in brain tumor classification, and the quality and relevance of the extracted features determine the classification task’s performance.

The motivation for this project is to conduct extensive experiments in the detection and classification of brain tumor MRI images using transfer learning, image processing, and sophisticated feature engineering techniques, building on existing research and expertise in the field of medical image analysis to improve accuracy and reduce run time, resulting in more reliable brain tumor diagnoses for more e↵ective treatment planning.

## Objective

The primary objective of this project is to develop a system for diagnosing and classifying brain tumor MRI images using transfer learning techniques. In addition, the project aims to explore how di↵erent image preprocessing and feature techniques can enhance the accuracy of medical image analysis systems.

## Dataset

The publicly available brain tumor dataset from Kaggle was used for this study. 
The dataset is a combination of MRI images from three datasets: figshare dataset, SARTAJ dataset and Br35H dataset. The dataset consists of 7023 images of human brain MRI images which is collected as training and testing. Each of the collection contains 4 classes of brain tumor MRI images: glioma, meningioma, no tumor, and pituitary.

## Practical Applications

-  Early Tumor Detection and Diagnosis:

The machine learning model can be deployed in medical institutions to assist radiologists in early detection and diagnosis of brain tumors. By analyzing medical images, the model can identify suspicious regions, enabling timely intervention and treatment planning.

-  Automated Tumor Screening:
  
The model can be integrated into medical imaging systems to automatically screen brain scans for tumors. This can save time for healthcare professionals, allowing them to focus on more complex cases and potentially reducing diagnosis time.

-  Clinical Decision Support System:
  
The machine learning model can be part of a clinical decision support system. It can provide additional insights and recommendations to healthcare providers, aiding in accurate patient management.


## Milestones

All experiments was done on Google collaboratory with CPU 83.48GB RAM and GPU 40GB. Keras, Tensorflow, and scikit-learn libraries with python programming language was used for the coding, testing and analysis of the models.

Key Features and Contribution:

Ensemble of deep features from pre-trained convolutional neural networks with machine learning and transfer learning is used for the classification of brain tumor MRI images into glioma tumor, meningioma tumor, notumor, and pituitary tumor. 

- VGG16, ResNet50, InceptionV3, MobileNet, and DesneNet are used to extract deep features from brain tumor MRI images from the Kaggle brain tumor datset. 
- The extracted deep features are then evaluated by random forest, xgboost and decision tree classifiers 
- The top three deep features are selected and concatenated as an ensemble of deep features 
- The ensembled deep features is used for the final classification using random forest, xgboost and decision tree classifiers and VGG16.

The presented technique in this study achieved a remarkable improvement in the accuracy of brain MRI scans classification compared to other existing methods, with an overall accuracy of 94%.

## Challenges & Future Work



## References
