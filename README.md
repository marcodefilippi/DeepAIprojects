# DeepAIprojects
python notebooks realized during the MIT program in AI. 
Two python notebooks:
## **1) Project_High_Code_SVHN_Digit_Recognition.ipynb**
--------------
## **Context** 
--------------

One of the most interesting tasks in deep learning is to recognize objects in natural scenes. The ability to process visual information using machine learning algorithms can be very useful as demonstrated in various applications.

The SVHN dataset contains over 600,000 labeled digits cropped from street-level photos. It is one of the most popular image recognition datasets. It has been used in neural networks created by Google to improve the map quality by automatically transcribing the address numbers from a patch of pixels. The transcribed number with a known street address helps pinpoint the location of the building it represents. 

----------------
## **Objective**
----------------

The objective is to predict the number depicted inside the image by using Artificial or Fully Connected Feed Forward Neural Networks and Convolutional Neural Networks. We will go through various models of each and finally select the one that is giving us the best performance. 

-------------
## **Dataset**
-------------
Here, we will use a subset of the original data to save some computation time. The dataset is provided as a .h5 file. The basic preprocessing steps have been applied on the dataset.

## **2) Reference_Notebook_Facial_Emotion_Detection_Full_Code.ipynb**
--------------
## **Context** 
--------------

This project aims to create a computer vision model to accurately detect facial emotions. This is a challenging yet rewarding project that involves multiple stages, such as preprocessing, model selection, training and evaluation. Facial emotion recognition is particularly important because it does not require advanced equipment and allows to acquire the data with simply a camera. The increase in available data and computing power has led to the use of deep learning techniques, providing interesting results. 
This task is not a typical classification task like any other, because there is not a clear distiction of the classes.  Typical classification is based on the concept that there is a corret answer, but in facial emotion recognition it is more important how people interpret them. In fact, the same face could be interpreted as expressing different emotions. In addition, the same facial expression could also show multiple emotions at the same time. That is the reason why this project is really challenging and therefore, it is needed to understand if more advanced models can address the peculiarities of facial emotions. A good classifier should be able to understand expressions not just as distict categories, but als oas  combinations of emotions. 

This project is of great interest, because facial emotion recognition is becoming ever more important in many fields, from social robotics to healtchare. All of this arises from the asumption tht relations with other people is vital in the life ef every person nd the verbal communication is not more important than all thse even imperceptible movements that are part of body language. One of the most important ways by which people interact with each other is through emotions and in particular, as confirmd from recent researches, the 55% of sentiments takes place through facial emotions. Therefore, the importance of solving facial emotion recognition problems lies in the potential improvements in human lives, in human-computer interations in order to contribute to societ well-being.

----------------
## **Objective**
----------------

The goal of this project is firstly to develope a baseline model and from this, make improvements by using more complex models in order to establish the best model able to better classify 4 basic emotions: happy, sad, surpire and neutral. This project also aims to analyze hte results of our model in terms of accuracy for each class. 
The final model should be able, given an input image that contains one emotions belonging to one of the 4 basic emotions, to generate an output that correctly labels the input image. 

-------------
## **Dataset**
-------------

A fundamental step, as in every kind of machine learning/deep learning task, is the choice of the datasets to be used for training and validation. 
For this project, the dataset is provided and already splitted into the train, validation and test set. 
Generally, a good dataset should have a number of examples sufficients for deep learning applications, being balanced and contain pictures taken in wildly different conditions in order to alow the network to properly generalize. To this end, a comparison between the results obtained from the original datasets and augmented dataset is performed in order to understand the limits of using a dataset that does not properly represent the variability of real-life situations. 
It will be also interesting to understand if data augmentation should be applied on the training set only, or if it makes sense to perform it for the validation set as well. As first intuition, the idea is to evaluate the model's performance on data that represents the true distribution of the data it will encounter in the real world, without artificial augmentation. If this is not applied, the final validation accuracy could be higher than the training accuracy because of the non-augmented cleaner validation set.
