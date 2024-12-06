# Overview
The Dog Breed Identification Project is a machine learning application that leverages deep learning techniques to accurately identify dog breeds from images. This project combines a user-friendly graphical interface with a robust model trained on a diverse dataset of dog images.

# Features
Image Upload: Users can upload images of dogs for breed identification.
Real-time Prediction: The model provides instant predictions of the dog's breed.
User-Friendly Interface: Built using Tkinter for easy interaction.
Wide Breed Coverage: Supports identification of 70 different dog breeds.

# Technologies Used
Programming Language: Python
Frameworks: TensorFlow, Keras, Tkinter
Libraries: NumPy, PIL (Pillow), OpenCV
Model Architecture: InceptionV3 for feature extraction and classification

# Usage
Launch the application to open the GUI.
Click on the "Upload Image" button to select an image of a dog.
The application will process the image and display the predicted breed along with a confidence score.

# Model Training
The model is trained using a dataset containing 6,390 images across 70 dog breeds. The training process involves:
##Data Preprocessing: Images are resized to 224x224 pixels and normalized for model input.
##Model Architecture: The InceptionV3 architecture is used for its efficiency in image classification tasks.
##Training Process: The model is trained for 10 epochs with accuracy reaching up to 99%.

# Key Training Parameters:
##Loss Function: Categorical Crossentropy
##Optimizer: Adam optimizer with a learning rate adjustment
