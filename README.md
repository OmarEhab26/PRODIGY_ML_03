# PRODIGY_ML_03
# Cat vs. Dog Classification Using SVM

## Overview
This project implements a classification model to differentiate between images of cats and dogs using Support Vector Machine (SVM) learning. The dataset consists of images stored in folders named 'train', where each image is labeled based on its filename.

- **Libraries Used**: 
  - `numpy`: For numerical computations.
  - `pandas`: For data manipulation.
  - `sklearn`: For implementing the SVM model and evaluation metrics.
  - `PIL`: For image processing.
  - `skimage`: For image feature extraction.

- **Image Processing**: 
  - Images are loaded from the specified folder, resized to 64x64 pixels, and converted to grayscale. 
  - Histogram of Oriented Gradients (HoG) feature extraction is applied to enhance the model's accuracy.

- **Label Extraction**: 
  - Labels are extracted from the image filenames, categorizing them into "cat" or "dog".

- **Model Training**: 
  - The dataset is split into training and testing subsets.
  - An SVM classifier is trained using a radial basis function (RBF) kernel.

- **Model Evaluation**: 
  - The model's performance is assessed using various metrics including accuracy, precision, recall, F1 score, and a confusion matrix.
  - A classification report is generated to provide detailed insights into the model's performance for each class.

## Conclusion
This project effectively demonstrates the application of SVM for image classification tasks, specifically for distinguishing between cats and dogs. The use of feature extraction techniques like HoG contributes to improved classification accuracy.
