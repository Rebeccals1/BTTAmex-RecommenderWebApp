# American Express: Attentive Recommendation Web Application
This project was part of the Break Through Tech AI program, which connects students from different experiences to help launch a generation of diverse tech talent into the workforce. This simple web application is meant to showcase our ML model. It displays a list of mock users to click on, then takes you to a separate page to display their product purchase history, along with a list of products recommended for that user based on their purchase history.

For more information about the ML model itself, you can find the original repository here: https://github.com/ardahk/amex.

## Features
* A recommendation system that uses a two-tower model with attention mechanisms.
* Generates six random users from the User csv file. Once created and locally stored, it will then load each user from that newly created json file.

## Tech Stack
* Python
* Streamlit
* Pandas
* Tensorflow
* Keras
* Json

## Running locally
To run this application locally, make sure to run the following in your local environment:

``pip install -r requirements.txt``

Then run the Streamlit app locally with the following:

``streamlit run app.py``
