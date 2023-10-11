# Project Name
> Convolutional Neural Network model for the Melanoma(Skin cancer) detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.
- We should arrive at the best train and validation accuracy at the end of the assignment

## Conclusions
- Following are the different steps followed to complete the assignment.
    - Problem Statement
    - Step1: Data load using Keras
    - Step2: Splitting tarin data into Training set and Validation set (80:20) 
    - Step3: Visualizing the data 1 of each class.
    - Step4: Create and train base CNN model.
    - Step5: Add augumentation to check if model performance increases
	- Step6: Check for class imbalances, Identify least and maximun number of samples 
    - Step7: Use Augmentor to add 500 samples to decrease the class imbalance.
	- Step8: Build and train the final model.
	- 
	
- Following are conclusions from Regularization
	- At step 4 with base CNN model there is very low accuracy.
    - At step 5 After data augmentation not much much improvement is seen in the accuracy.
    - After using augmentor and addressing the data imbalance the final model has given very good training and validation accuracy.
    - 

## Technologies Used
- Python - version 3.0
- Pyhton libraries used - pandas, numpy, matplotlib, Tensorflow, Keras 

## Acknowledgements
Give credit here.
- This project was done as part of Upgrad, IIITB Master of Science in Machine Learning & AI course
- This project was based on [Master of Science in Machine Learning & AI](https://www.upgrad.com/masters-in-ml-ai-ljmu/).


## Contact
Created by [@prakashreddyav] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->