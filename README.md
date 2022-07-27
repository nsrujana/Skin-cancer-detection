# Project Name
> Building Multiclass classfiication of skin cancer dataset to detect melanoma


## Table of Contents
* [To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.](#general-information)
* [impplementing basic Convotutional Neural Networks in tesnsorflow ](#technologies-used)
* [The model build handled overfiting to some extent. Increasing number of layers and epochs may help the performance of the model](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
-The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1: from the initial CNN model it is found the accuracy of trainig set is more indictaing the overfitting.
- Conclusion 2: To avoid overfitting, drop out layers are added in the model.This results a balnce accuracy between training set and validation set
- Conclusion 3: To improve model performance, data augmentation is preferred and with that class imbalance is taken care.
- Conclusion 4: The accuracy of the model is imporved. senario of overfitting is taken care to some extent.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@nsrujana] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->