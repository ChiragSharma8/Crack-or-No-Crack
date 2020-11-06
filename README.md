# Crack Segmentation

Here I present my solution to the problem crack segmentation for concrete meterials. In this article, I describe the approaches, dataset that I exprimented with and desmonstrate the result. 


# Overview

Crack segmentation is an important task in structure investigation problems. For example, in the bridge investigation project, a done is controlled to fly around bridges to take pictures of different bridge surfaces. The pictures will be then processed by computer to detect potential regions on the bridge surface that might be damaged. The more accurate the model is, the less human effort we need to process these images. Otherwise, the operators will have to check every single image, which is boring and error-prone. One challenge in this task is that the model is sentisive to noise and other objects such as moss on crack, title lines, etc.


# Dataset

From my knowledge, the dataset used in the project is the largest crack segmentation dataset so far. It contains 40k cracked and no-cracked images.
(https://www.kaggle.com/thesighsrikar/concrete-crack-images-for-classification) link for dataset. I have also added some more cracked images in the dataset.


# Approach

I have used two approaches in my solution for determining the crack or no-crack images.

##  1. Simple CNN model 
            Simple CNN model for binary classification and then making an app for the same deploying it locally .
            
##  2. Pytorch
           Using PyTorch for binary classification , even my system doesn't have GPU i have also coded for the same and i have worked with CPU with less epoch but                                    satisfactory results.
