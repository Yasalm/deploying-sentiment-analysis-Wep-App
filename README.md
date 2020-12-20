# SageMaker Deployment Project

Building recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. created the model by using Amazon's SageMaker service. In addition, deploying the model and construct a simple web app which will interact with the deployed model.


# Project Overview 
- The below diagram shows how the deployed endpoint - model - communicates to the app, The app here serves as interfce to get reviews data from the user, And through API gateway, Lambda we pass the data and get a predction back in binary [1, 0].
>>> - 1: Postive.
>>> - 0: Negative.

>>>![Diagram](Web%20App%20Diagram.svg)
