# Transfer_Learning_Radiology_Classifier
Keras Transfer Learning to classify radiology scans with pneumonia. (Source)[https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia#chest_xray.zip] Kaggle Dataset.

# Method:

 - TensorFlow Hub to download models
 - MobileNet pretrained model to do transfer learning
 - Kaggle API to load data
 - Keras to build new layers onto the Neural Net for pneumonia classification
 - Matplotlib to see accuracy of model with specific images

# Issues encountered:

 - Challenge was well above my current level
 - Pulled through with a lot of Google, Stack Overflow, and Youtube
 - Biggest issue was preprocessing the data to fit the format Keras requires to train
 - Hyperparameter tuning
 - Focus for this exercise was transfer learning
 - Not optimization or building new layers
 
 # Performance
 Model had 100% accuracy on validation data
