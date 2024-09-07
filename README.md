# Brain Tumor Detection

The Brain Tumor Detection Application is a cutting-edge solution built on machine learning principles, specifically leveraging Convolutional Neural Networks (CNNs), to accurately distinguish between four types of brain tumors: **Normal**, **Glioma**, **Meningioma**, and **Pituitary**.

## Key Features

- **Convolutional Neural Networks (CNNs)**: Utilizes CNNs for high-accuracy classification of brain MRI scans into four categories.
- **Automated Detection**: Predicts the presence and type of brain tumor based on MRI images, offering fast and reliable diagnostic assistance.
- **User-Friendly Interface**: A web-based front-end ensures easy interaction, allowing users to upload MRI scans and receive predictions.
- **Comprehensive Data Handling**: Supports both training and testing datasets, facilitating model improvements and accurate predictions.

## Project Structure

- **backend/**: Contains Python code for CNN model training, prediction, and data processing.
  - **model.py**: Defines the CNN architecture and training process.
  - **predict.py**: Loads the trained model and performs predictions on MRI scans.
  - **utils.py**: Helper functions for data preprocessing and visualization.
- **dataset/**: Placeholder for training and testing datasets (replace with your data source).
- **frontend/**: HTML, CSS, and JavaScript code for the user interface.
  - **index.html**: Main HTML template for the web application.
  - **style.css**: Stylesheet for the user interface.
  - **script.js**: JavaScript code for handling user interaction and communication with the backend.

## Requirements

- **Python 3.x** (with libraries like TensorFlow, Keras, NumPy)
- **Node.js** (for running a local server for the front-end)


