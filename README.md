# CompetitionHology7.0

## Overview

This is a machine learning model designed to predict the color and type of shirts from images. The model utilizes Convolutional Neural Networks (CNN) and the VGG-16 architecture for effective feature extraction and classification. 

## Features

- **Image Classification:** Predicts shirt type (t-shirt or hoodie) and color (red, yellow, blue, black, white) from input images.
- **VGG-16 Architecture:** Leverages the power of VGG-16 for robust image feature extraction.
- **Data Handling:** Organizes images based on shirt type and color labels to improve training efficiency.

## Requirements

To run this project, you'll need:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- imblearn
- PIL

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CompetitionHology7.0.git
   cd CompetitionHology7.0

2. Install the required package
3. After training, use the prediction script to classify new images
   ```bash
   python predict.py --image_path path/to/your/image.jpg


## Model Architecture
The model is built on the VGG-16 architecture, which includes:
- Convolutional layers
- MaxPooling layers
- Fully connected layers
The model has been fine-tuned for optimal performance on the shirt classification task.

