# Face-mask-Detection

The dataset I used for Face Mask model is taken from Kaggle : https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset
It contains seperate images for Train, Test and Validation

Used KERAS_TUNER to get an optimum model.
This is a two stage - pipeline :
1. face Detection
2. Face mask classification(with or without)

However, the drawback in this is that as Face mask occludes part of the part, face detection might not work properly . 

Future task: Use Object detection for face mask detector
