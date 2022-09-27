# Bark-Texture-Classification
Multiclass image classification of Bark-50 texture data from https://www.kaggle.com/datasets/saurabhshahane/barkvn50

# Handling data imabalance
Created more images for classes which had less number of images than the average number images of all classes uisng **image augmentaion**. **Reference for the augmentation technique:** https://github.com/mdbloice/Augmentor/blob/master/notebooks/Per_Class_Augmentation_Strategy.ipynb

# Transfer Learning
Loaded the pre-trained Resnet101V2 (without the top level feature layes) and added GlobalPooling2D, Dropout and final dense layer to complete the model architecture.

# Outcome
Average accuracy on the training set: 98%

Average accuracy on the validation set: 90%
