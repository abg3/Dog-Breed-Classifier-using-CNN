# Dog-Breed-Classifier using CNN

# Project Overview

Welcome to Convolutional Neural Networks (CNN). The project focuses on implementing a classifier to identify dog breeds using CNN from scratch and CNN using transfer learning. At the end of the project, we have an algorithm that predicts the closest dog breed a human face resembles.

# Blog

If you are an avid reader, please visit my blog post- https://medium.com/@abg_85948/discover-your-dog-breed-using-cnn-30636fb15d5f

# Contents

The main file in the repository is the dog_app.ipynb, which is the Jupyter notebook containing the process used to create our algorithm and model used to predict the dog breed. A copy of this file is also in dog_app.html format.

The haarcascades folder holds the xml file for use with the OpenCV face detector class that is used in the notebook. The images folder contains the images used to test the predictions of the final model in the notebook.

# Necessary packages

- opencv-python
- jupyter
- matplotlib
- pandas
- numpy
- pillow
- scipy
- tqdm
- scikit-learn
- scikit-image
- seaborn
- h5py
- ipykernel
- pickleshare

# Summary of the results

The CNN model from scratch yielded an accuracy of 22%, well above the 10% mark and the final model using transfer learning with the pretrained model Densenet121 produced 86% accuracy in identifying dog breeds.

# Acknowledgements

Thank you Udacity for providing the opportunity to work on this project!
