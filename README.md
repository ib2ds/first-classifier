# Bear Classifier

This project is a simple bear classifier that can distinguish between grizzly, black, and teddy bears. It's built using the fast.ai library and can be run as a web application using Voila.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ib2ds/first-classifier/master?urlpath=%2Fvoila%2Frender%2Fbear_classifier.ipynb)

## How to use

You can run the application on Binder by clicking the button above.

Alternatively, you can run it locally:

1.  Clone this repository:
    ```bash
    git clone https://github.com/ib2ds/first-classifier.git
    cd first-classifier
    ```

2.  Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  Run the application:
    ```bash
    voila bear_classifier.ipynb
    ```

4.  Open your browser and go to `http://localhost:8866` to view the application.

## How it works

The application uses a pre-trained model (`export.pkl`) to classify the uploaded image. The model was trained on a dataset of bear images to recognize three categories:

*   Grizzly bears
*   Black bears
*   Teddy bears

The Jupyter Notebook `bear_classifier.ipynb` contains the code for the application. It uses the `fastai` library to load the model and make predictions, and `ipywidgets` to create the user interface.

## File descriptions

*   `bear_classifier.ipynb`: The main Jupyter Notebook that contains the code for the application.
*   `export.pkl`: The pre-trained model used for classification.
*   `requirements.txt`: A list of the Python dependencies required to run the application.
*   `README.md`: This file.