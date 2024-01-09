# Hand Written Character Recognization
 
This Python code leverages the power of Convolutional Neural Networks (CNNs) to recognize handwritten alphabets. It uses the A-Z Handwritten Dataset and implements a CNN model using the Keras library. The code includes data preprocessing, model training, and evaluation.

## Key Features:

### Data Loading and Preprocessing:

Reads the A-Z Handwritten Dataset and prepares the data for training.

### Data Visualization:

Displays a horizontal bar chart showing the distribution of each alphabet in the dataset.

### Image Visualization:

Plots a 3x3 grid of randomly selected handwritten alphabet images.

### Convolutional Neural Network:

Defines a CNN model using Sequential layers with Conv2D, MaxPool2D, Flatten, and Dense layers.

### Model Training:

Compiles and trains the CNN model using the Adam optimizer and categorical crossentropy loss.

### Model Evaluation:

Displays model summary, saves the trained model, and provides accuracy and loss metrics during training.
