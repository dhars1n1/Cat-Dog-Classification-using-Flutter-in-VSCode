# Cat-Dog Classification using Flutter in VSCode

This repository contains the code for a mobile application developed using Flutter and VSCode that classifies images of cats and dogs. 

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Docker Integration](#docker-integration)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

This project demonstrates the use of Flutter to create a mobile application capable of classifying images as either a cat or a dog. It leverages a machine learning model trained to recognize and differentiate between cats and dogs.

## Features

- User-friendly interface
- Real-time image classification
- Supports image capture from camera and gallery
- High accuracy using a pre-trained machine learning model

## Installation

Follow these steps to get the project up and running on your local machine:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/dhars1n1/Cat-Dog-classification-using-flutter-in-vscode.git
    cd Cat-Dog-classification-using-flutter-in-vscode
    ```

2. **Install Flutter:**
    Follow the official [Flutter installation guide](https://flutter.dev/docs/get-started/install).

3. **Install dependencies:**
    ```bash
    flutter pub get
    ```

4. **Run the app:**
    ```bash
    flutter run
    ```

## Usage

Once the application is running, you can:

1. Select an image from your gallery or capture a new one using your device's camera.
2. The app will process the image and display whether it is a cat or a dog.

## Model

The classification model used in this project is a pre-trained convolutional neural network (CNN). The model is trained using a dataset of cat and dog images. You can replace the existing model with your own by following these steps:

1. Train your model using a preferred machine learning framework (e.g., TensorFlow, PyTorch).
2. Convert the trained model to TensorFlow Lite format.
3. Replace the existing model file in the `assets` directory with your model.

## Docker Integration

This project also includes a Docker setup for running a Flask server that can handle image uploads and classifications.

### Docker Repository

You can find the Docker image for the Flask server at:
[Docker Hub - dhars1n1/flask_docker](https://hub.docker.com/repository/docker/dhars1n1/flask_docker/general)

### Deployed Flask App

The Flask application is deployed and can be accessed at:
[Flask Docker App](https://flask-docker-vz33dvwhnq-uc.a.run.app/upload)


## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Contact

For any questions or inquiries, please contact:

- **Name:** Dharsini Sri
- **Email:** purpleunalome@gmail.com
- **GitHub:** [dhars1n1](https://github.com/dhars1n1)


https://github.com/dhars1n1/classifier/assets/161904561/cce6826d-4061-4c77-8f65-f710c9250664
