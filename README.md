# Kaggle Practice Notebooks

Machine learning notebooks I built on Kaggle while studying Artificial
Intelligence. Each notebook can be viewed directly on GitHub with all outputs.

## Notebooks

### 1. Heart Failure Prediction (`heart-failure-classification.ipynb`)
- **Task:** binary classification, predicting heart disease from clinical
  features (age, blood pressure, cholesterol, ECG results, etc.)
- **Methods:** data cleaning and feature selection, scaling and one-hot
  encoding with scikit-learn, a neural network in TensorFlow/Keras,
  hyperparameter tuning with Keras Tuner, evaluation with a confusion matrix
  and classification report
- **Dataset:** [Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

### 2. Flight Price Prediction (`flight-price-regression.ipynb`)
- **Task:** regression, predicting the ticket price of a flight from features
  such as airline, route, departure time, number of stops, class and days
  left before departure
- **Methods:** feature encoding, a neural network in TensorFlow/Keras trained
  with mean squared error loss and evaluated with mean absolute error
- **Dataset:** [Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

### 3. Car or Truck? (`car-or-truck-cnn.ipynb`)
- **Task:** binary image classification, car vs truck
- **Methods:** convolutional neural network in TensorFlow/Keras

### 4. Convolution Filters (`convolution-filters-experiments.ipynb`)
- **Task:** understanding how a CNN extracts features from an image
- **Methods:** applying different convolution kernels (filters) to the
  car-or-truck images and visualising the result, to see how each kernel
  detects edges, lines and other patterns

Notebooks 3 and 4 use these datasets:
[Car or Truck?](https://www.kaggle.com/datasets/ryanholbrook/car-or-truck),
[Computer Vision Resources](https://www.kaggle.com/datasets/ryanholbrook/computer-vision-resources),
[CV Course Models](https://www.kaggle.com/datasets/ryanholbrook/cv-course-models)

## Data

The datasets are not included in this repository. They are available on
Kaggle via the links above, and all credit goes to their original authors.
The computer vision datasets come from Kaggle Learn's
[Computer Vision course](https://www.kaggle.com/learn/computer-vision).

The notebooks read data from `/kaggle/input/...`, so they run as-is on Kaggle.
To run one locally, download the dataset and change the data path at the top
of the notebook.

## Tools

Python, pandas, NumPy, scikit-learn, TensorFlow/Keras, Keras Tuner,
Matplotlib, seaborn

## Other projects

- [Olist marketplace analysis in R](https://github.com/DogeWinner/olist-r-portfolio):
  delivery, reviews and seller segmentation on 96k e-commerce orders