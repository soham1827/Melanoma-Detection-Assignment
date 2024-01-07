# Project Name
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The jupyter notebook gives a walkthrough on CNN technique with data augmentation and generating addiional dataset via Augmentor library for handling Class imbalabnce dataset.
- We are trying to classify the skin cancer category
- The dataset used  consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

-Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- For 1st CNN model built, we saw clear signs of overfitting and it had to be taken care.
- To handle overfitting and need to boost validation accuracy, we used some augmentation. This helped to handle overfitting but not accuracy
- Observation took that class imbalance needs to be handled. The augmentor library helped to generated additional dataset images. 
- This helped the model to built excellent accuracy for train and validation too.
- In case of class imbalance, Augmentor library did solve the issue to much extent.





<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
