# Melonama Detection
> Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopic analysis, a biopsy and histopathological examination. Automated classification of skin lesions using images is a challenging task owing to the fine-grained variability in the appearance of skin lesions. Identify the melanoma in images of skin lesions and use images within the same patient and determine which are likely to represent a melanoma. Using patient-level contextual information may help the development of image analysis tools, which could better support clinical dermatologists

- What is the background of your project?
- The primary goal the project is to build a CNN based model which can accurately detect melanoma, which can be used to evaluate the images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis

- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions
- On Model 3 the training accuracy is 85.42% . The validation accuracy is 82.93%. Gap between train accuracy and validation accuracy is less.

- Now overfitting was avoided through class re-balancing. 

- Though the model accuracy has improved, the class rebalance has helped to treat the overfitting to some extent.

- Best models could be built by adding more epochs, more layers, neurons or adding dropout layers.

## Technologies Used
- Python - 3.7
- sklearn - 0.24.2
- Pandas - v1.3.5
- Numpy - v1.21.5
- Tensorflow 2.10.0

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Learning platform in understaning CNN

## Contact
Created by [@Pranavi][https://github.com/pranavich] - feel free to contact me!
