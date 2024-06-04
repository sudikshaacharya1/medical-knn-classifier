# Medical KNN Classifier

This repository contains a Jupyter notebook that implements a K-Nearest Neighbors (KNN) classifier to classify medical data. The notebook includes data loading, preprocessing, model training, evaluation, and prediction based on user input.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Contributing](#contributing)

## Introduction
The purpose of this project is to classify medical data using the KNN algorithm. The notebook ensures reliable performance evaluation by splitting the data into training and testing sets. Additionally, it allows users to input data for real-time predictions.

## Installation
To run this project locally, you need Python and Jupyter Notebook installed. Follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/medical-knn-classifier.git
    cd medical-knn-classifier
    ```

2. **Create and activate a virtual environment (optional but recommended):**
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Start Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```

## Usage
1. **Open the notebook:**
   Open the `Medical_KNN.ipynb` file in Jupyter Notebook.

2. **Run the notebook:**
   Execute the cells in the notebook sequentially. The notebook will:
   - Load and preprocess the dataset.
   - Train the KNN model on the training data.
   - Evaluate the model on the testing data.
   - Allow user input to predict the class of a medicine.

3. **Input data:**
   When prompted, enter the name of a medicine to get its predicted class.

## Code Overview
The main sections of the notebook are as follows:

1. **Import Libraries:**
   Essential libraries such as `numpy`, `pandas`, `sklearn`, etc., are imported.

2. **Load and Preprocess Data:**
   The dataset is loaded and the features are standardized using `StandardScaler`.

3. **Model Training and Evaluation:**
   The dataset is split into training and testing sets. A KNN classifier is trained on the training set and evaluated on the testing set. The accuracy of the model is printed.

4. **User Input and Prediction:**
   The user can input the name of a medicine, and the model will predict its class based on the input.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or submit a pull request.
