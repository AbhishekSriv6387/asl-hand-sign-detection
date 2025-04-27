# asl-hand-sign-detection
A project for detecting and classifying American Sign Language hand signs using computer vision. Tbh, one of the best projects to start your work in field of AI/ML

# ASL Hand Sign Detection

## Overview
This project focuses on detecting and classifying hand signs from the **American Sign Language (ASL)** using computer vision techniques. We use **OpenCV** and **cvzone** for hand tracking and build a custom classifier to detect different ASL signs. The model is trained on images captured using a webcam.

## Features
- **Hand Sign Detection**: Real-time detection of hand signs.
- **Sign Classification**: Classify signs into predefined ASL labels.
- **Custom Dataset**: The model is trained on custom images captured via webcam.
- **Webcam Integration**: Uses webcam feed for capturing images in real-time.

## Technologies Used
- **Python**: Programming language for implementing the solution.
- **OpenCV**: Used for image processing and hand detection.
- **cvzone**: Provides handy functions for hand tracking and classification.
- **TensorFlow/Keras**: Framework used for building the hand sign classifier.
- **NumPy**: For numerical operations on image data.


## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/AbhishekSriv6387/asl-hand-sign-detection.git
2.Navigate to the project directory:
  cd asl-hand-sign-detection

3.Install the required dependencies:
  pip install -r requirements.txt

4.Usage
Data Collection: To capture images of hand signs, run the following command:
python src/collect_data.py
Press 's' to save each image.

Model Training: After collecting the data, use the following command to train the model:
python src/train_model.py

Sign Detection: To run real-time sign detection using the trained model, run:
python src/detect_sign.py

Webcam Feed: The system will start detecting ASL signs using your webcam feed.

Dataset
The dataset for this project consists of images of different ASL hand signs. It was collected using the webcam with the help of cvzone hand detection module.

The dataset is organized into subfolders where each folder contains images of a specific ASL sign.

Model
The model is a Convolutional Neural Network (CNN) trained using images of hand signs. It utilizes Keras and TensorFlow for building and training the model.

The final model is saved in the Model/keras_model.h5 file, and the corresponding labels are stored in the Model/labels.txt.

Contributing
Feel free to fork the repository and submit pull requests for any improvements or bug fixes. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
OpenCV: For image processing and computer vision algorithms.

cvzone: For easy integration of hand tracking and detection.

TensorFlow/Keras: For building and training the machine learning model.

Developed by Abhishek Srivastava







