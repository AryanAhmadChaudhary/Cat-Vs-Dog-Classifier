# cat-vs-dog-classifie
# Cat vs Dog Classifier

A Convolutional Neural Network (CNN) model built with TensorFlow/Keras to classify images of cats and dogs. This project aims to distinguish between cat and dog images with a simple deep learning approach.

## Model Architecture
The model is built using three convolutional layers, each followed by batch normalization and max pooling layers to extract features from input images. After flattening, the features are passed through fully connected layers to make the final binary classification.

### Model Summary:
- **Input Shape:** (256, 256, 3)
- **Convolutional Layers:** 3 layers with increasing filters (32, 54, 128)
- **Activation:** ReLU for hidden layers, Sigmoid for output
- **Pooling:** MaxPooling with (2, 2) pool size
- **Fully Connected Layers:** 128 and 64 neurons with ReLU
- **Dropout:** 0.1 for regularization
- **Output:** 1 neuron with Sigmoid activation (for binary classification)
