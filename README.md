# AI-Trash-Classifier
An AI-powered web application that identifies and classifies types of trash from user-uploaded images, designed to support better waste sorting and recycling efforts.

# Overview
This application will use the CNN model, which is built using TensorFlow. It will categorize the images of trash into various categories. The model has been trained on the labeled dataset from Kaggle to be able to recognize common types of waste. A web server connects a model to a HTML/CSS/JavaScript front-end. Users are able to upload an image and get real-time prediction about trash type.

Features
Image Classification: Classifies images of trash into categories, aiding waste management efforts.
User-Friendly Interface: Simple web interface built with HTML, CSS, and JavaScript for easy image uploads and results display.
Real-Time Prediction: Fast, accurate results powered by a trained CNN model integrated with Flask.
Installation
Clone this repository.
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Start the Flask server:
bash
Copy code
python app.py
Usage
Launch the app by navigating to http://localhost:5000.
Upload an image of trash through the interface.
Receive an immediate prediction of the trash type.
Technologies Used
TensorFlow: For training and running the CNN model.
Flask: For connecting the front end with the model logic.
HTML/CSS/JavaScript: For building the web interface.
Acknowledgements
Dataset from Kaggle: https://www.kaggle.com/datasets/techsash/waste-classification-data?resource=download
