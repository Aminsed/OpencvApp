# Digit Recognizer Web App

This is a web application that allows users to draw a digit on a canvas and get a prediction of the drawn digit using a pre-trained machine learning model. The app is built using Streamlit, a Python library for creating interactive web applications, and is deployed on Heroku.

## Features

- Interactive canvas for drawing digits
- Real-time digit recognition using a pre-trained ONNX model
- Displaying the recognized digit and confidence score
- Option to clear the canvas and draw a new digit
- User-friendly interface with instructions

## Demo

Check out the live demo of the Digit Recognizer app: [https://ocv-amin-1f420cd78a19.herokuapp.com/](https://ocv-amin-1f420cd78a19.herokuapp.com/)

## Technologies Used

- Python
- Streamlit
- OpenCV
- NumPy
- ONNX Runtime
- Heroku

## Installation

To run the app locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Aminsed/OpencvApp.git
   ```

2. Navigate to the project directory:
   ```
   cd digit-recognizer
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the app:
   ```
   streamlit run cv_web_app.py
   ```

5. Open your web browser and visit `http://localhost:8501` to access the app.

## Deployment

The app is deployed on Heroku, a cloud platform for hosting web applications. To deploy your own instance of the app, follow these steps:

1. Create a Heroku account and install the Heroku CLI.

2. Create a new Heroku app:
   ```
   heroku create your-app-name
   ```

3. Push the code to Heroku:
   ```
   git push heroku main
   ```

4. Open the app in your web browser:
   ```
   heroku open
   ```

## File Structure

- `cv_web_app.py`: The main Streamlit app file that contains the user interface and prediction logic.
- `utils.py`: Utility functions for image processing and digit prediction.
- `model.onnx`: The pre-trained ONNX model for digit recognition.
- `setup.sh`: Shell script for configuring Streamlit on Heroku.
- `requirements.txt`: List of required Python packages.
- `Readme.md`: This readme file.

## Acknowledgements

- The pre-trained ONNX model used in this app is based on the MNIST dataset.
- The app is built using the Streamlit library and deployed on Heroku.
