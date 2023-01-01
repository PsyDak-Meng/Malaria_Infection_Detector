# Malaria-Infection-Detector
Used Resnet_50 and its pre-trained weights to implement CNN on malaria infection classification through cell images (dataset from Kaggle). With OOP, create a centralized Malaria_Resnet class where only the last output layer is unfreezed and modified to 2 classes--Infected and Uninfected. Used Pytorch to implement data augmentation through crops, rotations and flips, together with standard trainning and evaluation loop. <br />
Due to limited computing power, only 100 epoch was trialed and was able to reach roughly 93% accuracy. 
Dataset Link: https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria
