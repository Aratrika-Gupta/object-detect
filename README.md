# Object Detection with TensorFlow Hub

## Overview

This project demonstrates how to use TensorFlow Hub's pre-trained object detection models to identify and label objects in images. We utilize TensorFlow's efficient APIs and TensorFlow Hub's model repository to perform object detection and visualize results.

## Features

- **Image Downloading:** Automatically download and resize images for processing.
- **Object Detection:** Use a TensorFlow Hub model to detect objects in images.
- **Bounding Box Visualization:** Draw bounding boxes and labels on detected objects.
- **GPU Support:** Leverage available GPU devices for faster inference.

## Technologies Used

- **Programming Language:** Python
- **Machine Learning Framework:** TensorFlow
- **Pre-trained Model:** TensorFlow Hub's Faster R-CNN model
- **Image Processing Libraries:** PIL (Pillow), NumPy
- **Visualization:** Matplotlib

## Troubleshooting

GPU Device Not Available: Ensure you have the necessary CUDA and cuDNN libraries installed for TensorFlow to use GPU.
Font Issues: If the specified font file is not found, the code will fall back to a default font.
Contributing

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

TensorFlow and TensorFlow Hub for their pre-trained models and APIs.
Matplotlib and Pillow for visualization and image processing capabilities.
https://www.tensorflow.org/hub/tutorials/object_detection for its tutorial.
