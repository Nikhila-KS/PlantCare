# PlantCare🍃
### Description
PlantCare is a project dedicated to the detection of diseases in apple leaves using deep learning models. The best-performing model, which achieved high accuracy and compatibility for mobile application integration, has been incorporated into the Flutter app named PlantCare.

### About the Dataset used to train Machine learning model
The dataset utilized for training originates from the 'Plant Village Dataset', sourced from Kaggle. This dataset comprises 3366 images categorized into four classes:

Apple__Apple_scrab (753 images)
Apple__Black_rot (800 images)
Apple__Cedar_Apple_rust (800 images)
Apple__healthy (1145 images)

### Data Preprocessing
To ensure compatibility with the Convolutional Neural Network (CNN) architecture, the following preprocessing steps were undertaken:

Resizing and standardizing images to a consistent size, such as 224x224 pixels.
Augmentation of the dataset to enhance diversity and boost model generalization through random transformations, including rotations, flips, and brightness adjustments.
Usage
Run the Flutter application on your mobile device.
Capture or select an image of an apple leaf.
Submit the image for analysis.
The application will provide feedback on whether the leaf is diseased and, if so, which disease it may have.

### Contributors
- Smita Maurya
- Nikhila K S

