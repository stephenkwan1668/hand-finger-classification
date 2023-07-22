# Hand Fingers Classification
 
## Abstract
In this project, we use various Convolutional Neural Networks (CNNs) to identify what number a hand gesture
is trying to show. All models are trained on a dataset with about 21600 images of left or right hand fingers
showing number 0 to 5. The goals are to find or formulate the best model to recognize the shown digits and
attempt to apply the persistent homology tool from Topological Data Analysis (TDA) for data-preprocessing.
The result shows that among AlexNet, DenseNet and our custom architecture IzolNet, IzolNet has the best time
efficiency whereas the accuracy of these models are almost the same.

## Introduction
Computer image recognition technology has made unprecedented breakthroughs in the last decade, which
has been largely driven by the development of CNNs. Since the CNN architecture AlexNet[1] won the ImageNet
Large Scale Visual Recognition Challenge (ILSVRC), known as the world cup of computer vision, by a landslide
in 2012, CNNs have been dominating the field of computer vision (CV).
The aim of this research project is to develop the ‘best’ CNN architecture on recognizing the number that a
hand is showing. The motivation for this topic is that its extensions have a wide range of promising applications
in the field of human-computer interaction, such as commanding machines using hand gestures or sign language
recognition. Starting with this simple task, we compared the performance of different models in the course of
the study and attempted to build a custom one in an effort to improve accuracy, which would give us a guide to
future applications in this area. In addition to the aforementioned aim, we observe how applying a tool called
persistent homology from Topological Data Analysis (TDA) may assist us in data pre-processing and feature
extraction.
