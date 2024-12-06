# American Express: Attentive Recommendation Web Application
Break Through Tech is an organization that tries to empower many diverse students by participating in a year long program designed to help them learn and understand all AI & about Machine Learning. In this program, our team collaborated with an American Express Advisor who helped guide us through this challenging project. The goal assigned to us involved making a two-tower recommendation model. I created this simple web application to showcase our ML model. The application displays a list of mock users. Then, when a name is clicked, it takes you to a profile page where it will display the User ID, image and purchase history. After some time, it will then load a list of up to five recommended products based upon the user's id number and purchased history.

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
