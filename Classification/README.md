# Penguin Prediction App

This Streamlit web application predicts the species of Palmer penguins based on user input features. It utilizes a machine learning model trained on the Palmer penguins dataset.

## Overview

The Palmer penguins dataset provides measurements of bill length, bill depth, flipper length, body mass, island, and sex for different penguin species: Adelie, Chinstrap, and Gentoo.

## How to Use

1. **Input Features**: Users can input the following features through the sidebar:
   - Island: Select the island where the penguin was observed.
   - Sex: Select the sex of the penguin.
   - Bill length (mm): Adjust the slider to input the bill length.
   - Bill depth (mm): Adjust the slider to input the bill depth.
   - Flipper length (mm): Adjust the slider to input the flipper length.
   - Body mass (g): Adjust the slider to input the body mass.

2. **Prediction**: The app predicts the species of the penguin based on the provided input features.

## Data Sources

- [Palmer Penguins Dataset](https://github.com/allisonhorst/palmerpenguins): The dataset contains measurements and information on three species of penguins observed on three islands in the Palmer Archipelago, Antarctica.

## Technologies Used

- Streamlit: A popular Python library for building interactive web applications.
- pandas: Data manipulation library for Python.
- scikit-learn: Machine learning library for Python.

## Setup

To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Hitanshuser50/Streamlit.git
   ``` 
2. Navigate to the project directory:
   ```bash
    cd Streamlit
   ```
3.Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4.Run the streamlit application 
  ```
   streamlit run app.py
  ```

Note : if you have done some modification the rebuild the model by Running the Python file till then i am also uploding the pkl file and then Procced with the above Setup  



