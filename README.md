# Brain Tumor Detection
The main objective of this project is to use convolutional neural networks to identify brain tumors from MRI images of the brain. The dataset for this project was taken from Kaggle.

#Data Augmentation
The dataset present in Kaggle is not large enough to train the neural network thus data augmentation is used. 
Before augmentation there were, 155 positive and 98 negative examples, resulting in 253 example images.
After augmentation there were, 1085 positive and 980 examples, resulting in 2065 example images.

#Data Preprocessing
cropping and resizing of data is performed to have a shape of (240, 240, 3)=(image_width, image_height, number of channels)

#Data Split
70% of the data for training.
15% of the data for validation.
15% of the data for testing.

