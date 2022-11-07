# Train a Sentiment Detection Model


## Description
An experimentation to train a custom object detection model to understand how to differentiate a car with a happy face vs. unhappy face. The genesis of this experiment stems from a biometric study of the hidden-human experience of the built environment. More specifically, it relates to people's perceptions and emotional responses to the facial expressions/front views of cars. 

## Challenges
- Troubleshoot a whole bunch of errors during installations and set up
- resolve errors raised during installation of the TFOD API
- To resolve Runtime errors generated from the PC using CPU, I eventually switched over to the cloud to run and train the model to use GPU and high-RAM to complete the project.
- Project underwent several rounds of performance tuning: 1. scaled up my dataset for both training and testing; 2. modified image size & resolution.


## Outcome

Prediction accuracy metrics obtained 82.8% mean average precision, 87% average recall, and less than 4% total loss.
