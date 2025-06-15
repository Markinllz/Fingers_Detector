# Fingers_Detector
Context The goal of this project is to build a model capable of counting the number of fingers shown in an image and distinguishing between left and right hands.


Dataset Description
Total images: 21,600 (left and right hands)
Image size: 128x128 pixels
Training set: 18,000 images
Test set: 3,600 images
Features:
All images are centered by the hand’s center of mass.
The background contains a noise pattern.
Labels: The last two characters of each filename encode the label:
L/R — left/right hand
0,1,2,3,4,5 — number of fingers
Solution
In this project, I designed and trained a custom convolutional neural network (CNN) from scratch for the classification task.

Pipeline Overview
Implemented data augmentation and normalization for better generalization.
Trained the custom CNN model from scratch on the training dataset.
Evaluated model performance using loss and accuracy metrics on both training and validation sets.
