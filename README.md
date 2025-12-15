# CNN on Fashion-MNIST Dataset via PyTorch

## Overview
This project demonstrates the implementation of a Convolutional Neural Network (CNN) to classify images from the Fashion-MNIST dataset using PyTorch. The Fashion-MNIST dataset is a collection of 28x28 grayscale images of 10 different categories of clothing and accessories, designed as a drop-in replacement for the classic MNIST dataset.

## Features
- Data preprocessing and augmentation.
- Building and training a CNN model using PyTorch.
- Evaluation of the model's performance on test data.
- Visualization of training metrics and predictions.

## Files
- `CNN.ipynb`: Jupyter Notebook containing the implementation of the CNN model.
- `CNN_transfer_learning.ipynb`: Jupyter Notebook demonstrating transfer learning techniques on the Fashion-MNIST dataset.

## Requirements
To run the notebooks, ensure you have the following installed:
- Python 3.8 or higher
- PyTorch
- torchvision
- matplotlib
- numpy
- Jupyter Notebook or JupyterLab

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CNN_on-fashion-mnist-dataset-via-pytorch.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CNN_on-fashion-mnist-dataset-via-pytorch
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Select either `CNN.ipynb` or `CNN_transfer_learning.ipynb` to explore the implementation.
3. Run the cells sequentially to train and evaluate the model.

## Results
The model achieves a high accuracy on the Fashion-MNIST test dataset. Training and evaluation metrics are visualized within the notebooks.

## Acknowledgments
- The Fashion-MNIST dataset is provided by Zalando Research.
- PyTorch is an open-source machine learning library developed by Facebook's AI Research lab.

## License
This project is licensed under the MIT License. See the LICENSE file for details.