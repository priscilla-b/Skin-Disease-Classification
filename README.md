# Azubi Africa Data Science Hackathon: Team 12 - Skin Disease Classification

This project was submitted for the Data Science Hackathon of the Azubi Africa Training program. This is an image classification project that is built with the Microsoft Azure Computer Vision service. An alternative skin disease classification model was also built in Jupyter notebooks, but we settled on the Computer Vision model due to it's higher performance. 

The computer vision model was connected with a bot we built with the Microsoft Bot Framework Composer. The Bot, which we call DermDoc interacts with users and helps them upload an image of skin disease they're facing. That image is then sent to the computer vision model for a prediction, through an API. The prediction is relayed back to the user through a prediction API, alongise with some recommendation on the treatment of the skin disease.


# How to use

To use this project, first clone or fork the files to your local computer.
Section 5.2.1 of the documentary shows a step by step approach on how we built the computer vision model on the Microsoft Azure platform.
File: data_preparation.ipynb
------------------------------
This file contains the codes we used to preprocess the data for the model in the jupyter notebooks. Only use this file if you want to run Script.ipynb, which contains the jupyter notebook codes.
