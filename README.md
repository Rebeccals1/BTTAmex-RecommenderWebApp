# American Express: Attentive Recommendation Web Application
Break Through Tech is an organization that tries to empower diverse students to participate in a year program to learn more about Machine Learning and AI. In this program, I was assigned a wonderful team that collaborated with an American Express Advisor, who helped guide us through this challenging project. The goal assigned to us involved making a two-tower recommendation model. I helped create this simple web application in order to showcase our ML model. The application displays a list of mock users. When a name is clicked, it takes you to a separate page where it will display the User ID and their purchase history. It will then load a recommended list of up to five products based upon the user's id number and purchased history.

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
