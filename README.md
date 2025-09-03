🐶 Animal Image Classification Project

A comprehensive deep learning project to classify animal images using a Convolutional Neural Network (CNN).

📋 Overview
This project aims to build a robust system that can accurately identify the animal in a given image. The model is trained to recognize 15 different animal species from a structured dataset.

🚀 Getting Started
Follow these steps to run the project on your local machine.

Prerequisites
Make sure you have Python installed. All the necessary libraries can be installed using the requirements.txt file.

pip install -r requirements.txt

Project Structure
Your dataset should be organized into a main folder with sub-folders for each animal class, like this:

animal_classification/
├── Bear/
├── Bird/
├── Cat/
└── ...

How to Run
Clone this repository to your local machine.

Place your animal images in the specified folder structure.

Open the animal_classification_project.py file.

Update the dataset_path variable with the correct path to your main data folder.

Run the script from your terminal.

python animal_classification_project.py

🧠 Model Architecture
The model is a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

Layers: The architecture includes multiple Conv2D layers for feature extraction, followed by MaxPooling2D to reduce dimensionality.

Final Layer: The final Dense layer uses a softmax activation function to classify the images into one of the 15 animal classes.

✅ Results
After training, the model achieved a remarkable performance on the validation dataset:

Training Accuracy: 100%

Validation Accuracy: 100%

Total Parameters: 11,169,089

🛠️ Technologies Used
Python

TensorFlow

Keras

NumPy

✍️ Author
Mona Prajapati