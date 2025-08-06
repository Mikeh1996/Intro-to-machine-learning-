# Intro-to-machine-learning-

## Inspiration
This project focuses on building a machine learning model to support a mobile carrier, Megaline, in recommending optimal mobile plans (Smart or Ultra) to subscribers. The model is trained on user behavior data to predict which plan best suits each customer. This is my first solo machine learning classification project involving train/validation/test splitting, hyperparameter tuning, and sanity checks to ensure model reliability.

## Problem Statement
Megaline is transitioning users from legacy mobile plans to two modern offerings: Smart and Ultra. The goal is to develop a classifier that predicts which plan a user should switch to based on monthly behavioral data, including:

- Number of calls
- Total minutes used
- Number of text messages
- Internet usage in MB

The target variable is `is_ultra`, a binary indicator of whether the user chose the Ultra plan (`1`) or the Smart plan (`0`).

## Project Goals
- Build a classification model to predict the most suitable plan
- Maximize accuracy, targeting a minimum threshold of 0.75
- Compare multiple models and tune hyperparameters
- Perform a final evaluation on the test set and sanity-check the results

## Key Questions Explored
- Which classification model performs best at predicting plan type?
- What are the most important behavioral features driving plan selection?
- How do different hyperparameters affect model performance?
- How well does the model generalize to unseen data?
- Does the model produce logical results under sanity checks?

## What I Learned from This Project
This project helped me bridge theory and practice in supervised machine learning. Key lessons included:

- Structuring a clean ML workflow with data splits and evaluation
- Training and comparing multiple classification models
- Tuning hyperparameters to improve performance
- Evaluating results with accuracy and sanity checks
- Understanding the impact of user behavior on business recommendations
- Improving confidence in decision-making based on model output

## How to Run the Project Locally
Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/megaline-plan-recommendation.git
cd megaline-plan-recommendation