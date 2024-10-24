# Dogs vs. Cats Image Classification

This repository implements a Convolutional Neural Network (CNN) model to classify images of dogs and cats.

## Features:

- Utilizes TensorFlow and Keras for building and training the model.
- Performs image data augmentation for training data (random shearing, zooming, and horizontal flipping) to improve model robustness.
- Uses a CNN architecture with convolutional and pooling layers for feature extraction, followed by dense layers for classification.
- Trains the model on a dataset of dog and cat images.
- Predicts the class (dog or cat) of a new image.

## Requirements:

* Python 3.x
* Libraries: TensorFlow, Keras, numpy

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Dogs-Cats-Image-Prediction.git
2. **Install Libraries:**
   ```bash
   pip install tensorflow keras
3. **Prepare Data:**
   -This specific project utilizes the Dogs vs. Cats dataset, readily available on Kaggle:
   Download Link: [cat-and-dog](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
   - Download the dataset, change the directory name to `Dogs_Cats` containing two subdirectories: `training_set` and `test_set`.
   - These subdirectories should further contain folders named `dogs` and `cats` with their respective images.
5. **Run the Notebook:**
   Open the `Dogs_Cats_ImagePrediction.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Note:

- This is a basic example using a simple CNN architecture. You can explore more complex architectures and hyperparameter tuning for better performance.
- The script assumes the data directory structure mentioned above.

Feel free to explore and adapt the code for your own image classification tasks!
