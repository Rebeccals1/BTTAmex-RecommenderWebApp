# American Express: Attentive Recommendation Web Application
Break Through Tech is an organization that tries to empower many diverse students. They do this by having them participate in a year long program designed to help them learn Machine Learning. In this program, our goal was to makie a two-tower recommendation model. To help guide us through this process, our team collaborated with an American Express Advisor.

As a side project, I created this simple web application to help showcase the teams ML model. This application displays a list of mock users. Then, when a name is clicked, it takes you to a profile page where it will display the User ID, image and purchase history. After some time, it will then load a list of up to five recommended products based upon the user's id number and purchased history.

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
