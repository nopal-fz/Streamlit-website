# House Price Prediction with Streamlit

This repository contains a simple web application built with Streamlit for predicting house prices based on various features.

## About

This project aims to provide a user-friendly interface for predicting house prices using a machine learning model. The application allows users to input various features such as the number of bedrooms, bathrooms, square footage, and location, and then provides an estimated price prediction based on these inputs. It utilizes a pre-trained machine learning model that has been trained on historical housing data.

## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Run the Streamlit app with the command `streamlit run main.py`.
5. Open your web browser and navigate to `http://localhost:8501` to view the application.

## Usage

Once the application is running, you can interact with it using your web browser. Enter the desired values for the house features, such as the number of bedrooms, bathrooms, square footage, and location. After entering the necessary information, click the "Predict" button to see the estimated price prediction for the house.

## File Structure

- `app.py`: The main Streamlit application file containing the user interface and prediction functionality.
- `model.sav`: The pre-trained machine learning model saved as a pickle file.
- `requirements.txt`: A list of Python dependencies required to run the application.
- `housing.csv`: The dataset i'm used to this project

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Pickle

## Author

Naufal F

## License

This project is licensed under the [MIT License](LICENSE).
