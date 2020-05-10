# Clothers-classification
 normal clothers and camouflage clothers

This project is employed to classify normal clothers and camouflage clothers using Resnet network.
Specifically, we fine tune Resnet with keras, tensorflow and deep learning.
For training, we use the pre-trained Imagenet weights but leaving off the fully-connected layer head.
We build a new fully connected at the end.
Then the weights in the based model of Resnet are frozen, we only fine tune the head of the network.
