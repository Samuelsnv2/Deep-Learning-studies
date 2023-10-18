# Fashion MNIST CNN Classifier

This directory contains code for training a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset. The Fashion MNIST dataset consists of 60,000 training images and 10,000 test images, each of size 28x28 pixels, belonging to 10 different categories.

## Prerequisites

Make sure you have the following libraries installed:

```bash
pip install -r requirements.txt
```

## Usage
### Training the Model
1. Run **`fashion_mnist_cnn.ipynb`** to train the CNN model.
2. The trained model will be saved as fashion_model.h5.
### Testing the Model
1. To test the trained model, place your test images in the  **`image_test`** directory.
2. Run **`test_fashion_cnn.ipynb`** to load the trained model and test it on the provided images.

## File Descriptions
- **`fashion_mnist_cnn.ipynb`**: Jupyter Notebook containing code  for training the CNN model.
- **`test_fashion_cnn.ipynb`**: Jupyter Notebook for testing the trained CNN model on custom images.

## Model Architecture
The CNN model architecture is as follows:

1. Convolutional layer with 32 filters, kernel size (3,3), and ReLU activation.
2. MaxPooling layer with pool size (2,2).
3. Flatten layer.
4. Dense layer with 100 units and ReLU activation.
5. Output layer with 10 units (for 10 classes) and softmax activation.

## Results
The trained model achieved an accuracy of approximately 91% on the test data.

## Testing Custom Images
You can test the trained model on your own images by placing them in the image_test directory and running **`test_fashion_cnn.ipynb`**. The model will predict the class of each image and display the results.