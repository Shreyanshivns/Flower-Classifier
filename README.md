# Flower-Classifier using CNN

This project demonstrates how to create a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images of flowers into five categories: roses, daisies, dandelions, sunflowers, and tulips.

## Dataset

The dataset used in this project is the [Flower Photos](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz) dataset, which contains images of various flowers categorized into five classes.

## Project Structure

1. **Data Loading and Preparation**:
    - Download and extract the dataset.
    - Organize the dataset into training and validation directories with an 80-20 split.

2. **Data Augmentation**:
    - Apply various augmentation techniques such as random horizontal flips, rotations, and zooms to the training images to increase the dataset size and variability.

3. **Model Creation**:
    - Define a CNN model with multiple convolutional layers, max-pooling layers, dropout layers, and dense layers.
    - Compile the model with the Adam optimizer and Sparse Categorical Crossentropy loss function.

4. **Model Training**:
    - Train the model using the augmented training data and validate it using the validation data.
    - Plot training and validation accuracy and loss over epochs to visualize the training process.

## Requirements

- TensorFlow
- NumPy
- Matplotlib

You can install the required packages using the following command:

```bash
pip install tensorflow numpy matplotlib
```

## Usage

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory**:
    ```bash
    cd flower-classification
    ```

3. **Run the script**:
    ```bash
    python flower_classification.py
    ```

## Results

The training and validation accuracy and loss will be plotted after the model finishes training, allowing you to visualize the model's performance.

## Acknowledgments

- The dataset is provided by [TensorFlow Datasets](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz).
- This project is inspired by the TensorFlow tutorials and documentation.

Feel free to modify and expand this project to improve the model's performance or adapt it to different datasets.
