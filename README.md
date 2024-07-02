# CIFAR10_ResNet
ResNet CNN on CIFAR-10 using PyTorch Lightning

This repository contains an implementation of a ResNet architecture for a Convolutional Neural Network (CNN) to classify images in the CIFAR-10 dataset using PyTorch Lightning.

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. This project leverages the robustness and efficiency of ResNet architecture to achieve high accuracy on this dataset.

The model was overfitting after 20 epochs with batch of 64.
Final *train_acc was 74.1% and validation_acc was 62.6%*(Base accuracy being 10% to start with)

Using Transfer learning the model gave a *training accuracy of 92.3% and validation accuracy of 87.9%* after 10 epochs after which the model started overfitting.
The weights were fixed from the resnet18 classification of imagenet(1000 classes).
