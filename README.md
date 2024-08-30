# Mars Landmark Detection Project

This project focuses on developing a deep learning model using TensorFlow and Keras to detect landmarks in images of Mars. The model is trained to classify images into one of eight classes representing different Martian landmarks.

## Project Overview

The exploration of Mars has become a significant area of interest for scientists and space agencies worldwide. Understanding the terrain and landmarks on Mars is crucial for planning missions and conducting research on the Red Planet. This project aims to automate the process of identifying landmarks in Martian images, facilitating the analysis of Martian surface features.

## Key Features

- **Automated Landmark Detection**: The deep learning model automates the process of detecting landmarks in images of Mars, reducing the need for manual inspection and analysis.
  
- **Classification of Martian Landmarks**: The model classifies images into eight classes representing various Martian landmarks, including craters, valleys, mountains, and plateaus. This classification provides valuable insights into the geological features of Mars.

- **Scalability**: The project is designed to handle a large volume of image data, making it scalable for processing vast datasets of Martian images captured by orbiters, rovers, and other spacecraft.

- **Open-Source**: The project is open-source, allowing researchers, scientists, and enthusiasts to contribute, collaborate, and extend the capabilities of the landmark detection model.

## Why It's Important

- **Scientific Research**: Accurately identifying and classifying Martian landmarks is essential for conducting scientific research on Mars, including studying its geological history, climate, and potential for supporting life.

- **Mission Planning**: Landmark detection assists in mission planning for future Mars exploration missions, enabling scientists to identify suitable landing sites, navigation routes, and areas of scientific interest.

- **Data Analysis**: Automated landmark detection streamlines the analysis of Martian image data, enabling researchers to extract valuable information efficiently and effectively.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Jupyter Notebook

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone [repository-url]

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
## Usage

3. Open and run the `model.ipynb` notebook in Jupyter Notebook:

   ```bash
   jupyter notebook model.ipynb
Follow the instructions in the notebook to train the model and evaluate its performance.

To use the model:

Access the architecture.json file to create a model with the same architecture. 
The architecture is also available in the model.ipynb file.
After creating the model, load the weights from the my_model.weights.h5 file.
Use the model to predict the landmark in an input image by calling the prediction function with the image path.


## Dataset

The dataset consists of:

- 8,200 training images
- 2,000 testing images

The images depict various landmarks on Mars, categorized into eight classes.

## Model Architecture

The deep learning model architecture used for this project comprises:

- **Convolutional Base**: VGG16 with pre-trained weights from ImageNet.
- **Flatten Layer**: To convert the 2D matrix into a 1D vector.
- **Dense Layers**:
  - 256 units with ReLU activation
  - 128 units with ReLU activation
  - 8 output units with softmax activation for classification.

## Results

After training the model, it achieved an accuracy of 88% on the training dataset.

## Sample Images

The project includes a directory named `test`, which contains sample images that users can use to test the model's performance. Users can input these images into the model to obtain predictions of the corresponding landmarks.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Adding more training data
- Experimenting with different model architectures
- Enhancing the existing codebase

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Special thanks to contributors who participated in this project.

For any questions or concerns, please contact gorredinesh21@gmail.com .

