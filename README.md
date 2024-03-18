# SageMaker Deployment Project

## Sentiment Analysis Web App Using PyTorch and SageMaker

The notebook and Python files provided here, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. SageMaker is used to construct a complete project from end to end. A simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

![image](https://github.com/Prakarsha01/SentimentAnalysis-SagemakerDeployment/assets/67196711/11ca6a44-1090-4c6a-b9f3-fe3ca7790b6b)

# General Outline
- Download or otherwise retrieve the data.
- Process / Prepare the data.
- Upload the processed data to S3.
- Train a chosen model.
- Test the trained model (typically using a batch transform job).
- Deploy the trained model.
- Use the deployed model.

Sample Output!
![image](https://github.com/Prakarsha01/SentimentAnalysis-SagemakerDeployment/assets/67196711/d1a1d32d-35d8-4b3b-a98c-077d2a1c2513)

---
## Acknowledgments

This project is part of the **Udacity Machine Learning Engineer Nanodegree** course on Udacity. Special thanks to the course instructor for the guidance and inspiration.
