# Project Name
> multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](custom convolutional neural network in TensorFlow. )
* [Technologies Used](Tensor Flow, Google Colab)
* [Conclusions](#conclusions)
* [Acknowledgements](Submitted by Ravikanth Nagaraj)



## General Information
- What is the business probem that your project is trying to solve?
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 before Augementation
- Training and Validation Accuracy:
- Accuracy Plot (Left):

Training accuracy shows a consistent upward trend, reaching a value above 
0.7.
Validation accuracy also improves but exhibits more fluctuations and doesn't consistently match the training accuracy.

Loss Plot (Right):

Training loss decreases steadily over epochs, indicating the model is learning well on the training data.
Validation loss decreases initially but fluctuates significantly after a few epochs and doesn't closely follow the training loss curve.

Findings:
Model Overfitting:

There is some evidence of overfitting, as the gap between training and validation accuracy widens over epochs.
Validation loss fluctuations and the growing gap between training and validation metrics indicate the model might be memorizing the training data rather than generalizing well.

- Conclusion 2 after Augementation 
- Observations:

Training and Validation Accuracy:
The training accuracy remains consistently high (above 90%).
The validation accuracy shows significant improvement compared to the first model. Although it fluctuates slightly, it stabilizes at a much higher level (around 85%–87%), indicating better generalization.

Training and Validation Loss:
The training loss is low and consistent, showing that the model fits the training data well.
The validation loss is much more stable compared to the initial model and remains relatively low, indicating reduced overfitting.

Class Rebalancing Impact:
The improved validation metrics suggest that class rebalancing has helped the model generalize better by addressing class imbalance issues. This ensures the model does not overly favor dominant classes.

Analysis:

Underfitting: The model no longer shows signs of underfitting. The high training accuracy and low training loss indicate the model is learning the patterns in the training data effectively.
Overfitting: The validation loss and accuracy are close to the training metrics, showing that overfitting has been significantly reduced. The use of data augmentation and rebalancing likely played a major role in this improvement.







## Technologies Used
- library - Tensor Flow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
Upgrad & IIITB PG in AI & ML


## Contact
Created by [@nagarajravikanth] - feel free to contact me!

