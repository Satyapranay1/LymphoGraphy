# Lymph Classification with Random Forest Classifier

## Overview
This project implements a **Random Forest Classifier** to accurately classify different types of lymphs in a given dataset. The model has been optimized through hyperparameter tuning to improve classification performance, and it is integrated with a **Flask** application to provide an easy-to-use web interface for end users.

## Features
- **Random Forest Classifier** for lymph classification.
- **Hyperparameter tuning** that improved model accuracy from **83.3% to 87%**.
- **Flask-based web interface** for real-time classification results.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/lymph-classification
    cd lymph-classification
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

4. Open your browser and go to `http://127.0.0.1:5000/` to interact with the application.

## Dataset
The dataset used for this project contains information on various types of lymphs, which serves as the input to the model for classification.

## Model Details
- The model was built using **Random Forest Classifier** from scikit-learn.
- Initial model accuracy: **83.3%**
- After hyperparameter tuning: **87%**
  
Hyperparameters like the number of trees and maximum depth were fine-tuned to achieve better performance.

## Flask Application
The model is integrated with a **Flask** web app to allow users to input data and get real-time predictions.

## How to Use
1. Open the Flask application in a browser.
2. Enter the required input values for lymph classification.
3. Click the 'Predict' button to get the classification results.

## Future Work
- Improve the model by testing other classification algorithms.
- Add more detailed analytics and visualization for user predictions.
- Expand the dataset for more diverse classification tasks.
