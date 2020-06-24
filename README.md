# Dog-Breed-Classifier using CNN

# Project Overview

Welcome to Convolutional Neural Networks (CNN). The project focuses on implementing a classifier to identify dog breeds using CNN from scratch and CNN using transfer learning. At the end of the project, we have an algorithm that predicts the closest dog breed a human face resembles.

# Contents
The main file in the repository is the dog_app.ipynb, which is the Jupyter notebook containing the process used to create our algorithm and model used to predict the dog breed. A copy of this file is also in dog_app.html format.

The haarcascades folder holds the xml file for use with the OpenCV face detector class that is used in the notebook. The images folder contains the images used to test the predictions of the final model in the notebook.

# Necessary packages

pytorch
opencv-python==3.2.0.6
h5py==2.6.0
matplotlib==2.0.0
numpy==1.12.0
scipy==0.18.1
scikit-learn==0.18.1
pillow==4.0.0
ipykernel==4.6.1

# Project Instructions

1. Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/deep-learning-v2-pytorch.git
	cd deep-learning-v2-pytorch/project-dog-classification
 
2. Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

4. Make sure you have already installed the necessary Python packages according to the README in the program repository.


# Summary of the results- 

The final model for identifying dog breeds achieved an 86% accuracy level on the testing dataset.

# Acknowledgements

Thank you Udacity for providing this opportunity to work on this project!
