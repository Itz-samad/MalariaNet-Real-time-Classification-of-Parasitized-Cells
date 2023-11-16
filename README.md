# MalariaNet-Real-time-Classification-of-Parasitized-Cells
 Overview
MalariaNet is a project focused on leveraging deep learning techniques to classify malaria cell images as either infected (parasitized) or uninfected. The project incorporates image preprocessing, dataset splitting, convolutional neural network (CNN) model creation, and real-time prediction using a webcam feed.

Key Features
Dataset Preprocessing:

Resize original images to a standardized (224, 224) pixel size.
Organize resized images into corresponding directories.
Dataset Splitting:

Split images into training and testing sets (80% and 20%, respectively).
Create separate directories for training and testing data.
Visualization:

Visualize image counts in each category using bar plots.
CNN Model:

Build a sequential model with convolutional layers for feature extraction.
Utilize max-pooling layers to downsample feature maps.
Implement dense layers for classification, including dropout for regularization.
Use the sigmoid activation function for binary classification.
Data Augmentation:

Apply image data augmentation techniques, such as rescaling, shearing, zooming, and horizontal flipping, to enhance model generalization.
Training and Evaluation:

Train the model using training data.
Evaluate model performance on the test set.
Save the best-performing model using checkpoints.
Real-time Prediction:

Utilize a webcam to capture frames in real-time.
Preprocess each frame for model prediction.
Display the predicted class on the webcam feed.


Usage
Install Dependencies:
pip install -r requirements.txt

Dataset Preparation:

Place parasitized and uninfected cell images in the respective directories.
Run dataset splitting and resizing scripts.
Model Training:

Configure the model architecture and hyperparameters in the script.
Run the script for model training.
Real-time Prediction:

Execute the script for real-time prediction using a webcam.

**Acknowledgments**
The dataset used in this project is sourced from https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria.

License
This project is licensed under the MIT License.
