# Image Augmentation with Recognition

This repository demonstrates a Python-based approach to perform image augmentation and recognition. The project uses libraries like OpenCV and TensorFlow/Keras for processing and recognizing images.

## Features

- Perform various image augmentation techniques like rotation, flipping, scaling, etc.
- Use machine learning models for recognizing augmented images.
- Easy-to-understand implementation with examples.

## Prerequisites

- Python 3.x
- TensorFlow
- OpenCV
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aaronx1276/Image-Augmentation-with-Recognition.git
   cd Image-Augmentation-with-Recognition
2. Install the required libraries:
   ```
   pip install tensorflow
   pip install opencv-python
   pip install numpy
   pip install matplotlib
   pip install scikit-learn
   pip install pandas
   ```

## Usage
1. Add your dataset of images to the data folder.
2. Run the app.py to preprocess images:
   ```
   python app.py
   ```
3. Run the recognition model using:
   ```
   python recognition.html
   ```
5. Run index.html using:
   ```
   python index.py
   ```

## Project Structure
- index.py - This `HTML` file creates a webpage for image augmentation with options like rotation, grayscale, blur, brightness, contrast adjustments, and resizing (e.g., passport or stamp size). It uses JavaScript and a `<canvas>` element to apply operations dynamically and displays the augmented images in the browser.
- recognition.py - This `HTML` file creates a webpage that allows users to upload an image, display it, and use the MobileNet model (via TensorFlow.js) to classify the image and display recognition results on the page.
- app.py - The `app.py` file is a Flask application that uploads images, applies horizontal flip augmentation using OpenCV, and displays the original and augmented images via HTML templates.
- Dataset - Data to perform augmentation and recognition.

## Contributions
Feel free to fork this repository and make contributions. Pull requests are welcome!
