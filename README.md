# Detecting-pneumonia-using-chest-X-ray-Images
Pneumonia Detection: Pushing the Boundaries of Human Ability with Deep Learning
Convolutional Neural Network (CNN) That Detects Pneumonia From Chest X-Rays

Description of the Pneumonia Dataset
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal). Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from patients’ routine clinical care. For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low-quality or unreadable scans. Two expert physicians then graded the diagnoses for the images before being cleared for training the AI system. In order to account for any grading errors, a third expert also checked the evaluation set.

# Steps followed for the Python script to make the project.

1. Step I  : Data collection
2. Step II : Data Exploration
3. Step III: Image Preprocessing
4. Step IV : Data Modelling

# Deep Learning Models
Here are the different deep-learning models with test accuracy
1. Convolutional Neural Network (CNN): Test Accuracy: 0.7596
The model is built using an image of size 150x150 pixels in grayscale without data/image augmentation or an image data generator.
The CNN model architecture is summaries as follows:

2. Convolutional Neural Network (CNN) with ImageDataGenerator: Test Accuracy: 0.6795
The model is built using an image of size 150x150 pixels in grayscale with data/image augmentation or image data generator in the train, test, and validation dataset.
The CNN model architecture is summaries as follows:

3. Convolutional Neural Network (CNN) with VGG16: Test Accuracy: 0.8990
The model is built using an image of size 150x150 pixels in grayscale without data/image augmentation or an image data generator.
The CNN model architecture is summaries as follows:





