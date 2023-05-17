# Parkinson's Freezing of Gait Prediction

This repository contains the code and resources for the Parkinson's Freezing of Gait Prediction project.  
The project aims to develop a model that can detect and classify freeze of gait (FOG) episodes in patients with Parkinson's disease.

Competition Overview  
The project is based on the TLVMC - Parkinson's Freezing Gait Prediction competition on Kaggle.  

The competition focuses on two tasks:

## Task 1: FOG Episode Detection and Classification  
The goal is to detect FOG episodes and classify their types along the temporal axis.  

The types of FOG episodes are as follows:  

* StartHesitation: Uncertainty in initiating walking.  
* Turn: Uncertainty during turning or moving to a destination.  
* Walking: Delayed and extremely small steps.  
* 
The evaluation metric for this task is the mean Average Precision (mAP), which is the average sum of the Average Precision (AP) for each of the three event classes.

## Task 2: Motor and Non-Motor Symptoms Identification in Parkinson's Patients  

The objective is to explore the data and train a model to classify motor and non-motor symptoms in patients with Parkinson's disease.
