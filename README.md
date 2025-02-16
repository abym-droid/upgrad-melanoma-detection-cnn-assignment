# Melanoma detection CNN Model
> This is an effort to analyze images from "ISIC - The International Skin Imaging Collaboration" and create a custom CNN model with a step by step approach for detection of melanoma classes accurately


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- __Business Problem__: To build a custom CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- This is an assignment which requires me to build a custom CNN model using training data from "ISIC - The International Skin Imaging Collaboration" which has multiple images belonging to 9 different skin diseases including Melanoma
- The custom CNN model need to be built and trained using the images with observation for trends of overfitting, addressing the same and incorporating data augmentation and class imbalance issues.
  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- __Findings after first model__: The model overfit with significant difference between training and validation accuracy. The model would require some regularization and augmentation to close the gap and optimize.
- __Findings after second model__: The model train and validation accuracy gap is closer, thus justifying augmentation and regularization techniques. However the training accuracy was quite low which would signify some class imbalance issues
- __Final Model Analaysis__: The model has addressed overfitting issues as the training and validation scores are pretty close to each other. Thus the dropout and batch normalization strategies worked well. The accuracy of the model has increased more than that of the previous models, so the data augmenation has also worked well. The accuracy can potentially increase more if we add more augmented samples and do few more image transformations. For melanoma detection we may also need to focus on recall scores instead of focusing on just accuracy

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow - version 2.18.0
- Tensorflow Keras - version 3.8.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by the CNN module from Upgrad - IIITB Post Graduate program coursework
- It used a starter notebook provided by Upgrad as base for instructions and guidance
  


## Contact
Created by [@abym-droid] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
