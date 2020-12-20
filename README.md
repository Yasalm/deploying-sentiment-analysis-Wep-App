# SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.


# Project Overview 
- The below diagram shows how the deployed endpoint - model - communicates to the app, The app here serves as interfce to get reviews data from the user, And through API gateway, Lambda we pass the data and get a predction back in binary [1, 0].
>>> - 1: Postive.
>>> - 0: Negative.

>>>![Diagram](Web%20App%20Diagram.svg)
