# American Express: Attentive Recommendation Web Application
I was part of a team in the Break Through Tech AI program and this was one of the projects assigned to us. The Break Through Tech program tries to connect students from different experiences in order to help launch a generation of diverse tech talent into the workforce. We partnered with an American Express Advisor to help guide us through this challenging project. I helped create this simple web application in order to showcase our ML model. It displays a list of mock users to click on, then takes you to a separate page to display their product purchase history, along with a list of products recommended for that user based on their purchased history.

For more information about the Two-Tower Recommendation model itself, you can find the original repository here: https://github.com/ardahk/amex.

## Features
* A recommendation system that uses a two-tower model with attention mechanisms.
* Generates six random users from the User csv file. Once created and locally stored, it will then load each user from the newly created json file.

## Tech Stack
* Python
* Streamlit
* Pandas
* Tensorflow
* Keras

## Running locally
To run this application locally, make sure to run the following in your local environment:

``pip install -r requirements.txt``

Then run the Streamlit app locally with the following:

``streamlit run app.py``
