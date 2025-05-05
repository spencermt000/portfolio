# Classifying and Predicting Stunts
## Overview
This project focused on identifying and classifying pass rush stunts—a key defensive tactic in football—using player tracking data from the NFL Big Data Bowl. The goal was to automate the detection of stunts across thousands of plays to enable deeper player evaluation and defensive analysis. I began by cleaning and preprocessing the raw player tracking data in R, then visualized every pass rush snap to highlight defenders’ movement paths. To generate labeled training data, I developed an interactive Shiny app that allowed for manual classification of 200 plays based on visual inspection of rush patterns. The core of the modeling pipeline was a fusion model built in Python that combined a convolutional image classification model (trained on visual representations of the plays) with a gradient boosted model leveraging tabular features. This hybrid approach achieved 76% accuracy on a held-out test set. After applying the model to the full dataset, I used the predicted stunt classifications to isolate and analyze performance on those plays—opening up avenues for assessing player impact in complex defensive schemes. Potential future improvements include integrating more features, incorporating raw tracking data directly into the model to reduce classification noise, and expanding the labeled training dataset for better generalization. 

## Example
![image](https://github.com/user-attachments/assets/33084bee-a7f4-4ec1-ac19-782d69b6932b)

## Shiny App to Manually Classify
![image](https://github.com/user-attachments/assets/533d8769-ff77-4eb0-a3bd-b0847118fffb)

## Model Performance
![image](https://github.com/user-attachments/assets/6be0f21d-19ee-4718-8862-30690d62cb36)

## End Goal: Player Evaluation
![image](https://github.com/user-attachments/assets/b22b7dd8-06e3-4fa0-8dbf-c3c70e416551)

