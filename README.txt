Object Recognition with TensorFlow and Keras

Overview

This repository contains code for building and training a convolutional neural network (CNN) using TensorFlow and Keras for object recognition. The code includes data loading, dataset creation, model definition, training, and prediction functionalities. Additionally, data augmentation techniques are applied to enhance the model's generalization.

Prerequisites

Python 3.x
TensorFlow
Matplotlib
NumPy

Usage

1. Open the Jupyter notebook or Python script containing the code:

jupyter notebook object_recognition.ipynb

or
python object_recognition.py

2. Follow the code comments and execute each code cell or section sequentially.

3. View the training progress and visualizations generated during the process.

4. Make predictions on individual images or an entire folder of images.

Customization

- Adjust the batch_size, img_height, and img_width variables to fit your dataset.
- Experiment with the model architecture in the Sequential model definition section.
- Fine-tune hyperparameters such as learning rate, dropout rate, and number of epochs in     the training section.

Acknowledgments

The code in this repository is based on tutorials and examples from the TensorFlow and Keras documentation.

Path

# Path to the folder containing images
folder_path = r"C:\Users\dhyan\OneDrive - University of Hertfordshire\Documents\Object Recognition (1)\Photos\Food"

- Create a folder and put all the photos in it.
- Open the Validation Photos Folder and copy the path of one of the folder.

The directory is:
|--Photos/
   |--image 1.jpg
   |--image 2.jpg
   |--...

# Define the path to the 'Photos' directory
photos_dir = r"C:\Users\dhyan\OneDrive - University of Hertfordshire\Documents\Object Recognition (1)\Validation Photos"

- Create a folder and name it Photos.
- Inside that folder create 4 Folders. Folder 1 name it Food and it should contain all the images of the Food. Folder 2 name it Buildings and it should contain all the images of the Buildings. Folder 3 name it People and it should contain all the images of the People. Folder 4 name it Other and it should contain all the images of the Other.
- You can also replace it with the path of the Training Photos folder provided in the zip file. It consist of 47 images. I have trained the model on this 47 images only.

The directory is:
-- Photos/
   |--Food/
      |--image 1.jpg
      |--image 2.jpg
      |--...
   |--Buildings/
      |--image 1.jpg
      |--image 2.jpg
      |--...
   |--People/
      |--image 1.jpg
      |--image 2.jpg
      |--...
   |--Other/
      |--image 1.jpg
      |--image 2.jpg
      |--...
