# Image processing between Wat Pho and Wat Pra Kaew project

## Objective
The objective of this project is to develop an image classification model to distinguish between images of two famous Thai landmarks: Wat Pho and Wat Phra Kaew. The model will process a dataset containing labeled images of these landmarks, with the goal of accurately classifying each image as either Wat Pho or Wat Phra Kaew.

## Step
1. Data Loading: Load the image dataset from a directory containing labeled images of Wat Pho and Wat Phra Kaew.
2. Data Preprocessing: Resize the images to a uniform size and convert them to numerical arrays for processing.
3. Label Assignment: Assign labels to the images based on their filenames. Images starting with "pho" are labeled as Wat Pho, and others are labeled as Wat Phra Kaew.
4. Model Training: Use a machine learning model (such as a Convolutional Neural Network) to learn patterns from the preprocessed images and their associated labels.
5. Model Evaluation: Test the model's performance using a separate validation dataset and evaluate its accuracy.
6. Result Interpretation: Analyze the model's predictions to understand its strengths and weaknesses in distinguishing between the two landmarks.

## Result
After running this code, the result will be a saved dataset of preprocessed images and their corresponding labels. This dataset will be ready for training a machine learning model. The success of the model will be measured by its ability to correctly classify new images as either Wat Pho or Wat Phra Kaew.

## Documentation
1. [train_dataset_watpho_vs_wat_prakaew/ Directory](https://github.com/micsupasun/image_processing/tree/main/image_processing_wat_pho_and_wat_pra_kaew/train_dataset_watpho_vs_wat_prakaew): This directory contains the raw image files that are used to train the model. The images are named in a way that reflects their category: images of Wat Pho typically have filenames starting with "pho," while those of Wat Phra Kaew may have different naming conventions.

2. [exercise_3_code.ipynb](https://github.com/micsupasun/image_processing/blob/main/image_processing_wat_pho_and_wat_pra_kaew/exercise_3_code.ipynb): This Jupyter notebook contains the code that handles the entire image processing pipeline. It includes sections for mounting Google Drive, loading images from the dataset, resizing them, converting them to arrays, and assigning labels based on their filenames. The notebook also saves the processed images and labels into a format that can be easily used for model training.