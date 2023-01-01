# Malaria-Infection-Detector
Using Resnet_50 and its pre-trained weights to implement CNN on malaria infection classification through cell images. Onlky the last output layer is unfreezed and modified to teo neurons-- Infected and Uninfected.
With OOP, create a centralized Malaria_Resnet class. Used Pytorch to implement data augmentation through crops, rotations and flips. 
Due to limited computing power, only 100 epoch was trialed and was able to reach around 93% accuracy. 
