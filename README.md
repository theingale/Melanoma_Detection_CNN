# Melanoma Type Detection using CNN
Building a CNN based deep learning model that accurately detects the type of Melanoma Disease on limited imbalanced data available using various data augmentation techniques.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Problem Statement

Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support.

A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Objective

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.

Our aim is to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.

## About the Dataset

Dataset Link: https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases as labeled:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Sample Data
![image](https://github.com/user-attachments/assets/a0ee9a17-788a-49ac-b91c-2977d4118899)

## Technologies Used

- python (version 3.11.11)
- matplotlib (version  3.10.0)
- tensorflow (version 2.17.1)
- keras (version 3.5.0)
- augmentor (version 0.2.12)

## Conclusions
- Final model achieved the validation accuracy of around 80% on validation data.
- Use of Augmentor library for class balancing not only improved the model performance but also reduced overfitting issue.
- Thus having higher number of images per class lable is better for model training.
- Use of augmentation techniques like rotation, flipping, zoom etc. helps in making the model more robust.

## Acknowledgements
- https://www.cancer.org/cancer/types/melanoma-skin-cancer/about/what-is-melanoma.html
- https://www.isic-archive.com/
- https://www.sciencedirect.com/science/article/pii/S1361841521003509
- https://augmentor.readthedocs.io/en/stable/
- https://github.com/mdbloice/Augmentor 

## Contact
Created by [@theingale](https://github.com/theingale) - feel free to contact me!
  
