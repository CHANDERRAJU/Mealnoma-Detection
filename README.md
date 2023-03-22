# Mealnoma-Detection
CNN Model for Melanoma Detection
# Project Name
Image based model for Melanoma detection with a mix of healthy and cancerous image samples.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

## General Information
- Provide general information about your project here.

The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.

- What is the background of your project?

In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. 

- What is the business probem that your project is trying to solve?


In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.



- What is the dataset that is being used?

The dataset consists of 2K+ images of malignant and benign oncological diseases belonging to 9 classes, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.



## Technologies Used
- Pathlib
- Tensorflow
- Matplotlib
- Numpy
- Pandas
- PIL
- Keras
- Augmentor
- Sequential
