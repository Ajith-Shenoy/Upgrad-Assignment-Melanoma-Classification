# Upgrad-Assignment-Melanoma-Classification
My Assignment Submisson for the Melanoma Classification Assignment by Upgrad

## Table of Contents
* [General Info](#general-information)
* [Algorithms Used](#algorithms-used)
* [Dataset Information](#dataset-information)
* [Technologies Used](#technologies-used)
* [Steps Involved](#steps-involved)
* [Conclusions](#conclusions)
* [Contact](#contact)

### Problem Statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Algorithms Used

Convolutional Neural Network

## Dataset Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Technologies Used

- Python == 3.9.3
- Tensorflow Keras == 2.15
- Augmentor == 0.2.12
- Pandas == 1.5.3
- Seaborn == 0.12.2

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model
- Using modal against test data

## Conclusions

The final model has an accuracy of 83% and a loss of 0.45. The model is able to predict the class of the lesion with a high accuracy. Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

## Contact

This solution is created by me @Ajith-Shenoy, for Upgrad AIML IIITB Diploma Course.
