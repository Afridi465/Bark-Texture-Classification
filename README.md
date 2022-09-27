# Bark-Texture-Classification
Multiclass image classification of Bark-50 texture data from https://www.kaggle.com/datasets/saurabhshahane/barkvn50

# Handling data imabalance
Created more images for classes which had less number of images than the average of the dataset uisng **image augmentaion** .

# Transfer Learning
Loaded the pre-trained Resnet101V2 (without the top level feature layes) and added GlobalPooling2D, Dropout and final dense layer to complete the model architecture.

# Outcome
Average accuracy on the training set: 98%

Average accuracy on the validation set: 90%
