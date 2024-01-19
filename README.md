# MNIST Convolutional Neural Network (CNN) with Keras

This repository contains a simple Convolutional Neural Network (CNN) implemented using Keras for the MNIST dataset. The code includes data loading, preprocessing, model building, training, and evaluation.

## Requirements
- Python 3
- Numpy
- Matplotlib
- Keras
- Scikit-learn

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Parag-khandelwal/CNN-on-MNIST-Dataset.git
    cd CNN-on-MNIST-Dataset
    ```


## Description

- **Data Loading:** The MNIST dataset is loaded using Keras's `mnist.load_data()` function.
  
- **Data Visualization:** Matplotlib is used to visualize a sample image from the dataset.

- **One-Hot Encoding:** Labels are one-hot encoded to prepare the data for classification.

- **Normalization:** Image data is normalized to ensure values are between 0 and 1.

- **Reshaping:** Data is reshaped to include color channels for CNN compatibility.

- **Model Architecture:** A simple CNN model is built using Keras with Convolutional, Pooling, Flattening, Dense, and Output layers.

- **Model Compilation:** The model is compiled with categorical crossentropy loss and RMSprop optimizer.

- **Training:** The model is trained on the training data for 5 epochs.

- **Evaluation:** Model performance is evaluated on the test data, showing loss and accuracy.

- **Model Saving:** The trained model is saved to a file named `mnist_cnn.h5`.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



