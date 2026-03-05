# Airport and Airline Choice Modeling using Machine Learning

This project analyzes passenger decision behavior in airport and airline selection using survey data. The goal is to understand the factors influencing travel decisions and build predictive models for airport and airline choice.

## Project Objectives

The project focuses on two prediction tasks:

1. **Airport Choice Prediction**  
   Predict which airport a passenger chooses based on travel characteristics, costs, and demographic information.

2. **Airline Choice Prediction**  
   Predict which airline a passenger selects among multiple alternatives.

## Dataset

The dataset contains passenger survey responses including:

- Demographic information (age, gender, nationality, income)
- Travel characteristics (trip purpose, trip duration, destination)
- Flight information (airfare, departure time, seat class)
- Transportation access (mode of transport, access time, access cost)
- Travel history (number of trips, frequent flight destination)

Total observations: **488 passengers**

## Machine Learning Models Used

For **Airport Choice Prediction**:
- Logistic Regression
- Decision Tree
- Random Forest

For **Airline Choice Prediction**:
- Multinomial Logistic Regression
- Random Forest

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC (for airport choice)

## Key Results

- **Random Forest performed best for Airport Choice with ~93% accuracy**
- **Random Forest performed best for Airline Choice with ~67% accuracy**

## Important Factors Influencing Passenger Choice

Key variables affecting airport and airline selection include:

- Destination
- Airfare
- Departure time
- Trip duration
- Access cost and access time
- Passenger demographics (age, income)

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## Project Structure
