
# IPL Win Predictor

This project is a web application that predicts the probability of winning for a batting team in an IPL match. The prediction model is built using historical IPL data and is implemented with Python and Streamlit for the web interface.

## Overview
The IPL Win Predictor uses a machine learning model to predict the probability of a team winning a match based on current match statistics such as the score, overs completed, wickets lost, and more. The application is built using Python and uses Streamlit for creating the web interface.

## Features
- Predict the probability of winning for a batting team.
- Input various match statistics such as target score, current score, overs completed, and wickets lost.
- Displays the probability of both the batting and bowling team winning.

## Installation
To run the IPL Win Predictor locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/IPL-win-predictor.git
    cd IPL-win-predictor
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Run the Streamlit app**:
    ```sh
    streamlit run app.py
    ```

## Usage
1. Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).
2. Select the batting team, bowling team, and the host city.
3. Enter the target score, current score, overs completed, and wickets lost.
4. Click the "Predict Probability" button to see the winning probabilities.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For building and evaluating the machine learning model.
- **Streamlit**: For creating the web application interface.
- **Pickle**: For saving and loading the trained model.
